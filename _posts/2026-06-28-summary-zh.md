---
layout: default
title: "Horizon Summary: 2026-06-28 (ZH)"
date: 2026-06-28
lang: zh
---

> 从 69 条内容中筛选出 29 条重要资讯。

---

1. [DeepSeek 与北大发布 DSpark，LLM 推理速度提升 60-85%](#item-1) ⭐️ 9.0/10
2. [我国核聚变超导磁体取得世界领先突破](#item-2) ⭐️ 9.0/10
3. [高通计划 2028 年将数据中心 AI 芯片引入手机](#item-3) ⭐️ 8.0/10
4. [苹果 Vision Pro 负责人跳槽 OpenAI 组建硬件部门](#item-4) ⭐️ 8.0/10
5. [AI 算力需求引爆功率半导体涨价潮](#item-5) ⭐️ 7.0/10
6. [苹果寻求美国批准从中国长鑫存储购买内存芯片](#item-6) ⭐️ 7.0/10
7. [马斯克获 FTC 批准收购光模块初创公司 Mesh](#item-7) ⭐️ 7.0/10
8. [特朗普政府或在一周内解除 Anthropic Fable 5 禁令](#item-8) ⭐️ 7.0/10
9. [中国电子行业利润翻倍；SpaceX 拟收购光模块公司](#item-9) ⭐️ 7.0/10
10. [AI 基建投资推高通胀，美联储面临新挑战](#item-10) ⭐️ 7.0/10
11. [半导体巨头加码先进封装，AI 需求引爆壁垒环节](#item-11) ⭐️ 7.0/10
12. [AI 隐私转变：Vitalik、NVIDIA 与 Arcium](#item-12) ⭐️ 7.0/10
13. [大秦数字能源锂价豪赌失利后冲刺港股 IPO](#item-13) ⭐️ 6.0/10
14. [G7 易流发布穿戴式 AI 硬件，填补物流交付最后两米](#item-14) ⭐️ 6.0/10
15. [国内首个第四代半导体全产业链项目落户郑州](#item-15) ⭐️ 6.0/10
16. [触屏 MacBook Pro 传闻跳过 M6 芯片，首发 M5](#item-16) ⭐️ 6.0/10
17. [美国监管机构因 OTA 修复结束特斯拉转向调查](#item-17) ⭐️ 6.0/10
18. [A+H 股企业主导港股 IPO 前十](#item-18) ⭐️ 6.0/10
19. [诺奖得主警告：AI 失业恐慌或成自我实现预言](#item-19) ⭐️ 6.0/10
20. [高纯度二氧化碳短缺威胁半导体生产](#item-20) ⭐️ 6.0/10
21. [Meta 探索预测市场应用 Arena，与 Polymarket 和 Kalshi 合作](#item-21) ⭐️ 6.0/10
22. [美国企业 AI 应用加速：RBC 调查显示从试点转向生产](#item-22) ⭐️ 6.0/10
23. [2026 年 1-5 月中国电子行业利润增长 103.9%](#item-23) ⭐️ 6.0/10
24. [拓荆科技拟收购尚积半导体，拓展 PVD 与刻蚀](#item-24) ⭐️ 6.0/10
25. [AI 早报：DeepSeek 开源 DSpark，OpenAI 更新](#item-25) ⭐️ 6.0/10
26. [梅赛德斯-奔驰因利润暴跌推迟 9 万名德国员工奖金](#item-26) ⭐️ 5.0/10
27. [北大哲学系主任毕业致辞引发共鸣](#item-27) ⭐️ 5.0/10
28. [欧洲热浪引发空调短缺和价格上涨](#item-28) ⭐️ 5.0/10
29. [美线欧线运价回落，航司看好下半年需求](#item-29) ⭐️ 5.0/10

---

<a id="item-1"></a>
## [DeepSeek 与北大发布 DSpark，LLM 推理速度提升 60-85%](https://www.zhihu.com/question/2054255700407055156) ⭐️ 9.0/10

DeepSeek 与北京大学联合发布了 DSpark 推理加速框架，通过半自回归推测解码技术，将大语言模型单用户生成速度提升 60%~85%。该框架已部署在 DeepSeek-V4-Flash 和 DeepSeek-V4-Pro 的预览版引擎中。 该技术大幅降低了大语言模型的推理延迟并提高了生产环境中的吞吐量，解决了大规模部署大模型的关键瓶颈。开源发布使 AI 社区能够采用并在此基础上进行改进。 DSpark 结合了并行主干网络和轻量级顺序模块（马尔可夫头或 RNN 头）进行候选生成，并引入了基于置信度的调度机制动态调整验证长度以最大化吞吐量。在多个基准测试中，它的平均接受长度优于 Eagle3 和 DFlash。

rss · 知乎热榜 · 6月27日 09:32

**背景**: 大语言模型以自回归方式生成文本，每个 token 都需要一次完整的前向传播，延迟随输出长度线性增长。推测解码通过让小模型生成候选 token，再由大模型并行验证来加速推理，同时保持输出质量。DSpark 采用半自回归方法提升草稿质量，并优化了生产负载下的验证调度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cryptobriefing.com/deepseek-dspark-faster-inference/">DeepSeek unveils DSpark for 60% to 85% faster inference optimization</a></li>
<li><a href="https://www.kucoin.com/news/flash/deepseek-launches-dspark-to-boost-inference-speed-by-60-to-85">DeepSeek Launches DSpark to Boost Inference Speed by 60% to 85% | KuCoin</a></li>

</ul>
</details>

**标签**: `#DeepSeek`, `#LLM Inference`, `#Speculative Decoding`, `#AI Acceleration`, `#Open Source`

---

<a id="item-2"></a>
## [我国核聚变超导磁体取得世界领先突破](https://www.cls.cn/detail/2410829) ⭐️ 9.0/10

我国成功研制出全球最大的聚变堆环向场超导磁体并通过验收，同时完成了高温超导中心螺管线圈磁体的满工况测试，性能创纪录。 这些突破展示了我国在聚变磁体关键技术上的完全自主能力，推进了实用化聚变能研发进程，减少了对国外供应商的依赖。 环向场磁体长 21 米、宽 12 米、高 3.3 米，重 582 吨，是聚变堆主机关键系统综合研究设施的一部分。中心螺管线圈在产生和控制等离子体电流方面达到国际领先水平。

rss · 财联社深度 · 6月27日 02:06

**背景**: 托卡马克等聚变堆利用强磁场约束上亿摄氏度的高温等离子体。环向场磁体产生主约束磁场，中心螺管线圈驱动等离子体电流并控制等离子体形态。这些磁体需要在低温下运行并承受巨大应力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://global.chinadaily.com.cn/a/202606/27/WS6a3f7ed0a310986e2b4623db.html">World's largest superconducting magnet for fusion reactor ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tokamak">Tokamak - Wikipedia</a></li>
<li><a href="https://www.energy.gov/science/doe-explainstokamaks">DOE Explains...Tokamaks | Department of Energy</a></li>

</ul>
</details>

**标签**: `#fusion`, `#superconducting magnets`, `#plasma confinement`, `#energy technology`, `#Chinese science`

---

<a id="item-3"></a>
## [高通计划 2028 年将数据中心 AI 芯片引入手机](https://36kr.com/newsflashes/3871117388174336?f=rss) ⭐️ 8.0/10

高通宣布计划将其最新推出、原用于数据中心的高带宽计算（HBC）架构适配到智能手机中，以提升设备端 AI 性能，首批商用产品预计于 2028 年推出。 此举可能大幅缩小云端与边缘端 AI 能力的差距，使智能手机直接支持更强大、更私密、低延迟的 AI 应用。这也标志着高通将其数据中心创新成果向移动市场战略转移。 HBC 架构采用 3D 垂直堆叠技术将内存与计算单元紧密集成，每瓦带宽较 HBM 提升高达 6 倍。首批 HBC 产品将于 2026 年在数据中心推出，面向智能手机的适配版本预计 2028 年问世。

rss · 36氪 · 6月27日 07:44

**背景**: 设备端 AI 需要高内存带宽和能效，这在当前智能手机中常是瓶颈。高通最初为数据中心 AI 工作负载开发的 HBC 架构通过芯片堆叠来克服这些挑战。该技术利用硅通孔（TSV）和 3D 集成，将 LPDDR DRAM 芯片直接堆叠在计算单元上方。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cls.cn/detail/2409266">剑指内存墙问题 高通发布HBC架构 带宽较HBM大幅提升</a></li>
<li><a href="https://tech.ifeng.com/c/8uEr8BQlVFT">高通带来数据中心组合：HBC架构、C1000 CPU、AI300推理加速器_凤凰网</a></li>
<li><a href="https://technews.tw/2026/06/25/qualcomm-high-bandwidth-compute-tech/">瞄準 AI 記憶體牆！高通發表最新 HBC 架構，每瓦頻寬較 HBM 提升 6 倍 | TechNews 科技新報</a></li>

</ul>
</details>

**标签**: `#Qualcomm`, `#AI`, `#smartphone`, `#chip architecture`, `#edge computing`

---

<a id="item-4"></a>
## [苹果 Vision Pro 负责人跳槽 OpenAI 组建硬件部门](https://www.cls.cn/detail/2410940) ⭐️ 8.0/10

苹果视觉产品业务副总裁 Paul Meade 即将离职，加入 OpenAI 负责组建并领导全新的硬件部门，专注于 AI 设备的研发。 此次高管变动表明 OpenAI 正大力进军消费级 AI 硬件领域，引入苹果最雄心勃勃产品的高管。这可能会加速 AI 原生设备的到来，与智能手机和头显展开竞争。 Meade 领导了 Vision Pro 硬件工程长达七年，并负责苹果智能眼镜项目。他于 2017 年加入苹果视觉产品团队，此前曾参与 iPad 和 iPhone 的硬件研发。

rss · 财联社深度 · 6月27日 11:15

**背景**: OpenAI 一直在拓展硬件业务，2025 年 5 月以 65 亿美元收购了 Jony Ive 创立的初创公司 'io'。据悉，Ive 的设计团队正在开发多款 AI 设备，其中包括一款预计 2027 年上市的智能音箱。OpenAI 首席财务官 Sarah Friar 暗示第一款产品可能在 2025 年底前亮相。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Io_(company)">io (company) - Wikipedia</a></li>
<li><a href="https://applemagazine.com/openai-acquires-jony-ives-ai-hardware-startup-io-in-6-5-billion-deal/">OpenAI Acquires Jony Ive’s AI Hardware Startup io in $6.5 ...</a></li>

</ul>
</details>

**标签**: `#Apple`, `#OpenAI`, `#AI hardware`, `#Vision Pro`, `#executive departure`

---

<a id="item-5"></a>
## [AI 算力需求引爆功率半导体涨价潮](https://36kr.com/newsflashes/3871215128237313?f=rss) ⭐️ 7.0/10

包括扬杰科技、宏微科技在内的多家中国功率半导体企业今年已进行第二轮涨价，原因是 AI 相关电源订单暴增以及原材料成本上升。部分厂商表示，AI 电源订单'爆满'，产能根本跟不上。 这一涨价趋势表明，在 AI 数据中心功耗需求的推动下，功率半导体正成为继存储之后的下一个产业增长引擎。行业洗牌将加速，市场份额向具备 IDM 全链条能力的头部企业集中，从而影响 AI 基础设施等高景气领域的下游成本。 涨价呈阶梯式推进，依次受封装金属材料（金、铜）、晶圆制造特种气体以及 AI 需求放大等因素驱动。业内预计本轮成本驱动的涨价周期仍将持续，并加速低端功率器件产能出清。

rss · 36氪 · 6月27日 09:23

**背景**: 功率半导体是用于管理和转换电能的器件，广泛应用于从手机到数据中心的各类设备。IDM（垂直整合制造）模式指同时具备设计与制造能力的企业，能更好地控制成本与供应链。在数据中心中，800V HVDC 电源和服务器二次电源对于高效供电至 AI 计算集群至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Direct_current">Direct current - Wikipedia</a></li>
<li><a href="https://eu.36kr.com/en/p/3412636905540993">Next Stop for Data Centers: 800 V Power Supply !</a></li>
<li><a href="https://en.wikipedia.org/wiki/Foundry_model">Foundry model - Wikipedia</a></li>

</ul>
</details>

**标签**: `#功率半导体`, `#AI算力`, `#涨价`, `#电源管理`, `#半导体产业链`

---

<a id="item-6"></a>
## [苹果寻求美国批准从中国长鑫存储购买内存芯片](https://36kr.com/newsflashes/3871131045876995?f=rss) ⭐️ 7.0/10

苹果正向美国政府游说，希望获批从中国制造商长鑫存储（CXMT）采购 DRAM 内存芯片，以缓解内存成本上涨的压力。 若获批，此举将分散苹果的供应链，并挑战当前三星、SK 海力士和美光三巨头对 DRAM 市场的垄断，可能在地缘政治紧张局势下重塑全球半导体供应链格局。 长鑫存储成立于 2016 年，2025 年开始生产 DDR5 DRAM，季度产能达到 72 万片晶圆。苹果近期因内存成本上涨上调了 MacBook 和 iPad 售价，市值单日蒸发 2630 亿美元。

rss · 36氪 · 6月27日 07:58

**背景**: DRAM（动态随机存取存储器）是一种广泛应用于计算机和移动设备的易失性存储器。全球 DRAM 市场长期由三星、SK 海力士和美光三大巨头主导。长鑫存储是中国领先的 DRAM 制造商，但受到美国出口管制，其产品和设备采购需获得美国政府批准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ChangXin_Memory_Technologies">ChangXin Memory Technologies</a></li>
<li><a href="https://www.cxmt.com/en/">About cxmt - cxmt</a></li>

</ul>
</details>

**标签**: `#Apple`, `#semiconductors`, `#memory chips`, `#CXMT`, `#supply chain`

---

<a id="item-7"></a>
## [马斯克获 FTC 批准收购光模块初创公司 Mesh](https://36kr.com/newsflashes/3871125571802116?f=rss) ⭐️ 7.0/10

美国联邦贸易委员会（FTC）批准了埃隆·马斯克对 Mesh Optical Technologies 的收购，这家由前 SpaceX 工程师创立的初创公司开发用于 AI 和数据中心互连的 1.6Tbps 光学收发器。 此次收购可能通过用低延迟、高能效的光纤链路取代传统铜缆，显著提升马斯克旗下数据中心（包括 xAI 设施）的效率，有望降低 AI 训练成本和功耗。 Mesh 的核心产品 Alpha C1 光学收发器采用倒装芯片键合工艺（也用于现代处理器封装）实现 1.6 Tbps 速率。该公司于 2024 年 2 月完成了由 Thrive Capital 领投的超过 5000 万美元 A 轮融资。

rss · 36氪 · 6月27日 07:52

**背景**: 光学收发器将电信号转换为光信号，通过光纤实现高速数据传输，这在 AI 数据中心中日益关键，因为 GPU 需要以极高带宽通信。传统的铜缆互连在速度、距离和能效方面面临限制。该公司创始人曾为 SpaceX 的星链星座设计激光星间链路，因而在光通信领域拥有独特专长。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://post.smzdm.com/p/a5rvqlr8/">马斯克又下一城！ FTC批准 收 购 光 通信公司， 1 . 6 Tbps ...</a></li>
<li><a href="https://grokipedia.com/page/Mesh_Optical_Technologies">Mesh Optical Technologies</a></li>
<li><a href="https://www.meshoptical.com/blog/introducing-mesh">Introducing Mesh - Mesh Optical</a></li>

</ul>
</details>

**标签**: `#acquisition`, `#optical interconnect`, `#AI infrastructure`, `#Elon Musk`, `#data center networking`

---

<a id="item-8"></a>
## [特朗普政府或在一周内解除 Anthropic Fable 5 禁令](https://www.cls.cn/detail/2410998) ⭐️ 7.0/10

据报道，特朗普政府最快可能在一周内解除对 Anthropic 的 Fable 5 模型的限制，此前该模型自 2026 年 6 月 12 日起被禁止使用 15 天。与此同时，政府已允许 Anthropic 的 Mythos 5 模型向超过 100 家可信合作伙伴有限开放。 这一决定可能显著影响开发者和企业获取前沿 AI 模型的机会，同时也将塑造围绕 AI 安全和出口管制的持续辩论。解除限制可能加速强大编码和推理模型的采用，但也引发了对潜在滥用的担忧。 Fable 5 是一款 Mythos 级别模型，拥有 100 万 token 的上下文窗口，因其编码和深度推理能力而备受赞誉。美国国防部和国家安全局尚未批准最终方案，现有付费订阅用户是否能在无需额外付费和身份验证的情况下恢复使用仍不明确。

rss · 财联社深度 · 6月28日 00:49

**背景**: 2026 年 6 月 12 日，美国政府以安全为由发布出口管制令，要求 Anthropic 停止向所有用户提供其最先进的 AI 模型——Mythos 5 和 Fable 5。出口管制是政府限制敏感技术向外国实体转移的法规。Anthropic 的模型属于业界最强大的模型之列，Fable 5 是其最强的通用模型，而 Mythos 5 则是专门的网络安全模型。特朗普政府近期致信 Anthropic，表示可信合作伙伴及获批公司的外籍员工可以在无需出口许可证的情况下使用 Mythos 5。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/claude/mythos">Claude Mythos \ Anthropic</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#Anthropic`, `#Fable 5`, `#export controls`, `#AI safety`

---

<a id="item-9"></a>
## [中国电子行业利润翻倍；SpaceX 拟收购光模块公司](https://www.cls.cn/detail/2410988) ⭐️ 7.0/10

2026 年前五个月，中国电子行业利润同比增长 103.9%，对全部规模以上工业企业利润增长的贡献率达 43.1%。此外，SpaceX 正在考虑收购 Mesh Optical Technologies，这是一家由前 SpaceX 工程师创立的初创公司，专为 AI 数据中心开发光模块。 中国电子行业的利润大幅增长凸显了其在全球竞争力的提升，尤其是在光模块和电子元件领域。同时，SpaceX 收购 Mesh 的潜在动作表明其在 AI 数据中心领域的战略布局，这可能会加剧光模块市场的竞争。 电子元件及电子专用材料制造行业利润分别增长 665.4%和 19.7%。Mesh Optical Technologies 声称其光模块比现有方案能效更高、延迟更低。SpaceX 的收购正接受美国联邦贸易委员会的反垄断审查。

rss · 财联社深度 · 6月27日 23:00

**背景**: 中国电子行业包括计算机、通信设备和电子元件的制造。由于工厂开工率下降，半导体先进制程所需的高纯度二氧化碳供应也出现短缺。光模块将电信号转换为光信号用于高速数据传输，对 AI 数据中心至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.futunn.com/post/75193182/musk-plans-to-acquire-optical-module-company-mesh-spacex-s">马斯克拟收购光模块公司Mesh：SpaceX算力业务有望得到加强</a></li>
<li><a href="https://www.ithome.com/0/969/291.htm">马斯克获准收购初创公司 Mesh，加码 AI 数据中心光通信布局 - IT之家</a></li>

</ul>
</details>

**标签**: `#Semiconductors`, `#AI`, `#Optical Modules`, `#Space`, `#Electronics`

---

<a id="item-10"></a>
## [AI 基建投资推高通胀，美联储面临新挑战](https://www.cls.cn/detail/2410977) ⭐️ 7.0/10

科技巨头大幅增加 AI 基础设施建设投入，推高了芯片、内存和建筑工人的需求，并已开始反映在通胀数据中。分析人士警告，这可能通过推高中性利率，给美联储的货币政策带来复杂挑战。 这一分析表明，AI 在初期阶段可能具有通胀效应，而非此前预期的通缩效应，这与 AI 将压低通胀、允许降息的预期相悖。美联储必须在等待长期生产率提升（可能需要数年）的同时，应对短期价格压力。 TD Cowen 估计，主要云服务商今年的资本开支将达到 7450 亿美元，并在 2027-2028 年超过每年 1 万亿美元，占 GDP 比重从 2020 年的不到 0.5%升至 2025 年的约 3%。苹果已因内存和存储成本上升提高了 iPad 和 MacBook 价格，预计更广泛的价格影响将持续。

rss · 财联社深度 · 6月27日 19:44

**背景**: 中性利率是指既不刺激也不抑制经济增长的联邦基金利率水平。当中性利率上升时，美联储可能需要提高政策利率以避免经济过热。液冷系统越来越多地用于 AI 数据中心，以管理如谷歌 TPU v8 等大功率芯片的高热量输出，该芯片每颗功耗达 1300 瓦。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://caifuhao.eastmoney.com/news/20260412170942961134180">一文看懂 液 冷 数 据 中 心 ：谷歌TPU...</a></li>
<li><a href="https://baike.baidu.com/item/中性货币政策/10811071">中性货币政策 - 百度百科</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/50469602">深度解读中性利率 - 知乎专栏</a></li>

</ul>
</details>

**标签**: `#AI基础设施建设`, `#通胀`, `#美联储`, `#宏观经济`

---

<a id="item-11"></a>
## [半导体巨头加码先进封装，AI 需求引爆壁垒环节](https://www.cls.cn/detail/2410063) ⭐️ 7.0/10

包括台积电、日月光、三星在内的半导体巨头正大规模扩产先进封装产能，其中日月光将资本支出提高到 85 亿美元，台积电计划 2022 至 2027 年 CoWoS 和 SoIC 产能年复合增速超过 80%。 先进封装已成为 AI 芯片供应链中最具壁垒的环节，服务器 CPU 相关封测市场预计从 2025 年 19 亿美元增至 2028 年 96 亿美元，正在重构半导体产业链价值分布。 日月光正推动 15 座新建及扩建厂区，首条具经济规模的面板级封装（FOPLP）量产线将于 2025 年底投产；中国封测企业如甬矽电子、长电科技、华天科技等宣布了数十亿元的新项目。

rss · 财联社深度 · 6月27日 07:15

**背景**: 先进封装技术如台积电的 CoWoS（晶圆上芯片封装）和 SoIC（集成芯片系统）通过垂直堆叠多个芯片来提升性能并减小面积，对 GPU 等 AI 加速器至关重要。FOPLP（扇出型面板级封装）利用更大面板降低成本，而玻璃基板凭借优异的热学和电学性能成为下一代封装的关键材料。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/cowos.htm">CoWoS® - Taiwan Semiconductor Manufacturing Company Limited</a></li>
<li><a href="https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/SoIC.htm">TSMC-SoIC® - Taiwan Semiconductor Manufacturing Company Limited</a></li>
<li><a href="https://www.lovechip.com/blog/introduction-to-advanced-packaging-technology-foplp">FOPLP: Fan-Out Panel-Level Packaging Comprehensive Guide</a></li>

</ul>
</details>

**标签**: `#advanced packaging`, `#semiconductor`, `#AI`, `#CoWoS`, `#supply chain`

---

<a id="item-12"></a>
## [AI 隐私转变：Vitalik、NVIDIA 与 Arcium](https://x.com/Crypto_Cat888/status/2070888250622017865) ⭐️ 7.0/10

一篇推文强调 Vitalik Buterin 担心云端 AI 会破坏隐私，他更偏好本地/加密 AI 以及纯密码学方案（如 Garbled Circuits）而非 TEE。同时，NVIDIA CEO 黄仁勋在 2026 年 GTC 上表示机密计算将使数据对运营商都不可见，而 Arcium 推出了 Blackthorn 加密超智能框架，可在任何 NVIDIA H100/H200/B200 GPU 上运行 AI，且输入、模型和输出全程加密。 这标志着 AI 基础设施从硬件约束向软件定义隐私的重大转变，顺应了日益增长的机密计算需求。如果成功，将实现真正私密的 AI 服务，保护用户数据免受云运营商和模型所有者的访问，影响医疗、金融和去中心化 AI 等行业。 Vitalik Buterin 明确偏好纯密码学方案（如 Garbled Circuits）用于 AI 隐私，认为 TEE 不够可信。Arcium Blackthorn 使用多方计算（MPC）加密使用中的数据，是首个在顶级 NVIDIA GPU 上实现加密推理的框架，于 6 月 26 日宣布早期访问。

rss · Crypto Cat · 6月27日 11:18

**背景**: 机密计算保护使用中的数据，通常使用基于硬件的 TEE 或密码学技术如 MPC。Garbled Circuits 是一种密码学协议，允许双方在不泄露各自私密输入的情况下计算函数，提供比 TEE 更强的安全保障。Arcium 是一个去中心化机密计算网络，旨在为 web3 和 AI 提供无需信任、可验证的计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Garbled_circuit">Garbled circuit - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Confidential_computing">Confidential computing - Wikipedia</a></li>
<li><a href="https://www.arcium.com/blackthorn">Arcium Blackthorn™ | Confidential AI inference engine</a></li>

</ul>
</details>

**标签**: `#AI`, `#privacy`, `#confidential computing`, `#Vitalik Buterin`, `#Arcium`

---

<a id="item-13"></a>
## [大秦数字能源锂价豪赌失利后冲刺港股 IPO](https://36kr.com/p/3871109381035011?f=rss) ⭐️ 6.0/10

大秦数字能源于 2025 年 6 月 26 日递交港股上市申请，该公司因在 2022-2023 年锂价高位囤积电芯导致巨额亏损，直至 2025 年才清完库存并扭亏为盈。 此案例凸显了原材料价格波动对储能公司利润的毁灭性影响，其 IPO 成功扭亏为盈也揭示了在可再生能源供应链中赌锂价周期的风险。 大秦的毛利率在 2024 年因高价电芯存货撇减超过 1.3 亿元而暴跌至-19.9%，2025 年清完旧库存后反弹至 23.2%。公司目前 95.1%收入来自境外，其中 61%来自欧洲。

rss · 36氪 · 6月27日 07:37

**背景**: 碳酸锂价格在 2023 年初高达每吨 50 万元，随后年内暴跌超 80%。大秦公司在高位采购电芯，生产了 28.4 万台户用储能电池，因欧洲需求下滑而难以出售。储能公司面临原材料成本和需求周期的双重风险。

**标签**: `#储能`, `#IPO`, `#锂价`, `#财务分析`, `#商业案例`

---

<a id="item-14"></a>
## [G7 易流发布穿戴式 AI 硬件，填补物流交付最后两米](https://36kr.com/p/3869740772316162?f=rss) ⭐️ 6.0/10

2025 年 6 月 25 日，G7 易流发布了货运行业首款穿戴式 AI 硬件“拍拍豆”，可自动采集车下物流数据。 该产品填补了车辆与交付点之间的数据断联，实现了车下作业的实时可见与可追溯，是迈向全链路数字物流的关键一步。 设备仅重 30 克，采用磁吸设计，佩戴即录、放回底座自动上传，支持语音唤醒打标签和 AI 异常预警。

rss · 36氪 · 6月27日 01:40

**背景**: 物流行业中，车上数据（位置、温度、驾驶行为等）已基本数字化，但装卸、交接、检查等车下作业仍依赖人工且缺乏记录。这个“最后两米”的盲区常引发纠纷和损失。G7 易流此前已推出车上 AI 主机“紫宝盒”。

**标签**: `#logistics`, `#AI`, `#hardware`, `#wearable`, `#supply chain`

---

<a id="item-15"></a>
## [国内首个第四代半导体全产业链项目落户郑州](https://36kr.com/newsflashes/3872140630692872?f=rss) ⭐️ 6.0/10

中科粉研（河南）超硬材料有限公司与郑州高新区签署协议，建立国内首个第四代半导体材料全产业链生产基地，依托其全球首条 LPPHT 微纳米金刚石产线技术积累。 该项目填补了河南在全球独具优势的超硬材料产业链的关键一环，为实现第四代半导体核心材料的自主研发、生产和规模量产打下基础，减少对外部技术的依赖。 该项目利用全球首条 LPPHT 微纳米金刚石产线技术，旨在实现基于金刚石的第四代半导体材料的规模量产。

rss · 36氪 · 6月28日 01:15

**背景**: 半导体材料从第一代（硅）发展到第四代（超宽禁带材料如氧化镓、金刚石）。第四代半导体在高温、高频、强辐射等极端环境下性能优异。金刚石具有超高热导率和击穿场强，非常适合下一代功率电子器件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zhuanlan.zhihu.com/p/670379022">详解什么是第一、二、三、四代半导体; - 知乎 Images 四代半导体材料演进史：从硅、砷化镓到碳化硅、氧化镓 第四代半导体深度解析：材料革命与极端场景下的技术突破 半导体材料介绍，第一代、第二代、第三代、第四代半导体材料分类 四代半导体材料演进史：从硅、砷化镓到碳化硅、氧化镓，全面解析半导...</a></li>
<li><a href="https://news.qq.com/rain/a/20260331A05APR00">世界首条LPPHT微纳米金刚石产线在郑州启动_腾讯新闻</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#materials science`, `#fourth-generation semiconductor`, `#China industry`

---

<a id="item-16"></a>
## [触屏 MacBook Pro 传闻跳过 M6 芯片，首发 M5](https://36kr.com/newsflashes/3871135669048322?f=rss) ⭐️ 6.0/10

马克·古尔曼报道称，苹果传闻中的触屏 MacBook Pro 将在 2025 年底或 2027 年初发布，搭载 M5 Pro 及 M5 Max 芯片，跳过 M6 Pro 和 M6 Max，归因于内存短缺和成本压力。未来计划升级至 M7 芯片。 这一传闻表明苹果可能为了控制生产成本而调整芯片路线图，推迟高端芯片升级。这可能会影响开发者对 MacBook Pro 性能的预期，并影响用户的购买决策。 触屏 MacBook Pro 预计在苹果近期因成本上涨上调 Mac 和 iPad 产品售价后推出。古尔曼的报道与此前泄露的苹果跳过 M6 Pro/Max 直接推出 M7 系列的信息一致。

rss · 36氪 · 6月27日 08:02

**背景**: 苹果 M 系列芯片快速迭代，每代都有显著性能提升。M5 系列预计采用更先进的制程，而 M6 据传面临良率问题或成本超支。跳过一代可让苹果专注于更高效的节点并应对供应链挑战。

**标签**: `#Apple`, `#MacBook`, `#M5 chip`, `#rumors`, `#product roadmap`

---

<a id="item-17"></a>
## [美国监管机构因 OTA 修复结束特斯拉转向调查](https://36kr.com/newsflashes/3871127099315202?f=rss) ⭐️ 6.0/10

美国国家公路交通安全管理局（NHTSA）关闭了对 2023 款特斯拉 Model 3 和 Model Y 转向失效问题的工程分析调查，此前特斯拉通过 OTA 空中升级（软件版本 2023.38.4）解决了该问题，该更新自 2023 年 10 月起陆续推送。 此次调查关闭表明 NHTSA 认为该安全缺陷已通过软件更新解决，支持了特斯拉基于 OTA 的召回方式。这也凸显了远程修复汽车安全问题的有效性，可能影响未来的监管实践。 调查涉及约 24 万辆汽车，发现转向 ECU 印刷电路板上的电机驱动组件存在过压击穿风险，导致电子助力转向失效。OTA 更新后，相关投诉明显下降，调查据此结束。

rss · 36氪 · 6月27日 07:54

**背景**: 电子助力转向（EPS）依靠 ECU 控制电机来辅助转向。ECU 电路板上的过压击穿会禁用动力辅助，迫使驾驶员手动转向。OTA（空中升级）允许汽车制造商远程修复软件相关缺陷，通常避免物理召回。NHTSA 会持续监测此类召回的效果。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://wap.cj.sina.cn/pc/7x24/4958295">美国监管部门关闭针对特斯拉Model 3及Model Y转向失控调查_7x24快讯_...</a></li>
<li><a href="https://finance.sina.com.cn/7x24/2026-06-27/doc-inievrew7225957.shtml">美国监管部门关闭针对特斯拉Model 3及Model Y转向_7x24小时财经新闻_...</a></li>

</ul>
</details>

**标签**: `#Tesla`, `#Automotive Safety`, `#OTA Update`, `#NHTSA`, `#Steering Failure`

---

<a id="item-18"></a>
## [A+H 股企业主导港股 IPO 前十](https://36kr.com/newsflashes/3871124521620485?f=rss) ⭐️ 6.0/10

2026 年上半年，24 家 A 股上市公司通过发行 H 股在港募资超 1200 亿港元，前十大 IPO 中 A+H 企业占据 8 席。 这一趋势凸显了内地企业对跨境上市日益增长的需求，利用香港国际资本市场融资并提升全球知名度。 2026 年 6 月 26 日上市的领益智造、圣邦股份和芯碁微装是上半年最后一批 A+H IPO，助力创下历史同期募资新高。

rss · 36氪 · 6月27日 07:51

**背景**: A+H 股是指同时在中国内地（如上海或深圳）发行 A 股和在香港发行 H 股的公司。H 股是内地企业在香港交易所上市的股票，允许国际投资者交易。这种双重上市结构帮助公司接触更广泛的投资者群体。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.scmp.com/business/money/markets-investing/article/1273458/toast-20-years-h-share-listings">A toast to 20 years of H - share listings | South China Morning Post</a></li>
<li><a href="https://www.energytrend.com/news/20260106-50709.html">Great Power & Chint Electric Plan H - Share Listings : Hong Kong IPO...</a></li>

</ul>
</details>

**标签**: `#A+H shares`, `#IPO`, `#Hong Kong Stock Exchange`, `#cross-border listing`, `#capital markets`

---

<a id="item-19"></a>
## [诺奖得主警告：AI 失业恐慌或成自我实现预言](https://www.cls.cn/detail/2410973) ⭐️ 6.0/10

诺贝尔经济学奖得主罗伯特·席勒发表文章警告，对 AI 导致失业的过度恐慌可能演变成自我实现的预言，并类比历史上对技术的恐惧。他批评硅谷领袖放大 AI 负面叙事的行为。 席勒的观点将 AI 失业讨论从纯技术问题重新定义为集体心理和叙事问题，这可能会影响政策和公众行为。他呼吁硅谷收敛言论，可能改变科技领袖对 AI 风险的沟通方式。 席勒引用了皮尤调查，显示仅 16%的美国人认为 AI 在未来 20 年有积极影响，40%预计负面。他指出恐惧本身会导致招聘冻结和消费者信心下降，并举例 1957-58 年的“自动化衰退”。

rss · 财联社深度 · 6月27日 18:02

**背景**: 自我实现的预言是指当人们普遍相信某种未来结果时，其行为会使该结果更可能发生。历史上对新技术夺走工作的恐惧往往先于实际替代，例如 19 世纪的卢德运动和 1950 年代的“自动化衰退”。席勒认为，由科技领袖自身警告助长的当前 AI 失业恐慌，即使 AI 并未立即取代大量工作，也可能导致经济损害。

**标签**: `#AI`, `#economics`, `#job displacement`, `#self-fulfilling prophecy`, `#Robert Shiller`

---

<a id="item-20"></a>
## [高纯度二氧化碳短缺威胁半导体生产](https://www.cls.cn/detail/2410926) ⭐️ 6.0/10

报道指出，半导体制造用高纯度二氧化碳的库存已跌破一个月的安全水平，三星电子和 SK 海力士正紧急加紧采购。 此次短缺可能影响依赖超临界 CO2 清洗的先进半导体工艺，进而波及尖端存储和逻辑芯片的生产。 三星每月使用约 1800-2000 吨高纯度二氧化碳，SK 海力士需要 600-700 吨。供应紧张源于炼油和石化厂开工率下降，且价格自年初已上涨 20%。

rss · 财联社深度 · 6月27日 12:07

**背景**: 超临界 CO2 清洗是先进半导体制造中的关键工艺，用于去除复杂电路图案上的残留物而不损伤精细结构。CO2 是炼油和石化生产的副产品，因此其供应易受原油价格和炼厂开工率波动的影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="http://dfxnyz.com/list_22/59.html">dfxnyz.com/list_22/59.html</a></li>
<li><a href="https://baike.baidu.com/item/先进制程/67873200">先进制程 - 百度百科</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#supply chain`, `#carbon dioxide`, `#manufacturing`, `#memory`

---

<a id="item-21"></a>
## [Meta 探索预测市场应用 Arena，与 Polymarket 和 Kalshi 合作](https://www.cls.cn/detail/2410835) ⭐️ 6.0/10

Meta 正在内部开发一款名为 Arena 的预测市场应用，CEO 扎克伯格敦促高管探索与 Polymarket 和 Kalshi 的合作。该应用目前处于内部测试阶段，未来可能整合到 Facebook 和 Messenger 中。 此举标志着 Meta 进军快速增长的预测市场领域，该领域在 2024 年美国总统大选期间迅速崛起。但此举面临监管审查和伦理争议，因为预测市场已被曝出内幕交易和成瘾问题。 Arena 最初将采用游戏化积分系统而非真金白银，但未来可能接受真钱投注。Meta 瞄准 18-34 岁用户，目标每月 1 亿活跃预测者。Polymarket 是加密货币平台，Kalshi 受 CFTC 监管。

rss · 财联社深度 · 6月27日 02:54

**背景**: 预测市场允许用户对选举、体育赛事或经济指标等未来事件下注。Polymarket 于 2020 年推出，使用 Polygon 区块链，曾因内幕交易和虚假信息引发争议。Kalshi 于 2021 年推出，受 CFTC 监管，主要用于体育博彩。这两个平台均因允许对敏感话题赌博以及用户盈利问题受到批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kalshi">Kalshi</a></li>

</ul>
</details>

**标签**: `#Meta`, `#prediction markets`, `#Polymarket`, `#Kalshi`, `#social media`

---

<a id="item-22"></a>
## [美国企业 AI 应用加速：RBC 调查显示从试点转向生产](https://www.cls.cn/detail/2410810) ⭐️ 6.0/10

加拿大皇家银行资本市场的一项调查发现，超过一半的美国企业已将人工智能从试点阶段推进到生产阶段，另有 35%的受访者预计将在六个月内实现生产。人工智能预算正在增加，91%的受访者正在制定全新的人工智能预算，而不是重新调整现有支出。 这项调查表明，企业人工智能的采用速度比许多投资者预期的要快，可能预示着持续的投资周期。这一趋势可能缓解对“SaaS 末日”的担忧，因为增加的人工智能支出似乎并未侵蚀其他软件预算。 在受访者中，57%表示 ChatGPT 是他们最常用的人工智能模型服务，而只有 12%青睐 Anthropic 的 Claude。近 90%的受访者认为代币预算可控，结合订阅和基于使用量的混合定价模式已成为首选购买方式。

rss · 财联社深度 · 6月27日 02:35

**背景**: 代币成本是指为处理人工智能模型输入和输出而支付的费用，通常以每百万代币衡量。混合定价模式将固定订阅费与基于使用量的可变费用相结合，为企业提供灵活性。该调查的样本偏向年度预算达数十亿美元的大型科技公司，这可能会限制其普遍适用性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aitot.net/">AITOT — The Online Totalizer for AI Costs</a></li>
<li><a href="https://www.tsia.com/blog/ai-pricing-models-usage-based-outcome-based-hybrid">AI Pricing Models: Usage-Based, Outcome-Based, and Hybrid ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Anthropic_Claude">Anthropic Claude</a></li>

</ul>
</details>

**标签**: `#AI adoption`, `#enterprise AI`, `#survey`, `#ChatGPT`, `#AI spending`

---

<a id="item-23"></a>
## [2026 年 1-5 月中国电子行业利润增长 103.9%](https://www.cls.cn/detail/2410821) ⭐️ 6.0/10

国家统计局数据显示，2026 年 1-5 月份，电子行业利润同比增长 103.9%，对全部规模以上工业企业利润增长的贡献率达 43.1%。 这一激增凸显了全球 AI 需求对中国电子制造业的深远影响，尤其是在高端计算和存储芯片领域，并强调了该行业作为工业利润增长关键驱动力的作用。 该数据覆盖年营收 2000 万元以上的工业企业。2026 年 1-5 月，工业利润整体增长 18.8%，其中电子行业单独拉动总利润增长 5.2 个百分点。

rss · 财联社深度 · 6月27日 01:46

**背景**: “规模以上工业企业”指年主营业务收入 2000 万元及以上的企业。全球 AI 需求引发高带宽内存（HBM）和先进逻辑芯片短缺，提振了中国电子供应链制造商的利润。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/01/10/micron-ai-memory-shortage-hbm-nvidia-samsung.html">AI memory is sold out, causing an unprecedented surge in prices</a></li>
<li><a href="https://www.reuters.com/world/china/ai-frenzy-is-driving-new-global-supply-chain-crisis-2025-12-03/">The AI frenzy is driving a memory chip supply crisis | Reuters</a></li>

</ul>
</details>

**标签**: `#AI`, `#electronics`, `#industry profit`, `#China economy`

---

<a id="item-24"></a>
## [拓荆科技拟收购尚积半导体，拓展 PVD 与刻蚀](https://www.cls.cn/detail/2410813) ⭐️ 6.0/10

2026 年 6 月 26 日，拓荆科技宣布拟通过发行股份及支付现金的方式收购尚积半导体控股权，旨在拓展 PVD 和干法刻蚀设备领域。此举弥补了拓荆在 PECVD 和 ALD 核心产品之外的业务缺口。 此次收购增强了拓荆在半导体设备市场的地位，增加了关键的 PVD 和干法刻蚀能力，这些对功率器件、MEMS 和先进封装至关重要。这反映了中国设备制造商通过整合提供更全面解决方案的战略趋势。 拓荆科技股票自 6 月 29 日起停牌，等待交易完成，该交易不构成重大资产重组。尚积半导体于 2025 年 12 月完成了超 3 亿元的 Pre-IPO 轮融资，投资方包括中国中车和君联资本等。

rss · 财联社深度 · 6月27日 01:27

**背景**: 拓荆科技专注于薄膜沉积设备如 PECVD 和 ALD，用于半导体制造。PVD（物理气相沉积）和干法刻蚀是互补工艺；干法刻蚀利用等离子体高精度去除材料。收购尚积使拓荆能够提供更广泛的设备组合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ema3d.com/blog/pecvd-revolutionizing-thin-film-deposition/">PECVD : Revolutionizing Thin Film Deposition - Electro Magnetic...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Atomic_layer_deposition">Atomic layer deposition</a></li>
<li><a href="https://www.horiba.com/bra/semiconductor/applications/dry-etching/dry-etching/">Semiconductor Processing: Dry Etching</a></li>

</ul>
</details>

**标签**: `#semiconductor equipment`, `#M&A`, `#China`, `#thin film deposition`, `#etching`

---

<a id="item-25"></a>
## [AI 早报：DeepSeek 开源 DSpark，OpenAI 更新](https://daily.juya.uk/issues/2026-06-28/) ⭐️ 6.0/10

DeepSeek 发布了 DSpark 推测解码框架，该框架开源并可加速 DeepSeek V4 系列模型的推理。此外，OpenAI 为 Codex 介绍了体验优化更新，阿里巴巴也上线了千问输入法的 macOS 版。 DSpark 在不需新模型的情况下大幅提升推理吞吐量（51-400%），使先进 AI 更高效、更易用。OpenAI 和阿里巴巴的更新表明 AI 辅助编程和输入工具领域的竞争持续。 DSpark 采用了半自回归生成架构和置信度调度校验机制。其开源版本包含训练与评估代码，以及附加了 DSpark 草稿模块的 DeepSeek V4 系列检查点。

rss · Juya AI Daily · 6月27日 03:27

**背景**: 推测解码是一种使用更小、更快的草稿模型生成候选 token，再由更大的目标模型验证，从而加速推理的技术。半自回归生成按块而不是逐个 token 处理，而置信度调度则根据预测确定性自适应分配验证资源。DSpark 结合了这些方法来优化服务性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/deepseek-ai/DeepSpec/blob/main/DSpark_paper.pdf">DeepSpec/DSpark_paper.pdf at main · deepseek-ai/DeepSpec</a></li>
<li><a href="https://www.explainx.ai/blog/deepseek-dspark-v4-speculative-decoding-deepspec-guide-2026">DeepSeek DSpark: V4 Speculative Decoding Guide 2026 ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#Open Source`, `#DeepSeek`, `#OpenAI`, `#News`

---

<a id="item-26"></a>
## [梅赛德斯-奔驰因利润暴跌推迟 9 万名德国员工奖金](https://36kr.com/newsflashes/3871212322706690?f=rss) ⭐️ 5.0/10

梅赛德斯-奔驰已将约 9 万名德国工会员工的‘转型奖金’从原定 2026 年 7 月推迟 9 个月至 2027 年 4 月发放，并正考虑将每周工作时间从 35 小时延长至 40 小时且不支付额外加班费。此前公司 2025 年净利润近乎腰斩，降至 53 亿欧元。 这反映了传统汽车制造商在向电动汽车转型过程中面临的严重财务压力。这些降本措施可能为德国汽车行业的劳资谈判开创先例，影响员工士气与工会关系。 被推迟的‘转型奖金’相当于月薪的 18.4%，公司保留在业务未见好转时完全取消该奖金的权利。拟议的 40 小时工作周将比标准 35 小时工作周延长且不支付加班费，这在德国劳工实践中是一项重大变化。

rss · 36氪 · 6月27日 09:20

**背景**: 梅赛德斯-奔驰与其他传统汽车制造商一样，正面临向电动汽车转型成本高昂、竞争加剧以及供应链挑战导致的利润下滑。公司报告 2025 年净利润为 53 亿欧元，低于上一年的 104 亿欧元。德国汽车行业传统上拥有强大的劳工保护，包括 35 小时工作周，工会对此极力捍卫。拟议的变化是更广泛降本措施的一部分，旨在保持竞争力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ad-hoc-news.de/boerse/news/ueberblick/mercedes-benz-delays-bonus-for-90-000-german-workers-as-profit-halves-in/69636450">Mercedes-Benz Delays Bonus for 90,000 German Workers as ...</a></li>
<li><a href="https://group.mercedes-benz.com/documents/investors/reports/annual-report/mercedes-benz/mercedes-benz-remuneration-report-2025.pdf">Remuneration Report 2025 - Mercedes-Benz Group</a></li>

</ul>
</details>

**标签**: `#automotive`, `#business`, `#labor`, `#cost-cutting`

---

<a id="item-27"></a>
## [北大哲学系主任毕业致辞引发共鸣](https://www.zhihu.com/question/2054203043105567686) ⭐️ 5.0/10

北京大学哲学系主任程乐松在毕业典礼上发表了一篇在社交媒体上迅速走红的致辞，反思了学生的困境以及哲学思考的价值。 这篇致辞与许多面临激烈竞争和存在焦虑的年轻人产生共鸣，提供了审视现代生活及其压力的哲学视角。 程乐松批评了年度毕业致辞竞赛和教师面临的压力，同时敦促毕业生在怀疑与确信之间保持平衡，避免僵化的自我确信和持续的自我否定。

rss · 知乎热榜 · 6月27日 06:02

**背景**: 在中国，顶尖大学的毕业致辞经常引起广泛关注。此次致辞因其对学生生活的坦率批判以及将哲学视为自我反思和抵制表面叙事的工具而脱颖而出。

**标签**: `#philosophy`, `#education`, `#graduation speech`, `#reflection`

---

<a id="item-28"></a>
## [欧洲热浪引发空调短缺和价格上涨](https://www.cls.cn/detail/2410964) ⭐️ 5.0/10

2025 年 6 月欧洲创纪录的热浪导致空调需求激增，造成短缺和价格上涨，尤其是美的 PortaSplit 型号，经常一上架就售罄。 这凸显了在历史上空调渗透率低的地区，气候驱动的制冷需求不断增长，为中国家电出口商带来重大机遇，并重塑全球供应链。 欧洲空调普及率仅约 20%，因为安装成本高昂（通常超过 1000 欧元）。PortaSplit 是一种便于安装的便携式分体空调，变得非常受欢迎，一些顾客驱车 200 公里寻找一台，价格上涨了 100 欧元。

rss · 财联社深度 · 6月27日 15:00

**背景**: 欧洲历史上因气候温和和严格的建筑法规，空调普及率低。然而，气候变化导致更频繁和强烈的热浪。便携式空调是传统固定安装的灵活替代品，但通常效率较低。美的 PortaSplit 采用分体式设计，能效更高（A+++级）且噪音更低，弥补了便携性与性能之间的差距。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.midea.com/global/heating-cooling/porta-split-ac">PortaSplit AC | Midea</a></li>
<li><a href="https://xueqiu.com/8118865907/396783345">||#32654;的集团 (SZ000333)$ 美的 PortaSplit空调入选《时代》全球最佳发明...</a></li>

</ul>
</details>

**标签**: `#Heatwave`, `#Air Conditioning`, `#Supply Chain`, `#Climate Change`, `#Consumer Electronics`

---

<a id="item-29"></a>
## [美线欧线运价回落，航司看好下半年需求](https://www.cls.cn/detail/2410836) ⭐️ 5.0/10

2025 年 6 月下旬，美线和欧线空运运价大幅下降，受季节性需求变化和欧盟跨境小包关税政策预期影响。尽管如此，国泰航空等航司和分析师对 2025 年下半年需求保持乐观，认为 AI、电商和高价值货物将提供支撑。 运价变化预示全球空运格局可能发生转变，欧盟政策变化可能重塑跨境电商物流。下半年展望显示市场或在高位企稳，影响货代、电商平台和运输合同谈判。 国泰航空计划 2025 年下半年将其飞往美洲的货运航班从每周约 30 班增至 35 班。航空燃油价格自 6 月初以来下跌 24.4%，国泰 7 月 1-15 日燃油附加费下降 28.8%。波罗的海航空货运指数截至 6 月 22 日仍处于历史高位 2760 点。

rss · 财联社深度 · 6月27日 02:55

**背景**: 空运价受季节性需求、燃油成本和地缘政治因素影响。包板协议是货代向航司预购物流舱位的合同安排。欧盟正考虑取消低值包裹的免税政策，可能增加跨境电商成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/abdul-wasay-husssain-qureshi-514b2b268_cargochronicles-airfreight-blockspaceagreement-activity-7385239858681892864-1sCu">Understanding Block Space Agreements in Air Cargo | LinkedIn</a></li>
<li><a href="https://www.heycross.com/article/Gy7q1P5k6RMG1">The End of Duty-Free Era in the EU ! New Tariffs to be Levied from...</a></li>

</ul>
</details>

**标签**: `#air freight`, `#logistics`, `#trade policy`, `#market analysis`

---