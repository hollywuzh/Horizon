---
layout: default
title: "Horizon Summary: 2026-05-03 (EN)"
date: 2026-05-03
lang: en
---

> From 52 items, 10 important content pieces were selected

---

1. [NVIDIA NeMo RL Achieves 1.8x Speedup with Speculative Decoding](#item-1) ⭐️ 9/10
2. [UK AISI Evaluates OpenAI's GPT-5.5 Cyber Capabilities](#item-2) ⭐️ 9/10
3. [VideoLAN Releases dav2d, the Fastest AV2 Decoder](#item-3) ⭐️ 8/10
4. [VS Code Rolls Back Default Copilot Co-Author Tag](#item-4) ⭐️ 8/10
5. [Tesla owner wins $10k court case over FSD lies](#item-5) ⭐️ 7/10
6. [California to Ticket Driverless Cars for Traffic Violations](#item-6) ⭐️ 7/10
7. [Little Caesars Launches Flytrex Sky2 Drone Pizza Delivery in Texas](#item-7) ⭐️ 7/10
8. [1071 National Standards for IoT and Robots Take Effect](#item-8) ⭐️ 7/10
9. [Ladybird Browser April 2026 Progress Update](#item-9) ⭐️ 6/10
10. [Proposed DO_NOT_TRACK Environment Variable Standard for CLI Tools](#item-10) ⭐️ 6/10

---

<a id="item-1"></a>
## [NVIDIA NeMo RL Achieves 1.8x Speedup with Speculative Decoding](https://news.google.com/rss/articles/CBMinAJBVV95cUxOLTlaYjhPMXF2ZWRnZ3VxZU9xYXVFeTFHVllsY1hqdEwxSVV5bjZoeUtaWVVnbGRCTndzWHhaQ1pfU1VQMVZIYlB5TEN2eVZFUXVpdVFTQzZJUktUTGp6WDRDSFNsaERYZTY4V3hmM3RIazRSdFczdTlTRmRQRlFOa0NDUmUwSWt6NG53R1NHSHZGWDcxbjQ2cTZjSTRLdnBPN1hhNlUxdlQ2eFRQNWs2amJzbW5sY2Z6Smw0ZFV1LWlBcGV4d2g1LXhGaHdxWUJsZUo3WVQ2S2pjU2g2ZW5tNkE4OWZGN1NvSjFMbHBrRmVnUTdlVUNFR3dodElPLVl0ZkVMLTE2VlFaMm9MeUFPeTlnNjBHelBodHAyMtIBogJBVV95cUxPWUJZSjlEdGs5QTRvekF5VElnellLRWdreVhzbHRJM3FJb3dEbTlHbG96d01UTmxVR0haSjV0XzgtQ0FLaTFKWWpPQTZ5Z0tHVGpONk9EQnIwVDZ3MzdaMmIyMHpnbUYzdDVYaGFfYU1IVWxqb1BPWkdPUjhjaG5OMXNNSTBsTHNhM2M1MFRlc2x2cjE2LUJLY09vUS12RkhuVldDcjRBTUdwUGl1dERzMkd0QkNUMXRGTFo4NWsxaW9qbTF1d3N2TEVRZlc1aVVZengxeFowMHNtb0J2ZUNFUmpUYUFJMGJ3OFJmVnhuUi1BcUQtay1qV1RtTU56d1p3dkgzQU1MSlRZTWtlczNWdjVYdHJjQjUzeElOWnRnUVNrQQ?oc=5) ⭐️ 9/10

NVIDIA research demonstrates that applying speculative decoding within the NeMo RL framework achieves a 1.8× rollout generation speedup for 8B parameter models and projects a 2.5× end-to-end speedup for massive 235B parameter models. This breakthrough directly addresses the severe inference latency bottleneck during rollout generation in reinforcement learning from human feedback (RLHF), making the training of advanced large language models significantly faster and more cost-effective. The speedup is achieved by using speculative decoding to predict and verify multiple tokens simultaneously during inference without degrading output quality, which is particularly impactful for the computationally heavy rollout phases in RL pipelines.

rss · Google News - Reinforcement Learning · May 2, 03:47

**Background**: Speculative decoding is an inference optimization technique that accelerates large language models by predicting and verifying multiple tokens simultaneously, reducing latency while preserving output quality. NeMo RL is an open-source post-training library developed by NVIDIA, designed to streamline and scale reinforcement learning methods for large language and multimodal models. In reinforcement learning for LLMs, rollout generation is a critical step where the model generates sequences of actions to compute rewards, which is traditionally a major computational bottleneck.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/an-introduction-to-speculative-decoding-for-reducing-latency-in-ai-inference/">An Introduction to Speculative Decoding for Reducing Latency in AI Inference | NVIDIA Technical Blog</a></li>
<li><a href="https://docs.nvidia.com/nemo/rl/latest/index.html">NeMo RL Documentation — NeMo - RL</a></li>

</ul>
</details>

**Tags**: `#reinforcement learning`, `#speculative decoding`, `#NVIDIA NeMo`, `#LLM optimization`, `#RLHF`

---

<a id="item-2"></a>
## [UK AISI Evaluates OpenAI's GPT-5.5 Cyber Capabilities](https://simonwillison.net/2026/Apr/30/gpt-55-cyber-capabilities/#atom-everything) ⭐️ 9/10

The UK AI Security Institute (AISI) has evaluated OpenAI's GPT-5.5 for its ability to find security vulnerabilities, finding its cyber capabilities comparable to Anthropic's Claude Mythos Preview. Unlike Claude Mythos, which remains unreleased to the public, GPT-5.5 is immediately and generally available. The immediate general availability of a frontier model with advanced cyber capabilities significantly raises the stakes for AI security and vulnerability research. This widespread access could impact the broader cybersecurity ecosystem, potentially accelerating both defensive vulnerability discovery and offensive exploitation by malicious actors. The evaluation specifically focused on the models' proficiency in finding security vulnerabilities, establishing a direct performance comparison between GPT-5.5 and Claude Mythos. The critical distinction highlighted by the evaluation is the deployment status: GPT-5.5 poses immediate real-world implications due to its public accessibility, whereas Mythos remains restricted.

rss · Simon Willison · Apr 30, 23:03

**Background**: The UK AI Security Institute (AISI) is a state-backed research organization dedicated to equipping governments with a scientific understanding of the risks posed by advanced AI. Claude Mythos Preview is a highly capable AI model developed by Anthropic that was released to select companies in 2026 but not to the general public. Evaluating frontier models for cyber capabilities helps governments understand potential misuse before or shortly after these powerful tools are deployed.

<details><summary>References</summary>
<ul>
<li><a href="https://www.aisi.gov.uk/">The AI Security Institute (AISI)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model ) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#ai-security`, `#openai`, `#gpt-5.5`, `#vulnerability-research`, `#llm-evaluation`

---

<a id="item-3"></a>
## [VideoLAN Releases dav2d, the Fastest AV2 Decoder](https://code.videolan.org/videolan/dav2d) ⭐️ 8/10

The VideoLAN team has introduced dav2d, an open-source, highly optimized CPU-based decoder for the AV2 video codec. Although the AV2 specification is still in draft status, this early decoder is already targeted to be small, portable, and the fastest AV2 decoder across all platforms. This development is crucial because efficient video decoding is essential for constrained environments like edge computing and IoT networks where bandwidth and compute resources are limited. Furthermore, dav2d paves the way for the practical adoption of AV2, which promises approximately 30% lower bitrates than AV1, significantly reducing streaming costs and improving video quality. The decoder heavily utilizes Assembly (ASM) language for performance-critical paths, a proven strategy the VideoLAN team previously used to great success with their AV1 decoder, dav1d. It is important to note that while dav2d handles decoding, a usable AV2 encoder is still likely years away, mirroring the historical timeline for SVT-AV1's maturity.

hackernews · dabinat · May 2, 17:32

**Background**: AV2 is the next-generation, open, royalty-free video coding format currently being developed by the Alliance for Open Media (AOMedia) as the successor to AV1. It aims to deliver superior compression efficiency and enhanced support for AR, VR, and split-screen usage, competing directly with the royalty-based VVC format. While the final AV2 specification was initially targeted for late 2025, it remains in draft status as of 2026, with hardware implementations expected to follow in the coming years.

<details><summary>References</summary>
<ul>
<li><a href="https://www.phoronix.com/news/Dav2d-Open-Source-AV2-Decode">VideoLAN Publishes Dav2d For Open-Source AV2 Decoder</a></li>
<li><a href="https://en.wikipedia.org/wiki/AV2_(video_coding_format)">AV2 (video coding format)</a></li>

</ul>
</details>

**Discussion**: The community is highly enthusiastic about dav2d's release and the potential 30% bitrate improvement of AV2 over AV1, though there is shared concern about the long wait for a mature AV2 encoder. Commenters also highlighted the continued relevance of using Assembly (ASM) for performance-critical paths in video decoding, praising VideoLAN for replicating the successful strategy they employed with dav1d.

**Tags**: `#AV2`, `#video-codec`, `#edge-computing`, `#multimedia-processing`, `#open-source`

---

<a id="item-4"></a>
## [VS Code Rolls Back Default Copilot Co-Author Tag](https://github.com/microsoft/vscode/pull/310226) ⭐️ 8/10

A VS Code PR enabled a 'Co-Authored-by Copilot' tag in git commits by default, which automatically added the AI as a co-author regardless of whether Copilot was actually used. Following massive community backlash, the maintainer who approved the PR apologized and rolled back the change. This incident highlights the growing tension between aggressive AI feature adoption and the integrity of standard developer practices. Falsifying authorship in git commits undermines the legal and technical trust developers place in their version control systems and IDEs. Ironically, GitHub Copilot itself commented on the PR, warning that the change created an inconsistency between the configuration schema default and the runtime fallback, and suggested reverting it. The feature also incorrectly added the co-author tag even when the disableAIFeatures setting was turned on.

hackernews · indrora · May 2, 19:57

**Background**: The 'Co-authored-by' trailer is a standard git feature used to attribute commits to multiple people, typically when multiple humans collaborate on a piece of code. VS Code integrates GitHub Copilot to provide AI-powered smart actions, such as generating commit messages and suggesting code edits. Modifying this trailer by default to include an AI tool transforms a historical record of human contribution into what many perceive as a marketing mechanism.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.github.com/articles/creating-a-commit-with-multiple-authors">Creating a commit with multiple authors - GitHub Docs</a></li>
<li><a href="https://code.visualstudio.com/docs/copilot/copilot-smart-actions">AI smart actions in Visual Studio Code</a></li>

</ul>
</details>

**Discussion**: The community reacted with strong hostility, viewing the default tag as a breach of trust that prioritizes AI branding over the integrity of legal and technical records. Commenters drew parallels to invasive email signatures and criticized the broader tech industry's willingness to ignore standards to push AI usage metrics. The maintainer apologized, acknowledging the mistake of enabling it by default without sufficient validation, while noting Copilot's own ignored recommendation to revert the change.

**Tags**: `#AI ethics`, `#developer tools`, `#GitHub`, `#software engineering`, `#tech backlash`

---

<a id="item-5"></a>
## [Tesla owner wins $10k court case over FSD lies](https://electrek.co/2026/05/02/this-tesla-owner-won-10k-in-court-for-teslas-fsd-lies-tesla-is-still-fighting-him/) ⭐️ 7/10

A Tesla owner successfully won a court judgment of $10,672.88 against Tesla for misleading Full Self-Driving (FSD) claims, which covers the amount he paid for the FSD package including taxes and court fees. However, Tesla is continuing to fight the court decision rather than paying the awarded amount. This case establishes a significant legal precedent for holding automakers accountable for unfulfilled autonomous driving capabilities, potentially opening the floodgates for similar consumer lawsuits. It also highlights growing regulatory and public scrutiny over deceptive marketing in the automotive and broader autonomous systems industry. The core issue revolves around older Hardware 3 (HW3) vehicles that were sold with a $10,000 FSD package but never achieved convincing full self-driving capability, whereas newer Hardware 4 (HW4) vehicles have a more acceptable performance. Additionally, users have reported dangerous software behaviors, such as "emergency lane departure" activating during manual driving and swerving towards obstacles.

hackernews · breve · May 2, 22:45

**Background**: Tesla's Autopilot and Full Self-Driving (FSD) are advanced driver-assistance systems (ADAS) that require active driver supervision and are not fully autonomous, despite their marketing names. Regulatory bodies like the California DMV and courts in Germany have accused Tesla of misleading consumers by using terms like "Autopilot" and "Full Self-Driving" that imply full autonomy. Since 2019, Tesla's FSD hardware has evolved from HW3, built on a 14nm process, to the newer HW4, leaving millions of older vehicles technically incapable of fulfilling the promised self-driving features.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tesla_Autopilot_hardware">Tesla Autopilot hardware - Wikipedia</a></li>
<li><a href="https://www.cnet.com/home/electric-vehicles/california-dmv-seeking-30-day-tesla-sale-suspension-for-unrealistic-autopilot-full-self-driving-claims/">California DMV Seeking 30-Day Tesla Sale Suspension for... - CNET</a></li>
<li><a href="https://interestingengineering.com/innovation/germany-bans-teslas-misleading-autonomous-driving-ad-statements">Germany Bans Tesla's Misleading ' Autonomous ' Driving Ad...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed strong frustration over Tesla's misleading marketing and hardware limitations, particularly for HW3 owners who paid for unfulfilled capabilities, while some drew parallels to the Theranos fraud case regarding the scale and danger of the deception. Users also shared personal grievances, such as recovering funds under the California lemon law for dangerous software glitches like emergency lane departure, and skepticism about Tesla actually paying out the court-awarded judgments.

**Tags**: `#autonomous-vehicles`, `#regulation`, `#liability`, `#real-world-deployment`, `#safety`

---

<a id="item-6"></a>
## [California to Ticket Driverless Cars for Traffic Violations](https://www.bbc.com/news/articles/clypjx3rg2go) ⭐️ 7/10

California has announced it will begin issuing traffic tickets to driverless cars that violate traffic laws, ending a period where autonomous vehicles operated without the same ticketing consequences as human-driven cars. This policy shift is crucial because it establishes a concrete accountability mechanism for autonomous vehicle operators, preventing them from using the absence of a human driver to escape responsibility for traffic infractions and societal harm. The tickets will likely be issued to the operating companies rather than a human driver, forcing AV manufacturers to treat traffic citations as operational signals to improve their edge computing models and driving algorithms.

hackernews · geox · May 2, 17:59

**Background**: Autonomous vehicles rely on complex AI and edge computing systems to make real-time driving decisions, bypassing the need for cloud connectivity to avoid latency. Existing liability laws have been struggling to adapt to AVs, as traditional frameworks depend on the concept of human negligence, raising difficult questions about whether AI should be treated as a product or a driver. Regulators are now actively evolving these frameworks to identify the responsible parties—whether system operators, manufacturers, or insurers—when AVs cause damage or injury.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nstlaw.com/faqs/autonomous-car-accidents-liability-laws-by-state/">Autonomous Car Crashes & Liability Laws by State | NST Law</a></li>
<li><a href="https://en.wikipedia.org/wiki/Regulation_of_self-driving_cars">Regulation of self-driving cars - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community expressed surprise that driverless cars were not already subject to traffic tickets, with many agreeing that accountability is essential to prevent manufacturers from externalizing harm. Users debated the best enforcement mechanism, with some suggesting that tickets provide valuable data signals to improve AI models, while others argued for direct operational thresholds or fines rather than traditional ticketing. A significant concern raised was how to scale penalties appropriately for AV companies, questioning whether standard fines would merely become an acceptable cost of doing business or if executive accountability is needed.

**Tags**: `#autonomous vehicles`, `#regulation`, `#liability`, `#edge computing`, `#deployment`

---

<a id="item-7"></a>
## [Little Caesars Launches Flytrex Sky2 Drone Pizza Delivery in Texas](https://news.google.com/rss/articles/CBMiqwFBVV95cUxOVEIwXzg0SHZDMUJSbWJmdnJ6OGpqbUhKZklFeGxMZHdGUUJsUll2WHRBMU5KR014SHE3VzE4bnJyU09KNG5MVHhjT3hITnBqM0FuSUQzZmlibUZDQmYxUVJsai1NbVVYb0xGaURsSVBYMVBXWW1SRjFodS1fMExjdk9YV1k2eGZiUXdhX2RVRnZmcEVKeElaZ3hQSUJWQ0tCcWVSVlcxRlNyZEk?oc=5) ⭐️ 7/10

Little Caesars has launched a new drone pizza delivery service in Wylie, Texas, powered by Flytrex's new Sky2 drone. Announced on April 23, this limited test marks the nation's first drone delivery of full family meals, capable of delivering orders within a four-mile radius in under five minutes. This deployment represents a significant step in the commercialization of UAV delivery systems, demonstrating that drone logistics can handle complete, heavy meal orders rather than just small items. It directly impacts the retail and food delivery sectors by showcasing a scalable, rapid delivery model that could reshape urban logistics and consumer expectations. The Flytrex Sky2 drone can carry payloads of up to 8.8 pounds, which is sufficient for two large pizzas, Crazy Bread, and drinks. The delivery system operates within a four-mile radius and completes flights in less than five minutes, highlighting significant speed and capacity improvements in commercial UAV technology.

rss · Google News - UAV and IoT Applications · May 1, 02:23

**Background**: Unmanned Aerial Vehicle (UAV) delivery systems are increasingly being explored to bypass ground traffic and improve supply chain efficiency in urban logistics. Integrating drones into the broader delivery ecosystem requires specialized robotic systems to ensure they operate as connected nodes rather than isolated units. Companies like Flytrex are developing dedicated chains that include starting locations, intermediate transfer points, and final delivery locations to make commercial drone drops feasible and safe.

<details><summary>References</summary>
<ul>
<li><a href="https://dallasexpress.com/metroplex/pizza-by-drone-little-caesars-tests-sky2-delivery-in-wylie-texas/">Pizza By Drone: Little Caesars Tests Sky2 Delivery In Wylie, Texas</a></li>
<li><a href="https://www.usatoday.com/story/money/food/2026/04/27/little-caesars-drone-pizza-delivery/89812907007/">'Pizza! Pizza!' Little Caesars debuts drone delivering family‑size meals</a></li>

</ul>
</details>

**Tags**: `#UAVs`, `#drones`, `#commercial deployment`, `#IoT applications`, `#delivery systems`

---

<a id="item-8"></a>
## [1071 National Standards for IoT and Robots Take Effect](https://news.google.com/rss/articles/CBMib0FVX3lxTFBycENYRnFuN3JRdFRiNmZiYkhRMXA5REpRSmhoVFM4b1FPdnpPRFc1WnlnTXg1ZlRwOTZxVkUwVjVtTDNIODZiN1NGLXlNV0d2Q1dKVGszdS1qTGR1Sl9XckhwZjRjVFVTQjFNSU92NA?oc=5) ⭐️ 7/10

On May 1st, a total of 1071 national standards officially went into effect in China, specifically covering emerging sectors such as educational robots and the Internet of Things (IoT). The implementation of these standards provides crucial regulatory clarity that will significantly impact the real-world deployment and productization of IoT and robotics technologies in China. It also signals strong government support for standardizing emerging industries, which will shape industry trends and market entry requirements. The newly implemented standards encompass a broad range of technical specifications, with notable inclusions being educational robots and IoT frameworks. These regulations will serve as mandatory baselines for product compliance, safety, and interoperability within the Chinese market.

rss · Google News CN - 边缘计算物联网应用 · Apr 30, 10:08

**Background**: China has been actively promoting the development of an efficient standardization system to support technological innovation and emerging industries. As the AI and robotics industry experiences explosive growth in the country, the government is heavily investing in advanced technologies and establishing standardized frameworks to ensure orderly market development and international competitiveness.

<details><summary>References</summary>
<ul>
<li><a href="http://paper.people.com.cn/rmrb/images/2024-01/03/02/rmrb2024010302.pdf">YW2BRMRB02B20240103C</a></li>
<li><a href="https://www.bbc.com/zhongwen/articles/c99n7x5jrygo/simp">人 工智能：从聊天 机 器 人 到玩具，AI... - BBC News 中文</a></li>

</ul>
</details>

**Tags**: `#IoT`, `#regulation`, `#standards`, `#robotics`, `#industry-trends`

---

<a id="item-9"></a>
## [Ladybird Browser April 2026 Progress Update](https://ladybird.org/newsletter/2026-04-30/) ⭐️ 6/10

The Ladybird browser project released its April 2026 monthly progress update, detailing ongoing development milestones and bug fixes as it approaches its planned 2026 alpha release. As a rare from-scratch, independent browser engine, Ladybird's progress challenges the Chromium-dominated ecosystem and offers a potential future alternative for users seeking a truly independent web experience. The update highlights specific compatibility fixes, such as resolving a Strava.com login issue by correcting the error type thrown by Navigator.getBattery to match the specification, and successfully rendering complex CSS like CSS Doom.

hackernews · richardboegli · May 2, 20:46

**Background**: Ladybird is an open-source, privacy-focused web browser developed from scratch by the non-profit Ladybird Browser Initiative, originally as a component of SerenityOS. A browser rendering engine is the core software component that transforms HTML, CSS, and JavaScript into the interactive visual representation on a user's device. The browser market is currently heavily dominated by Chromium-based engines, making new independent engines face significant web compatibility challenges and hurdles like acquiring DRM Widevine certification.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ladybird_browser">Ladybird browser</a></li>
<li><a href="https://en.wikipedia.org/wiki/Browser_engine">Browser engine - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community is enthusiastic about Ladybird's progress, with users comparing the update notes to gaming emulator progress reports and expressing eagerness to adopt early alpha builds. However, significant concerns were raised regarding "artificial" web compatibility, where websites forcibly block non-Chromium browsers, and the near-impossibility for new browsers to acquire DRM Widevine certification, which severely limits mainstream adoption.

**Tags**: `#web browser`, `#open source`, `#Ladybird`, `#web compatibility`, `#rendering engine`

---

<a id="item-10"></a>
## [Proposed DO_NOT_TRACK Environment Variable Standard for CLI Tools](https://donottrack.sh/) ⭐️ 6/10

A new proposed standard introduces the DO_NOT_TRACK environment variable, allowing users to opt out of telemetry, analytics, and tracking in CLI and TUI applications. Developers are encouraged to check for this single variable to respect a user's wish to disable non-essential network requests. This standard aims to unify the fragmented landscape of tool-specific opt-out variables, giving developers a clear, universal signal to respect user privacy. However, its reliance on an opt-out mechanism rather than explicit opt-in raises concerns about its actual effectiveness in protecting privacy across the ecosystem. The standard suggests that if the DO_NOT_TRACK variable is set, applications should disable telemetry, analytics, and non-essential network requests. Currently, many popular tools like .NET CLI and GitHub CLI use their own specific environment variables, which makes a unified approach necessary but difficult to enforce.

hackernews · RubyGuy · May 2, 17:40

**Background**: Modern development tools and libraries frequently collect telemetry by default to help improve products, requiring users to find and set specific environment variables to opt out. The concept mirrors the failed browser-based Do Not Track (DNT) standard, which was ignored by advertisers because it lacked legal enforcement. As an alternative to application-level settings, many users employ network-level solutions like DNS blocklists (e.g., hagezi/dns-blocklists or Pi-hole) to block known telemetry domains entirely.

<details><summary>References</summary>
<ul>
<li><a href="https://donottrack.sh/">DO_NOT_TRACK</a></li>
<li><a href="https://github.com/hagezi/dns-blocklists">GitHub - hagezi/dns-blocklists: DNS-Blocklists: For a better ...</a></li>
<li><a href="https://learn.microsoft.com/en-us/dotnet/core/tools/telemetry">NET SDK and .NET CLI telemetry - .NET CLI | Microsoft Learn</a></li>

</ul>
</details>

**Discussion**: The community is highly skeptical, with users pointing out that the default opt-in model is creepy and that this standard might just act as a honeypot to identify tools that collect telemetry without explicit consent. Others shared practical frustrations, noting how difficult it is to truly stop telemetry in libraries like Hugging Face's transformers, and suggested that network-level DNS blocking is a more reliable solution than relying on environment variables.

**Tags**: `#telemetry`, `#privacy`, `#developer-tools`, `#open-source`, `#dns-blocking`

---