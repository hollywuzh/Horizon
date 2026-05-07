---
layout: default
title: "Horizon Summary: 2026-05-07 (ZH)"
date: 2026-05-07
lang: zh
---

> From 119 items, 10 important content pieces were selected

---

1. [KAIST 开发用于组合优化的 CMOS 伊辛机](#item-1) ⭐️ 9/10
2. [使用 MRC 和 SRv6 的弹性 AI 超算网络](#item-2) ⭐️ 9/10
3. [LCM：无损上下文管理性能超越 Claude Code](#item-3) ⭐️ 9/10
4. [中性原子量子架构上拉马努金超图的最优对数路由](#item-4) ⭐️ 9/10
5. [Vibe Coding 与 Agentic Engineering 正在趋同](#item-5) ⭐️ 8/10
6. [Anthropic 提升 Claude 使用限额并与 SpaceX 签署大规模算力协议](#item-6) ⭐️ 8/10
7. [中国批准首个卫星物联网业务商用试验](#item-7) ⭐️ 8/10
8. [VLM 将自然语言转化为逻辑以实现安全导航](#item-8) ⭐️ 8/10
9. [标量不可约动力学实现内生体制切换](#item-9) ⭐️ 8/10
10. [BOOOM：Stiefel 流形上的无导数优化](#item-10) ⭐️ 8/10

---

<a id="item-1"></a>
## [KAIST 开发用于组合优化的 CMOS 伊辛机](https://news.google.com/rss/articles/CBMigAFBVV95cUxNZHdvMTRXRlpCZUE0YnpJUHJhN2Jwb1lrV0xSZmNZZjA5b1RkSFgtbDYzNmxCLXVHV0VRRFF3VFcwTFNZRmVNaDdCOXhObXJhNmRXNzh0VXppcFJDeE5NY0ttcy1hM05fVlhuUUxUYTg2N0Q1QWhCUHFFQ3lpb1BTU9IBlAFBVV95cUxOLWJXZkZMTWk5bkV5aFJ5cTBWVzZjLWpIOXJiYnVTMnF5VkNfVkc1NzR2VTB6b21ZMVRrUEt2LTdtaXFORDZtYXZZaXR5R1ZvSHlyWmZnRTVNWjJKZG44UUFKdTJFOXRVSWlCdWlJTnNXZjJVUDU0Y1hIWTI0QUNMSlgwdEd3ZzNUeUpOTVV5dk1iTXNp?oc=5) ⭐️ 9/10

KAIST 的研究人员开发了一种基于 CMOS 的伊辛机，该机器利用振荡器来加速组合优化问题的求解。这种新的硬件方法利用标准硅晶体管技术，通过多个耦合元件的相互作用来寻找最优解。 这一突破具有重要意义，因为它为解决 NP 困难问题提供了一种可扩展的室温替代方案，可替代量子退火炉和庞大的光学伊辛机。通过依赖成熟的 CMOS 工艺技术，这种方法可以为应对复杂物流和路由挑战的行业带来高度实用、节能且紧凑的硬件加速器。 KAIST 的设计专注于以固定周期重复信号的基于振荡器的元件来表示伊辛自旋，将系统的能量最小化直接映射到优化问题的求解。最近相关的 CMOS 实现（例如使用双稳态锁存器和 FeFET 阵列进行耦合的实现）已经证明能够以高精度和低于 100 纳秒的稳定时间解决多达 50 个节点的图的 MaxCut 问题。

rss · Google News - Combinatorial Optimization · May 6, 05:03

**背景**: 伊辛机是一种专用计算机，旨在通过寻找伊辛模型的基态来解决组合优化问题，该模型是铁磁性的数学模型，其中离散变量代表磁偶极矩。组合优化问题（如旅行商问题或 MaxCut）涉及从有限的集合中寻找最佳解决方案，对于传统计算机而言在计算上是出了名的棘手。虽然量子退火炉和光学相干伊辛机（CIM）已展现出前景，但它们需要低温冷却或庞大的光纤，这使得 CMOS 兼容的实现对于实际的可扩展性极具吸引力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://biz.chosun.com/en/en-science/2026/05/06/OVIMDJIEHZEDPK5T6C43IUC7Q4/">KAIST builds CMOS Ising machine to speed combinatorial ...</a></li>
<li><a href="https://www.nature.com/articles/s41598-023-28217-8">CMOS-compatible ising machines built using bistable latches ... Scalable Ising machine composed entirely of Si transistors Low Power CMOS Stochastic Bit Based Ising Machine and Its ... A CMOS-compatible Ising Machine with Bistable Nodes A 28 nm Ising machine with adaptive majority voter and ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Ising_machine">Ising machine</a></li>

</ul>
</details>

**标签**: `#combinatorial optimization`, `#Ising machine`, `#CMOS hardware`, `#KAIST`, `#accelerator`

---

<a id="item-2"></a>
## [使用 MRC 和 SRv6 的弹性 AI 超算网络](https://arxiv.org/abs/2605.04333) ⭐️ 9/10

一篇新论文介绍了一种三管齐下的网络架构，其特色包括基于 RDMA 的 MRC 传输协议、多平面 Clos 拓扑以及静态 SRv6 源路由，从而消除了流碰撞并绕过了故障。该架构已成功部署在 OpenAI 和微软最大的训练集群中，用于在 10 万以上 GPU 规模下训练最新的前沿模型。 该架构直接解决了在 10 万以上 GPU 空前规模下同步预训练中尾延迟的关键瓶颈，防止网络故障中断昂贵且庞大的训练任务。它对 AI 基础设施做出了范式转变级的贡献，确保了下一代前沿模型的高吞吐量和弹性。 MRC 协议允许单个 RDMA 连接同时将流量分散到多条网络路径上以实现主动负载均衡，同时与现有的 RDMA 编程模型无缝集成。静态 SRv6 源路由为 MRC 提供了独立绕过网络故障的自由，而多平面 Clos 拓扑则允许将超过 10 万 GPU 的集群构建为两层拓扑，并增加物理冗余。

rss · arXiv cs.NI Networking and Internet Architecture · May 7, 04:00

**背景**: 像 RoCEv2 这样的传统 RDMA 传输通常依赖单一路径来传输特定流，这会在大规模 AI 训练集群的重负载下导致流碰撞和严重的尾延迟。Clos 拓扑通常用于构建可扩展网络，但标准设计在极端规模下面临交换机端口基数限制和故障恢复的困难。SRv6（基于 IPv6 的段路由）是一种网络架构，允许源节点使用段标识符指定通过网络路径，从而实现精确的流量工程，而无需在中间交换机中维护每流状态。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.servethehome.com/nvidia-spectrum-x-mrc-is-the-custom-rdma-transport-protocol-for-gigascale-ai/">NVIDIA Spectrum-X MRC is the Custom RDMA Transport Protocol for Gigascale AI - ServeTheHome</a></li>
<li><a href="https://www.amd.com/en/blogs/2026/next-gen-networking-transport-for-large-scale-ai-training.html">Next Gen Networking Transport for Large Scale AI Training</a></li>
<li><a href="https://www.segment-routing.net/images/20250630-SRv6-uSID-SONiC-FRR.pdf">[PDF] SRv6 uSID in SONiC - Segment-Routing.net</a></li>

</ul>
</details>

**标签**: `#AI Infrastructure`, `#High-Performance Networking`, `#Distributed Systems`, `#RDMA`, `#SRv6`

---

<a id="item-3"></a>
## [LCM：无损上下文管理性能超越 Claude Code](https://arxiv.org/abs/2605.04050) ⭐️ 9/10

研究人员提出了无损上下文管理（LCM），这是一种用于 LLM 内存的确定性架构，采用了递归上下文压缩和任务分区技术。当与 Opus 4.6 模型结合并在其 Volt 编码智能体中运行时，LCM 在 OOLONG 基准测试中从 32K 到 1M token 的所有上下文长度上均超越了 Claude Code。 这代表了上下文管理领域的重大范式转变，证明了确定性、结构化的内存架构能够超越具有原生文件系统访问权限的前沿模型。它为复杂的 AI 智能体工程提供了一种可扩展的解决方案，确保随着上下文长度的增长，系统能拥有无限内存且不会丢失先前的状态。 LCM 将符号递归分解为两种确定性机制：使用分层摘要 DAG 的递归上下文压缩（保留指向原始消息的无损指针），以及使用 LLM-Map 等引擎管理的并行原语的递归任务分区。这种设计牺牲了最大的灵活性，以换取终止保证、短任务上的零成本连续性以及无损可检索性，类似于编程语言设计中从 GOTO 到结构化控制流的转变。

rss · arXiv cs.AI Artificial Intelligence · May 7, 04:00

**背景**: 递归语言模型（RLM）是一种推理策略，允许语言模型分解并递归地与输入进行交互，使其能够处理远超标准上下文窗口的内容。OOLONG 基准测试通过要求模型在原子级别分析单个文本块并聚合这些分析来回答分布性问题，从而评估长上下文推理能力。LCM 通过用确定性的引擎管理操作取代模型编写的循环，扩展了 RLM 范式，从而解决了纯符号递归中固有的灵活性和终止问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/stephenschoettler/hermes-lcm">GitHub - stephenschoettler/hermes-lcm: Lossless Context Management plugin for Hermes Agent — DAG-based context engine that never loses a message</a></li>
<li><a href="https://arxiv.org/abs/2512.24601">[2512.24601] Recursive Language Models - arXiv</a></li>
<li><a href="https://arxiv.org/abs/2511.02817">[2511.02817] Oolong: Evaluating Long Context Reasoning and Aggregation Capabilities</a></li>

</ul>
</details>

**标签**: `#LLM`, `#Context Management`, `#Recursive Models`, `#AI Agents`, `#Long Context`

---

<a id="item-4"></a>
## [中性原子量子架构上拉马努金超图的最优对数路由](https://arxiv.org/abs/2605.02498) ⭐️ 9/10

本文证明了具有 N 个顶点的拉马努金(d,r)-正则超图的路由数满足Θ(log N)，并引入了新颖的特征值居中条件来取代传统的双侧谱隙假设。该研究还为 3D 声光透镜(AOL)架构建立了容量-深度权衡，证明多层堆叠可通过 O(log N)个独立覆盖层实现Θ(log N)的路由。 这一理论突破为扩展中性原子量子计算机提供了最优路由边界，直接影响了量子架构的软硬件协同设计。通过将数学框架从双侧谱隙简化为单侧特征值居中，它为解决量子量子比特路由中的组合优化问题开辟了新途径。 研究表明，通过预分配的贝尔对进行纠缠辅助路由可实现 O(log N)的传态深度，并在约 4 个路由轮次处出现稳定交叉。此外，混合贪心-Valiant 协议在实际规模下实现了约 3 倍的加速，而阿贝尔 Alon-Boppana 屏障证明了 Z_n^2 上的固定度 Cayley 图不能是拉马努金图。

rss · arXiv cs.DS Data Structures and Algorithms · May 7, 04:00

**背景**: 拉马努金图是谱图理论中的正则图，其谱隙几乎达到最大可能值，这使其成为非常适合高效网络路由的出色谱扩展子。中性原子量子计算机利用由声光透镜(AOL)控制的高度聚焦激光束，在 3D 空间中物理移动（穿梭）原子以执行双量子比特门。超图路由通过允许连接两个以上顶点的超边来推广传统图路由，这能更好地对量子架构中的多量子比特交互进行建模。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ramanujan_graph">Ramanujan graph - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2605.02498">[2605.02498] Permutation Routing on Ramanujan Hypergraphs with Applications to Neutral Atom Quantum Architectures</a></li>
<li><a href="https://arxiv.org/abs/2510.09398">[2510.09398] Acousto-optic lens for 3D shuttling of atoms in a neutral atom quantum computer</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#combinatorial optimization`, `#hypergraph routing`, `#neutral atom architectures`, `#spectral graph theory`

---

<a id="item-5"></a>
## [Vibe Coding 与 Agentic Engineering 正在趋同](https://simonwillison.net/2026/May/6/vibe-coding-and-agentic-engineering/#atom-everything) ⭐️ 8/10

Simon Willison 意识到，在他自己的工作中，非正式的“vibe coding”与严谨的“agentic engineering”之间的界限正在变得模糊，因为 AI 编程代理已经足够可靠，以至于他甚至在生产系统中也不再审查每一行生成的代码。 这种趋同挑战了先前的一种假设，即专业工程师可以安全地将 AI 的随意使用与严谨的生产标准隔离开来；随着 AI 工具变得越来越自主，这引发了关于问责制、代码质量和负责任部署的关键问题。 Willison 指出，对于构建带有 SQL 的 JSON API 端点等常规任务，像 Claude Code 这样的 AI 代理现在能够持续生成正确的代码以及自动化测试和文档，这诱使工程师跳过手动审查，尽管他们对此感到内疚。

rss · Simon Willison · May 6, 14:24

**背景**: Vibe coding 由 Andrej Karpathy 于 2025 年 2 月提出，是指一种 AI 辅助编程实践，用户在不进行彻底审查的情况下接受生成的代码，而是依赖自然语言提示和运行结果。相比之下，agentic engineering 是一种严谨的方法，强调人类监督和工程严谨性，将 AI 代理作为工具来构建更高质量的生产系统，而不仅仅是更快但质量低下的系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding</a></li>
<li><a href="https://addyosmani.com/blog/agentic-engineering/">AddyOsmani.com - Agentic Engineering</a></li>

</ul>
</details>

**社区讨论**: 社区强调，AI 的“参差前沿”使其在弥补个人知识盲区方面表现出色，但在关键系统中却存在风险；评论者认为 LLM 并没有创造不严谨的工程，而只是暴露并加速了现有的薄弱实践。几位评论者反驳了 Willison 对 AI 的信任，警告说虽然 AI 生成的代码可能编译并运行，但通常包含微妙的边缘情况错误、安全漏洞或可疑的架构决策，仍需要人工仔细审查。

**标签**: `#AI Coding`, `#Agentic Engineering`, `#Software Engineering`, `#LLM`, `#Developer Tools`

---

<a id="item-6"></a>
## [Anthropic 提升 Claude 使用限额并与 SpaceX 签署大规模算力协议](https://www.anthropic.com/news/higher-limits-spacex) ⭐️ 8/10

Anthropic 大幅提升了 Claude 订阅用户的使用限额（包括将 Claude Code 限额翻倍），并与 SpaceX 签署了一项重大算力协议，以使用位于孟菲斯的 Colossus 1 超级计算机。该协议为 Anthropic 提供了超过 300 兆瓦的电力容量和超过 22 万个 Nvidia GPU，包括 H100、H200 和 GB200 加速器。 这项合作意义重大，因为它使一家专注于 AI 安全的初创公司获得了大规模的即时基础设施扩展能力，从而能够与行业巨头竞争，同时也暗示了未来的轨道计算网络。此外，这代表了 Anthropic 与埃隆·马斯克生态系统之间令人惊讶的休战，因为 Anthropic 租用了最初为马斯克的竞争对手 xAI 建造的数据中心容量。 新增的算力将直接提升 Claude Pro、Max、Team 和 Enterprise 用户的容量，并减少高峰时段的限制。作为协议的一部分，Anthropic 还表达了与 SpaceX 合作开发未来数吉瓦级轨道 AI 算力容量的兴趣。

hackernews · meetpateltech · May 6, 16:17

**背景**: Colossus 1 超级计算机是位于田纳西州孟菲斯的一个大型数据中心，最初由 xAI 建造用于训练其 Grok 模型。对于希望训练最先进模型并为数百万用户提供服务的 AI 公司来说，获取数十万个高级 GPU 目前是最大的瓶颈。由于容量限制，Anthropic 此前一直在高峰时段调整和限制 Claude 的使用限额。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/higher-limits-spacex">Higher usage limits for Claude and a compute deal with SpaceX</a></li>
<li><a href="https://x.ai/news/anthropic-compute-partnership">New Compute Partnership with Anthropic | xAI</a></li>
<li><a href="https://www.cnbc.com/2026/05/06/anthropic-spacex-data-center-capacity.html">Anthropic, SpaceX announce compute deal, includes space ...</a></li>

</ul>
</details>

**社区讨论**: 社区讨论突显了一家 AI 安全公司租用其竞争对手 xAI 建造的数据中心所带来的强烈讽刺感，同时还有对 Colossus 设施非法用电、空气污染以及可能污染孟菲斯水资源的严重环境担忧。评论者还对 22 万个 GPU 用于推理和训练的惊人规模感到震惊，并指出这种对算力的争夺验证了关于 AI 需要大规模基础设施建设的预测。

**标签**: `#AI Infrastructure`, `#Anthropic`, `#SpaceX`, `#Compute Scaling`, `#Industry News`

---

<a id="item-7"></a>
## [中国批准首个卫星物联网业务商用试验](https://news.google.com/rss/articles/CBMifkFVX3lxTE1qUXJHNXlwamliUXhJT0pXTnJrbTJnajk4dlhFbUNiY1I5bl9KenRHYWUxX1hzclVkV2VPaVU0NGhxMnFybUZ6UTdWekNveUlORFBnVmJGX3dqbmE1cVNUZDFvNEZzSWMzamRKRlBVcUNBajF2R01hNXhUWnV5QQ?oc=5) ⭐️ 8/10

中国工业和信息化部（MIIT）批准了全国首个卫星物联网业务商用试点，特别批准了国电高科开展此项业务。这一监管里程碑标志着卫星物联网从实验研究正式向商业部署和应用过渡。 此次获批意义重大，因为它为实用的天基物联网网络铺平了道路，使其能够在地面网络无法覆盖的偏远和服务欠缺地区提供弹性且可靠的连接。它通过将卫星基础设施与物联网解决方案相整合，直接加速了商业航天领域的商业化进程，并拓展了边缘计算的生态系统。 该商用试验专门授权国电高科运营卫星物联网业务，这表明在推出天基网络时采取了受控的、监管优先的方式。该计划利用低地球轨道（LEO）卫星技术，确保地面网络与卫星网络之间的互操作性，以实现无缝的物联网通信。

rss · Google News - Edge Computing and IoT · May 7, 01:40

**背景**: 卫星物联网利用卫星通信连接全球各地的物联网设备，确保在缺乏传统蜂窝或地面基础设施的偏远、农村或海洋环境中提供网络覆盖。现代天基物联网网络越来越依赖低地球轨道（LEO）星座来提供低延迟、可靠的通信。该技术正不断发展以与 5G 标准（如 IoT-NTN，非地面网络）相集成，从而实现在地面和卫星连接之间无缝切换的混合解决方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.viasat.com/perspectives/enterprise/2024/satellite-iot-the-future-of-networking/">Satellite Internet of Things (IoT): the future of networking</a></li>
<li><a href="https://www.iotforall.com/types-of-satellite-networks-used-in-iot-solutions">Types of Satellite Networks Used in IoT Solutions | IoT For All</a></li>
<li><a href="https://www.abiresearch.com/blog/5-ways-satellite-iot-is-changing">5 Ways Satellite IoT Is Changing - ABI Research</a></li>

</ul>
</details>

**标签**: `#IoT`, `#Satellite Communication`, `#Edge Computing`, `#Commercialization`, `#Regulation`

---

<a id="item-8"></a>
## [VLM 将自然语言转化为逻辑以实现安全导航](https://arxiv.org/abs/2605.04327) ⭐️ 8/10

一种新架构提出使用视觉语言模型（VLM）将自然语言安全规则和偏好转化为信号时序逻辑（STL）规范和 2D 代价地图，用于自主导航。该方法弥合了高级人类指令与严格数学逻辑之间的差距，以在非结构化户外环境中实现形式化保证的安全导航。 这种整合具有重要意义，因为它允许无人机和边缘机器人等自主系统实时理解并遵守人类定义的复杂安全约束，而无需手动进行数学编码。它提高了自主系统在不可预测的非结构化环境中导航的安全性和可靠性，而传统的基于规则的系统在这些环境中往往会失效。 持久的、以环境为中心的规则和地形偏好被转化为 2D 代价地图，而时间动态需求则被表达为在运行时监控的 STL 规范。该架构利用 VLM 进行零样本场景理解，将人类指令映射到语义特征和环境约束，并利用形式化满足度指标来确保合规性。

rss · arXiv cs.RO Robotics · May 7, 04:00

**背景**: 信号时序逻辑（STL）是一种形式化规范语言，用于表达实值信号上的时序属性，通常应用于信息物理系统和混合系统以进行严格的系统验证。视觉语言模型（VLM）结合了视觉和文本理解能力，使机器人能够通过评估视觉数据中的地形属性（如可变形性和滑移性）来进行零样本场景理解和物理基础导航。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/signal-temporal-logic-stl">Signal Temporal Logic (STL)</a></li>
<li><a href="https://arxiv.org/html/2409.20445v1">VLM-GroNav: Robot Navigation Using Physically Grounded Vision-Language Models in Outdoor Environments</a></li>

</ul>
</details>

**标签**: `#safe navigation`, `#vision-language models`, `#signal temporal logic`, `#robotics`, `#autonomous systems`

---

<a id="item-9"></a>
## [标量不可约动力学实现内生体制切换](https://arxiv.org/abs/2605.04054) ⭐️ 8/10

最近的一篇论文引入了一种新的分类方法，将标量可约动力学与标量不可约动力学区分开来，并证明后者能够在没有外部调度的情况下自然地实现内生体制切换。作者构建了一个最小动力学模型，展示了快速动态变量与慢速结构适应之间的反馈如何产生持续的、内部生成的体制转换。 这一发现具有重要意义，因为它为实现自主智能提供了一种新的动力学范式，在这种范式中，适应性行为是由内部组织而不是外部规定的。它直接解决了现有机器学习框架中的一个核心挑战，即这些框架通常依赖于外部强加的转换，从而为真正的自主学习系统铺平了道路。 大多数现有的机器学习系统都在标量可约类别内运行，这意味着它们可以表示为由标量目标驱动的梯度流，这种结构限制了它们生成内生体制转换的能力。相比之下，标量不可约动力学不能简化为单一的标量目标流，从而允许快速变量和慢速适应之间形成必要的反馈回路，以自主触发体制转换。

rss · arXiv cs.LG Machine Learning · May 7, 04:00

**背景**: 在机器学习中，大多数优化过程（如梯度下降）都是标量可约的，这意味着它们遵循最小化单一标量损失函数的轨迹。体制切换是指系统在不同的行为状态或操作模式之间进行转换；在当前的机器学习中，这通常通过外部干预来处理，例如学习率调度或课程设计。然而，内生体制切换意味着系统根据其内部状态动力学自主决定改变其操作模式。这个概念对于自主智能至关重要，因为它模仿了生物系统在没有外部提示的情况下调整其学习策略的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2605.04054v1">Endogenous Regime Switching Driven by Scalar-Irreducible ...</a></li>

</ul>
</details>

**标签**: `#reinforcement learning`, `#dynamical systems`, `#autonomous intelligence`, `#regime switching`, `#machine learning theory`

---

<a id="item-10"></a>
## [BOOOM：Stiefel 流形上的无导数优化](https://arxiv.org/abs/2605.04087) ⭐️ 8/10

该论文提出了 BOOOM，一个针对 Stiefel 流形的无导数黑盒优化框架，它使用基于全局 Givens 旋转的参数化方法，将受约束的流形问题映射到无约束的欧几里得角度空间，同时精确保持可行性。 该框架显著扩展了正交矩阵优化在非平滑、非凸和黑盒环境中的适用性，而传统的基于梯度的黎曼优化或凸松弛方法在这些环境中往往会失效。它为独立成分分析和稀疏矩阵分解等多种机器学习和统计推断任务提供了稳健的工具，特别是在高度多模态的情况下。 BOOOM 采用了一种基于递归修正模式搜索的结构化、可并行化的无导数搜索方法，通过平面旋转实现系统性探索，而无需梯度信息。作者建立了一个统一的理论框架，证明了角度空间与流形优化之间的等价性、平稳性的转移，以及在温和条件下的概率全局收敛性。

rss · arXiv math.OC Optimization and Control · May 7, 04:00

**背景**: Stiefel 流形是所有列正交矩阵的集合，在需要正交性约束的统计学、机器学习和科学计算中频繁出现。Givens 旋转是数值线性代数中的一种基本操作，在由两个坐标轴张成的平面内执行旋转，为参数化正交变换提供了一种自然的方式。递归修正模式搜索是一种最初为概率单纯形等约束空间设计的无导数黑盒优化技术，它通过向当前解添加导出的步长向量来系统地探索搜索空间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Stiefel_manifold">Stiefel manifold</a></li>
<li><a href="https://en.wikipedia.org/wiki/Givens_rotation">Givens rotation - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/1604.08636">[1604.08636] Recursive Modified Pattern Search on High ... Recursive Modified Pattern Search on High-Dimensional Simplex ... RMPSS: 'Recursive Modified Pattern Search on Simplex' can be ... RMPSH: Recursive Modified Pattern Search on Hyper-Rectangle [1604.08636] Recursive Modified Pattern Search on High ... Images Recursive Modified Pattern Search on High-Dimensional Simplex ... RMPSS package - RDocumentation</a></li>

</ul>
</details>

**标签**: `#combinatorial optimization`, `#machine learning`, `#black-box optimization`, `#Stiefel manifold`, `#derivative-free optimization`

---