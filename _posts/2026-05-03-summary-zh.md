---
layout: default
title: "Horizon Summary: 2026-05-03 (ZH)"
date: 2026-05-03
lang: zh
---

> From 52 items, 10 important content pieces were selected

---

1. [NVIDIA NeMo RL 通过推测解码实现 1.8 倍加速](#item-1) ⭐️ 9/10
2. [英国 AISI 评估 OpenAI GPT-5.5 的网络能力](#item-2) ⭐️ 9/10
3. [VideoLAN 发布 dav2d，最快的 AV2 解码器](#item-3) ⭐️ 8/10
4. [VS Code 撤回默认插入 Copilot 共同作者标签的更改](#item-4) ⭐️ 8/10
5. [特斯拉车主因 FSD 虚假宣传赢得一万美元诉讼](#item-5) ⭐️ 7/10
6. [加州将开始对违反交通法规的无人驾驶汽车开罚单](#item-6) ⭐️ 7/10
7. [小凯撒在德州推出 Flytrex Sky2 无人机披萨配送服务](#item-7) ⭐️ 7/10
8. [涉及物联网与机器人等 1071 项国家标准正式实施](#item-8) ⭐️ 7/10
9. [Ladybird 浏览器 2026 年 4 月进展更新](#item-9) ⭐️ 6/10
10. [针对 CLI 工具提出的 DO_NOT_TRACK 环境变量标准](#item-10) ⭐️ 6/10

---

<a id="item-1"></a>
## [NVIDIA NeMo RL 通过推测解码实现 1.8 倍加速](https://news.google.com/rss/articles/CBMinAJBVV95cUxOLTlaYjhPMXF2ZWRnZ3VxZU9xYXVFeTFHVllsY1hqdEwxSVV5bjZoeUtaWVVnbGRCTndzWHhaQ1pfU1VQMVZIYlB5TEN2eVZFUXVpdVFTQzZJUktUTGp6WDRDSFNsaERYZTY4V3hmM3RIazRSdFczdTlTRmRQRlFOa0NDUmUwSWt6NG53R1NHSHZGWDcxbjQ2cTZjSTRLdnBPN1hhNlUxdlQ2eFRQNWs2amJzbW5sY2Z6Smw0ZFV1LWlBcGV4d2g1LXhGaHdxWUJsZUo3WVQ2S2pjU2g2ZW5tNkE4OWZGN1NvSjFMbHBrRmVnUTdlVUNFR3dodElPLVl0ZkVMLTE2VlFaMm9MeUFPeTlnNjBHelBodHAyMtIBogJBVV95cUxPWUJZSjlEdGs5QTRvekF5VElnellLRWdreVhzbHRJM3FJb3dEbTlHbG96d01UTmxVR0haSjV0XzgtQ0FLaTFKWWpPQTZ5Z0tHVGpONk9EQnIwVDZ3MzdaMmIyMHpnbUYzdDVYaGFfYU1IVWxqb1BPWkdPUjhjaG5OMXNNSTBsTHNhM2M1MFRlc2x2cjE2LUJLY09vUS12RkhuVldDcjRBTUdwUGl1dERzMkd0QkNUMXRGTFo4NWsxaW9qbTF1d3N2TEVRZlc1aVVZengxeFowMHNtb0J2ZUNFUmpUYUFJMGJ3OFJmVnhuUi1BcUQtay1qV1RtTU56d1p3dkgzQU1MSlRZTWtlczNWdjVYdHJjQjUzeElOWnRnUVNrQQ?oc=5) ⭐️ 9/10

NVIDIA 的研究表明，在 NeMo RL 框架中应用推测解码技术，可为 8B 参数模型实现 1.8 倍的推演生成加速，并预计为 235B 参数模型带来 2.5 倍的端到端加速。 这一突破直接解决了基于人类反馈的强化学习（RLHF）过程中推演生成的严重推理延迟瓶颈，使得高级大语言模型的训练显著加快且更具成本效益。 这种加速是通过在推理期间使用推测解码来同时预测和验证多个 token 而实现的，且不会降低输出质量，这对强化学习流程中计算量庞大的推演阶段尤为关键。

rss · Google News - Reinforcement Learning · May 2, 03:47

**背景**: 推测解码是一种推理优化技术，通过同时预测和验证多个 token 来加速大语言模型，在保持输出质量的同时减少延迟。NeMo RL 是 NVIDIA 开发的开源训练后库，旨在简化和扩展大语言模型及多模态模型的强化学习方法。在大语言模型的强化学习中，推演生成是一个关键步骤，模型在此过程中生成动作序列以计算奖励，这传统上是一个主要的计算瓶颈。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/an-introduction-to-speculative-decoding-for-reducing-latency-in-ai-inference/">An Introduction to Speculative Decoding for Reducing Latency in AI Inference | NVIDIA Technical Blog</a></li>
<li><a href="https://docs.nvidia.com/nemo/rl/latest/index.html">NeMo RL Documentation — NeMo - RL</a></li>

</ul>
</details>

**标签**: `#reinforcement learning`, `#speculative decoding`, `#NVIDIA NeMo`, `#LLM optimization`, `#RLHF`

---

<a id="item-2"></a>
## [英国 AISI 评估 OpenAI GPT-5.5 的网络能力](https://simonwillison.net/2026/Apr/30/gpt-55-cyber-capabilities/#atom-everything) ⭐️ 9/10

英国人工智能安全研究所（AISI）对 OpenAI 的 GPT-5.5 发现安全漏洞的能力进行了评估，发现其网络能力与 Anthropic 的 Claude Mythos Preview 相当。与尚未向公众发布的 Claude Mythos 不同，GPT-5.5 目前已立即全面开放使用。 具有先进网络能力的前沿模型立即全面开放，显著提升了 AI 安全和漏洞研究领域的风险级别。这种广泛的访问权限可能会影响更广泛的网络安全生态系统，有可能同时加速防御性的漏洞发现和恶意行为者的攻击利用。 该评估专门聚焦于模型发现安全漏洞的熟练程度，确立了 GPT-5.5 与 Claude Mythos 之间的直接性能比较。评估强调的关键区别在于部署状态：由于 GPT-5.5 的公众可访问性，它带来了直接的现实世界影响，而 Mythos 仍处于受限状态。

rss · Simon Willison · Apr 30, 23:03

**背景**: 英国人工智能安全研究所（AISI）是一个国家支持的研究机构，致力于为政府提供对先进 AI 所带来风险的科学理解。Claude Mythos Preview 是由 Anthropic 开发的高能力 AI 模型，于 2026 年向部分公司发布，但未向公众开放。评估前沿模型的网络能力有助于政府在这些强大工具部署之前或之后不久了解其潜在的滥用风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aisi.gov.uk/">The AI Security Institute (AISI)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model ) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#ai-security`, `#openai`, `#gpt-5.5`, `#vulnerability-research`, `#llm-evaluation`

---

<a id="item-3"></a>
## [VideoLAN 发布 dav2d，最快的 AV2 解码器](https://code.videolan.org/videolan/dav2d) ⭐️ 8/10

VideoLAN 团队推出了 dav2d，这是一个针对 AV2 视频编解码器的开源、高度优化的基于 CPU 的解码器。尽管 AV2 规范仍处于草案阶段，这款早期解码器已致力于实现小巧、便携，并成为所有平台上最快的 AV2 解码器。 这一进展至关重要，因为高效的视频解码对于边缘计算和物联网网络等带宽与计算资源受限的环境来说是必不可少的。此外，dav2d 为 AV2 的实际应用铺平了道路，AV2 有望比 AV1 降低约 30%的码率，从而显著降低流媒体传输成本并提升视频质量。 该解码器在性能关键路径上大量使用了汇编语言（ASM），这是 VideoLAN 团队此前在 AV1 解码器 dav1d 上取得巨大成功的成熟策略。需要注意的是，尽管 dav2d 已经解决了解码问题，但可用的 AV2 编码器可能仍需数年时间才能成熟，这与 SVT-AV1 的历史发展时间线相似。

hackernews · dabinat · May 2, 17:32

**背景**: AV2 是由开放媒体联盟（AOMedia）正在开发的下一代开源免版税视频编码格式，作为 AV1 的继任者。它旨在提供卓越的压缩效率，并增强对 AR、VR 和分屏应用的支持，与基于专利授权的 VVC 格式直接竞争。虽然 AV2 最终规范最初计划在 2025 年底发布，但截至 2026 年仍处于草案阶段，硬件实现预计将在未来几年内推出。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.phoronix.com/news/Dav2d-Open-Source-AV2-Decode">VideoLAN Publishes Dav2d For Open-Source AV2 Decoder</a></li>
<li><a href="https://en.wikipedia.org/wiki/AV2_(video_coding_format)">AV2 (video coding format)</a></li>

</ul>
</details>

**社区讨论**: 社区对 dav2d 的发布以及 AV2 相比 AV1 可能带来的 30%码率提升感到非常兴奋，但大家也共同担忧需要漫长等待才能迎来成熟的 AV2 编码器。评论者还强调了在视频解码的性能关键路径上使用汇编语言（ASM）的持续重要性，并赞赏 VideoLAN 复制了他们在 dav1d 上采用的成功策略。

**标签**: `#AV2`, `#video-codec`, `#edge-computing`, `#multimedia-processing`, `#open-source`

---

<a id="item-4"></a>
## [VS Code 撤回默认插入 Copilot 共同作者标签的更改](https://github.com/microsoft/vscode/pull/310226) ⭐️ 8/10

一个 VS Code 的 PR 默认在 git 提交中启用了 'Co-Authored-by Copilot' 标签，无论是否实际使用了 Copilot，都会自动将 AI 添加为共同作者。在引发大规模社区强烈反对后，批准该 PR 的维护者道歉并回滚了此更改。 这一事件凸显了强行推广 AI 功能与标准开发者实践完整性之间日益紧张的关系。在 git 提交中伪造作者身份破坏了开发者对其版本控制系统和 IDE 的法律与技术信任。 具有讽刺意味的是，GitHub Copilot 本身在该 PR 中评论称，此更改导致配置架构默认值与运行时回退之间产生不一致，并建议撤回该更改。即使在禁用 AI 功能的设置开启时，该功能也会错误地添加共同作者标签。

hackernews · indrora · May 2, 19:57

**背景**: 'Co-authored-by' 尾部标记是一项标准的 git 功能，用于将提交归因于多个人，通常是在多人协作编写同一段代码时使用。VS Code 集成了 GitHub Copilot 以提供 AI 驱动的智能操作，例如生成提交信息和代码编辑建议。默认修改此标记以包含 AI 工具，将人类贡献的历史记录变成了许多人眼中的营销机制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.github.com/articles/creating-a-commit-with-multiple-authors">Creating a commit with multiple authors - GitHub Docs</a></li>
<li><a href="https://code.visualstudio.com/docs/copilot/copilot-smart-actions">AI smart actions in Visual Studio Code</a></li>

</ul>
</details>

**社区讨论**: 社区对此反应强烈并充满敌意，认为默认标签破坏了信任，将 AI 品牌推广置于法律和技术记录的完整性之上。评论者将其比作侵扰性的电子邮件签名，并批评整个科技行业为了推高 AI 使用指标而无视标准。维护者对此道歉，承认在没有充分验证的情况下默认启用该功能是错误的，同时指出 Copilot 建议撤回更改的评论被忽略了。

**标签**: `#AI ethics`, `#developer tools`, `#GitHub`, `#software engineering`, `#tech backlash`

---

<a id="item-5"></a>
## [特斯拉车主因 FSD 虚假宣传赢得一万美元诉讼](https://electrek.co/2026/05/02/this-tesla-owner-won-10k-in-court-for-teslas-fsd-lies-tesla-is-still-fighting-him/) ⭐️ 7/10

一名特斯拉车主因特斯拉全自动驾驶（FSD）的误导性宣传成功赢得了 10,672.88 美元的法院判决，该金额涵盖了他为 FSD 支付的费用、税费及法庭费用。然而，特斯拉并未支付该笔赔偿，而是继续对法院判决提出异议。 此案为追究汽车制造商未能兑现自动驾驶能力的法律责任开创了重要先例，可能为类似的消费者诉讼打开闸门。它也凸显了汽车及更广泛的自动驾驶系统行业中，针对欺骗性营销的监管和公众审查正日益严格。 核心问题在于搭载旧版 Hardware 3 (HW3)的车辆以一万美元售出 FSD 套餐，却从未实现令人信服的全自动驾驶能力，而较新的 Hardware 4 (HW4)车辆的表现则相对可接受。此外，用户报告了危险的软件行为，例如在手动驾驶时激活“紧急车道偏离”导致车辆转向障碍物。

hackernews · breve · May 2, 22:45

**背景**: 特斯拉的 Autopilot 和全自动驾驶（FSD）是高级驾驶辅助系统（ADAS），需要驾驶员主动监督，并非完全自动驾驶，尽管其营销名称暗示了这一点。加州车管局和德国法院等监管机构指控特斯拉使用“Autopilot”和“Full Self-Driving”等词汇误导消费者相信其车辆具备完全自动驾驶能力。自 2019 年以来，特斯拉的 FSD 硬件已从基于 14nm 工艺构建的 HW3 发展到较新的 HW4，导致数百万旧车在技术上无法实现承诺的自动驾驶功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tesla_Autopilot_hardware">Tesla Autopilot hardware - Wikipedia</a></li>
<li><a href="https://www.cnet.com/home/electric-vehicles/california-dmv-seeking-30-day-tesla-sale-suspension-for-unrealistic-autopilot-full-self-driving-claims/">California DMV Seeking 30-Day Tesla Sale Suspension for... - CNET</a></li>
<li><a href="https://interestingengineering.com/innovation/germany-bans-teslas-misleading-autonomous-driving-ad-statements">Germany Bans Tesla's Misleading ' Autonomous ' Driving Ad...</a></li>

</ul>
</details>

**社区讨论**: 评论者对特斯拉的误导性营销和硬件限制表示强烈不满，特别是为未兑现的功能买单的 HW3 车主，一些人甚至将这种欺骗的规模和危险性与 Theranos 欺诈案相提并论。用户还分享了个人维权经历，例如因紧急车道偏离等危险软件故障依据加州柠檬法成功退款，并对特斯拉是否会真正支付法院判决的赔偿金表示怀疑。

**标签**: `#autonomous-vehicles`, `#regulation`, `#liability`, `#real-world-deployment`, `#safety`

---

<a id="item-6"></a>
## [加州将开始对违反交通法规的无人驾驶汽车开罚单](https://www.bbc.com/news/articles/clypjx3rg2go) ⭐️ 7/10

加州宣布将开始对违反交通法规的无人驾驶汽车开罚单，结束了自动驾驶汽车在运营期间无需承担与人类驾驶汽车相同罚单后果的局面。 这项政策转变至关重要，因为它为自动驾驶汽车运营商建立了一个具体的问责机制，防止他们利用没有人类驾驶员作为借口来逃避交通违规和造成社会危害的责任。 罚单可能会开给运营公司而不是人类驾驶员，这将迫使自动驾驶制造商将交通罚单视为改进其边缘计算模型和驾驶算法的运营信号。

hackernews · geox · May 2, 17:59

**背景**: 自动驾驶汽车依赖复杂的 AI 和边缘计算系统做出实时驾驶决策，通过绕过云连接来避免延迟。现有的责任法律一直难以适应自动驾驶汽车，因为传统框架依赖于人类过失的概念，这引发了关于 AI 应被视为产品还是驾驶员的难题。监管机构现在正积极完善这些框架，以便在自动驾驶汽车造成损害或伤害时确定责任方——无论是系统运营商、制造商还是保险公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nstlaw.com/faqs/autonomous-car-accidents-liability-laws-by-state/">Autonomous Car Crashes & Liability Laws by State | NST Law</a></li>
<li><a href="https://en.wikipedia.org/wiki/Regulation_of_self-driving_cars">Regulation of self-driving cars - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区对无人驾驶汽车此前未受到交通罚单约束表示惊讶，许多人同意问责制对于防止制造商将危害外部化至关重要。用户对最佳执法机制进行了辩论，一些人认为罚单可以提供有价值的数据信号来改进 AI 模型，而另一些人则主张采用直接的运营阈值或罚款而非传统罚单。提出的一个重大关切是如何对自动驾驶公司进行适当规模的处罚，质疑标准罚款是否会仅仅成为可接受的商业成本，或者是否需要追究高管的责任。

**标签**: `#autonomous vehicles`, `#regulation`, `#liability`, `#edge computing`, `#deployment`

---

<a id="item-7"></a>
## [小凯撒在德州推出 Flytrex Sky2 无人机披萨配送服务](https://news.google.com/rss/articles/CBMiqwFBVV95cUxOVEIwXzg0SHZDMUJSbWJmdnJ6OGpqbUhKZklFeGxMZHdGUUJsUll2WHRBMU5KR014SHE3VzE4bnJyU09KNG5MVHhjT3hITnBqM0FuSUQzZmlibUZDQmYxUVJsai1NbVVYb0xGaURsSVBYMVBXWW1SRjFodS1fMExjdk9YV1k2eGZiUXdhX2RVRnZmcEVKeElaZ3hQSUJWQ0tCcWVSVlcxRlNyZEk?oc=5) ⭐️ 7/10

小凯撒在德克萨斯州怀利市推出了一项新的无人机披萨配送服务，该服务由 Flytrex 的新型 Sky2 无人机提供支持。这项于 4 月 23 日宣布的有限测试标志着美国首次通过无人机配送全套家庭餐，能够在不到五分钟的时间内完成四英里范围内的订单配送。 此次部署代表了无人机配送系统商业化的重要一步，证明了无人机物流能够处理完整且较重的餐食订单，而不仅仅是小件物品。它通过展示一种可扩展的快速配送模式，直接影响了零售和食品配送行业，该模式可能会重塑城市物流和消费者期望。 Flytrex 的 Sky2 无人机最高可承载 8.8 磅的物品，足以装载两个大披萨、Crazy Bread 和饮料。该配送系统在四英里半径内运行，并在不到五分钟的时间内完成飞行，突显了商用无人机技术在速度和载重能力方面的显著提升。

rss · Google News - UAV and IoT Applications · May 1, 02:23

**背景**: 无人机（UAV）配送系统正越来越多地被探索用于绕过地面交通并提高城市物流中的供应链效率。将无人机整合到更广泛的配送生态系统中需要专门的机器人系统，以确保它们作为互联节点而非孤立单元运行。像 Flytrex 这样的公司正在开发包含起点、中转点和最终配送地点的专用链条，以使商用无人机投放变得可行且安全。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dallasexpress.com/metroplex/pizza-by-drone-little-caesars-tests-sky2-delivery-in-wylie-texas/">Pizza By Drone: Little Caesars Tests Sky2 Delivery In Wylie, Texas</a></li>
<li><a href="https://www.usatoday.com/story/money/food/2026/04/27/little-caesars-drone-pizza-delivery/89812907007/">'Pizza! Pizza!' Little Caesars debuts drone delivering family‑size meals</a></li>

</ul>
</details>

**标签**: `#UAVs`, `#drones`, `#commercial deployment`, `#IoT applications`, `#delivery systems`

---

<a id="item-8"></a>
## [涉及物联网与机器人等 1071 项国家标准正式实施](https://news.google.com/rss/articles/CBMib0FVX3lxTFBycENYRnFuN3JRdFRiNmZiYkhRMXA5REpRSmhoVFM4b1FPdnpPRFc1WnlnTXg1ZlRwOTZxVkUwVjVtTDNIODZiN1NGLXlNV0d2Q1dKVGszdS1qTGR1Sl9XckhwZjRjVFVTQjFNSU92NA?oc=5) ⭐️ 7/10

5 月 1 日起，中国共有 1071 项国家标准正式实施，这些标准具体涵盖了教育机器人和物联网等新兴领域。 这些标准的实施提供了关键的监管清晰度，将显著影响物联网和机器人技术在中国现实世界中的部署与产品化。这也表明了政府对新兴产业标准化的强力支持，将深刻影响行业趋势和市场准入要求。 新实施的标准涵盖了广泛的技术规范，其中教育机器人和物联网框架是值得关注的重点。这些法规将作为中国市场上产品合规性、安全性和互操作性的强制性基准。

rss · Google News CN - 边缘计算物联网应用 · Apr 30, 10:08

**背景**: 中国一直在积极推动高效标准化体系的建设，以支撑科技创新和新兴产业发展。随着国内人工智能和机器人产业出现爆发式增长，政府正在大力投资先进技术，并建立标准化框架以确保市场的有序发展和国际竞争力。

<details><summary>参考链接</summary>
<ul>
<li><a href="http://paper.people.com.cn/rmrb/images/2024-01/03/02/rmrb2024010302.pdf">YW2BRMRB02B20240103C</a></li>
<li><a href="https://www.bbc.com/zhongwen/articles/c99n7x5jrygo/simp">人 工智能：从聊天 机 器 人 到玩具，AI... - BBC News 中文</a></li>

</ul>
</details>

**标签**: `#IoT`, `#regulation`, `#standards`, `#robotics`, `#industry-trends`

---

<a id="item-9"></a>
## [Ladybird 浏览器 2026 年 4 月进展更新](https://ladybird.org/newsletter/2026-04-30/) ⭐️ 6/10

Ladybird 浏览器项目发布了 2026 年 4 月的月度进展更新，详细介绍了在迈向计划中的 2026 年 Alpha 版本发布过程中的持续开发里程碑和错误修复。 作为一个罕见的从零开始构建的独立浏览器引擎，Ladybird 的进展挑战了由 Chromium 主导的生态系统，并为寻求真正独立网络体验的用户提供了未来的潜在替代方案。 此次更新突出了具体的兼容性修复，例如通过修正 Navigator.getBattery 抛出的错误类型以符合规范来解决 Strava.com 的登录问题，以及成功渲染 CSS Doom 等复杂的 CSS 效果。

hackernews · richardboegli · May 2, 20:46

**背景**: Ladybird 是一个开源的、注重隐私的网络浏览器，由非营利组织 Ladybird Browser Initiative 从零开始开发，最初是 SerenityOS 的一个组件。浏览器渲染引擎是核心软件组件，负责将 HTML、CSS 和 JavaScript 转换为用户设备上的交互式视觉呈现。当前浏览器市场严重被基于 Chromium 的引擎所主导，这使得新的独立引擎面临巨大的网络兼容性挑战以及获取 DRM Widevine 认证等障碍。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ladybird_browser">Ladybird browser</a></li>
<li><a href="https://en.wikipedia.org/wiki/Browser_engine">Browser engine - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区对 Ladybird 的进展充满热情，用户将更新日志比作游戏模拟器的进度报告，并表达了采用早期 Alpha 版本的渴望。然而，大家也对“人为的”网络兼容性问题提出了严重关切，即网站强制屏蔽非 Chromium 浏览器，以及新浏览器几乎不可能获得 DRM Widevine 认证，这严重限制了其主流普及。

**标签**: `#web browser`, `#open source`, `#Ladybird`, `#web compatibility`, `#rendering engine`

---

<a id="item-10"></a>
## [针对 CLI 工具提出的 DO_NOT_TRACK 环境变量标准](https://donottrack.sh/) ⭐️ 6/10

一项新提出的标准引入了 DO_NOT_TRACK 环境变量，允许用户在 CLI 和 TUI 应用程序中选择退出遥测、分析和跟踪。该标准鼓励开发者检查这一单一变量，以尊重用户禁用非必要网络请求的意愿。 该标准旨在统一目前各工具互不相同的退出变量碎片化现状，为开发者提供一个清晰、通用的信号以尊重用户隐私。然而，它依赖于退出机制而非明确的加入机制，这引发了人们对其在整个生态系统中保护隐私实际效果的担忧。 该标准建议，如果设置了 DO_NOT_TRACK 变量，应用程序应禁用遥测、分析和非必要的网络请求。目前，许多流行的工具（如.NET CLI 和 GitHub CLI）都使用各自特定的环境变量，这使得统一方法成为必要但难以强制执行。

hackernews · RubyGuy · May 2, 17:40

**背景**: 现代开发工具和库默认频繁收集遥测数据以帮助改进产品，这要求用户寻找并设置特定的环境变量才能选择退出。该概念与浏览器端失败的不跟踪（DNT）标准如出一辙，后者因缺乏法律强制力而被广告商无视。作为应用程序级设置的替代方案，许多用户采用网络级解决方案（如 hagezi/dns-blocklists 或 Pi-hole）来完全阻止已知的遥测域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://donottrack.sh/">DO_NOT_TRACK</a></li>
<li><a href="https://github.com/hagezi/dns-blocklists">GitHub - hagezi/dns-blocklists: DNS-Blocklists: For a better ...</a></li>
<li><a href="https://learn.microsoft.com/en-us/dotnet/core/tools/telemetry">NET SDK and .NET CLI telemetry - .NET CLI | Microsoft Learn</a></li>

</ul>
</details>

**社区讨论**: 社区对此高度怀疑，用户指出默认加入的模式令人毛骨悚然，且该标准可能只是作为一个蜜罐，用来识别那些未经明确同意就收集遥测数据的工具。其他人分享了实际的挫折感，指出在 Hugging Face 的 transformers 等库中真正停止遥测极其困难，并建议网络级的 DNS 阻止比依赖环境变量是更可靠的解决方案。

**标签**: `#telemetry`, `#privacy`, `#developer-tools`, `#open-source`, `#dns-blocking`

---