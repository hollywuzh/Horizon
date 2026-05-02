---
layout: default
title: GitHub Actions Deployment
---

# GitHub Actions Deployment

Horizon can run entirely on GitHub Actions: a scheduled workflow fetches recent content, generates Markdown summaries, copies them into the Jekyll docs site, and publishes `docs/` to the `gh-pages` branch for GitHub Pages.

## 1. Fork or Push the Repository

Create your own fork, or push this repository to a GitHub repository you control. Keep `data/config.json` committed, but put API keys and tokens in GitHub Actions secrets rather than in the repository.

## 2. Configure Secrets

In your repository, open **Settings -> Secrets and variables -> Actions -> New repository secret** and add the variables required by `data/config.json`.

The default checked-in config currently needs:

- `DEEPSEEK_API_KEY` for the OpenAI-compatible DeepSeek endpoint
- `APIFY_TOKEN` because Twitter fetching is enabled
- `HORIZON_WEBHOOK_URL` because webhook delivery is enabled
- `LWN_KEY` because the LWN RSS feed uses `${LWN_KEY}`

Optional secrets:

- `HORIZON_GITHUB_TOKEN` if you want the GitHub scraper to use a personal access token instead of the workflow token
- `OPENAI_API_KEY`, `ANTHROPIC_API_KEY`, `GOOGLE_API_KEY`, `MINIMAX_API_KEY`, `DASHSCOPE_API_KEY`, or `DOUBAO_API_KEY` if your `data/config.json` selects those providers
- `EMAIL_PASSWORD` if email delivery is enabled

If you do not want Twitter, LWN, webhook, or email features, disable those blocks in `data/config.json` instead of creating unused secrets.

## 3. Enable GitHub Pages

Open **Settings -> Pages** and set the publishing source to the `gh-pages` branch, root directory. The workflow publishes that branch after every successful run and keeps previous generated summaries.

## 4. Run the Workflow

The workflow at `.github/workflows/daily-summary.yml` runs every day at 08:10 Asia/Shanghai and can also be started manually from **Actions -> Daily Horizon Summary -> Run workflow**.

The manual trigger accepts `hours`, which controls how far back Horizon fetches content. For example, use `48` to summarize the last two days.

## 5. Customize Your Radar

Edit `data/config.json` to choose sources, scoring threshold, languages, and delivery channels. The workflow validates required secrets before running, so missing keys fail early with a readable error message.
