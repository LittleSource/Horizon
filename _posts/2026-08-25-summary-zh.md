---
layout: default
title: "Horizon Summary: 2026-08-25 (ZH)"
date: 2026-08-25
lang: zh
---

> 从 7 条内容中筛选出 6 条重要资讯。

---

1. [AI 早报：模型发布、合作与行业动态](#item-1) ⭐️ 7.0/10
2. [Windows on ARM 原生应用稀缺？这些改造方法值得一试](#item-2) ⭐️ 6.0/10
3. [DIY 改造：让非智能升降桌支持语音控制与多端联动](#item-3) ⭐️ 6.0/10
4. [每日科技摘要：机器人捂脸跑夺冠、小米芯片、英伟达涨价](#item-4) ⭐️ 5.0/10
5. [阿里云上线 Wan3.0 视频模型，小米发布玄戒芯片](#item-5) ⭐️ 5.0/10
6. [用快捷指令实现 iPhone 应用独立音量](#item-6) ⭐️ 5.0/10

---

<a id="item-1"></a>
## [AI 早报：模型发布、合作与行业动态](https://daily.juya.uk/issues/2026-08-25/) ⭐️ 7.0/10

2026 年 8 月 25 日的 AI 早报涵盖多项行业动态：MiniMax 与 GMI Cloud 合作免费开放 M3 模型 14 天访问；阿里云面向高校学生发放 Qoder CN 专业版；OpenAI 向美国大学生提供四个月免费 ChatGPT Plus；Agnes AI 发布 Agnes 2.5 Pro Alpha 多模态推理模型；阿里视频模型 Wan3.0 上线并限时 7 折；字节将 TRAE 与扣子整合至豆包体系；小米发布三款玄戒自研芯片并展出 AI Cube 原型机；SpaceXAI 部署 NVIDIA Vera CPU 并计划发射太空版 NVL72。 这份早报展现了 AI 竞争的激烈步伐，涵盖开放模型访问、学生优惠、新推理模型、自研芯片乃至太空 AI 计算。这些动态将改变开发者、学生和企业可获得的 AI 工具及其成本。 Agnes 2.5 Pro Alpha 是一个多模态推理模型（支持文本/图像/视频输入，文本输出），在 Sapiens AI 的 API 上定价为每百万输入 tokens 0.45 美元、每百万输出 tokens 0.90 美元。另外，阿里云 Qoder CN 系列（原通义灵码）于 2026 年 5 月 20 日正式更名；早报中诸如 Wan3.0 API 限时 7 折等子项，体现了激进的上市策略。

rss · Juya AI Daily · 8月25日 00:50

**背景**: 这是一份每日 AI 新闻摘要，汇总模型发布、合作与行业动态。关键背景：Qoder CN 是阿里云的 AI 编程助手系列，前身为通义灵码；Agnes 2.5 Pro Alpha 是一款支持多模态输入的付费推理模型，可通过 OpenAI 兼容 API 使用；NVIDIA Vera CPU 于 2026 年推出，专为代理式 AI 和强化学习负载设计，因此其在太空 AI 场景中的部署格外引人注目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://help.aliyun.com/en/lingma/introduction-of-lingma">Product introduction_ Qoder CN series_intelligent coding...</a></li>
<li><a href="https://artificialanalysis.ai/models/agnes-2-5-pro-alpha">Agnes 2 . 5 Pro Alpha - Intelligence, Performance & Price Analysis</a></li>
<li><a href="https://nvidianews.nvidia.com/news/nvidia-launches-vera-cpu-purpose-built-for-agentic-ai">NVIDIA Launches Vera CPU, Purpose-Built for Agentic AI | NVIDIA Newsroom</a></li>

</ul>
</details>

**标签**: `#AI`, `#news`, `#models`, `#industry`, `#tech`

---

<a id="item-2"></a>
## [Windows on ARM 原生应用稀缺？这些改造方法值得一试](https://sspai.com/prime/story/create-your-own-windows-apps) ⭐️ 6.0/10

这篇来自少数派（sspai.com）的实用指南介绍了多种在 Windows on ARM 上改造和运行应用的方法，以应对该平台原生软件匮乏的问题。文章讨论了 x86/x64 模拟、ARM64EC 应用程序二进制接口以及 Windows 11 兼容层 Prism 等方案。 对于 Windows on ARM 设备（尤其是最新的 Copilot+ PC）用户来说，原生应用匮乏是主要使用障碍，因此实用的替代方案直接影响日常可用性。随着基于 ARM 的 Windows 笔记本日益普及，软件兼容性仍是其能否被广泛接受的关键。 文章涵盖的技术可能包括利用系统内置的 x86/x64 模拟、借助 ARM64EC ABI 在单个应用中混用原生与模拟代码，以及使用微软的 Prism 模拟层。这些方法都以一定性能换取兼容性，具体表现因 CPU 和应用指令类型而异。

rss · 少数派 · 8月24日 08:28

**背景**: Windows on ARM 早在 2012 年就随 Windows RT 出现，但原生软件支持一直很薄弱。现代的 Windows 11 on ARM 设备通过软件模拟方式运行 x86 和 x64 应用，而 ARM64EC 允许开发者构建同时包含原生 ARM 代码与模拟 x64 代码的应用。Prism 是 Windows 11 on ARM 中最新的模拟层，旨在提高旧应用的兼容性和性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://windowsreport.com/windows-11-arm64ec-support/">Windows 11 Arm x64 Emulation: Does it Work?</a></li>
<li><a href="https://onarm.net/guides/prism-emulation-explained">What Is Prism ? Windows 11 x86 Emulation on Arm ... | OnARM.Net</a></li>
<li><a href="https://www.techrepublic.com/article/windows-on-arm-this-is-how-well-64-bit-emulation-is-working/">Windows on Arm : This is how well 64-bit emulation is... - TechRepublic</a></li>

</ul>
</details>

**标签**: `#Windows on ARM`, `#app compatibility`, `#emulation`, `#software adaptation`

---

<a id="item-3"></a>
## [DIY 改造：让非智能升降桌支持语音控制与多端联动](https://sspai.com/post/113563) ⭐️ 6.0/10

一个 DIY 项目展示了如何将非智能双电机升降桌改造为支持语音控制与多端联动的智能升降中枢。这项改造让普通办公桌获得了智能化的使用体验。 该项目展示了如何通过 AI 与物联网技术升级现有的非智能家具，无需购买昂贵的智能升降桌。它可能激励其他 DIY 爱好者改造自己的家具，符合智能家居个性化定制的大趋势。 该升降桌采用双电机升降系统，通过集成控制器实现语音指令与多端联动功能。项目可能涉及添加智能控制板等硬件改造，并利用 Wi-Fi 或蓝牙等协议进行连接。

rss · 少数派 · 8月24日 07:14

**背景**: 升降桌（也称坐立交替办公桌）让用户可以在坐姿和站姿之间切换，以改善健康和生产力。传统非智能型号需要手动调节，而智能升降桌则支持编程、语音控制并融入智能家居生态。这个 DIY 项目通过将 AI 能力赋予现有硬件，填补了二者之间的空白。

**标签**: `#智能家居`, `#DIY`, `#硬件改造`, `#语音控制`, `#AI`

---

<a id="item-4"></a>
## [每日科技摘要：机器人捂脸跑夺冠、小米芯片、英伟达涨价](https://blog.csdn.net/weixin_39786569/article/details/164021167) ⭐️ 5.0/10

这份科技新闻摘要报道，天工团队称其机器人在比赛中捂脸并夺冠的动作是它自己想出来的；小米今天公布了玄戒芯片的最新进展；英伟达已通知客户，AI 相关产品涨价超过 15%。 这些新闻反映了重要趋势：人形机器人的自主行为、中国在先进 3nm 芯片设计上的进展，以及英伟达在 AI 硬件市场的定价权。它们将影响机器人研究者、智能手机芯片竞争者和 AI 基础设施采购方。 天工是由北京人形机器人创新中心开发的 1.63 米高、43 公斤重的全电驱人形机器人，能以 6 公里/小时稳定奔跑。小米的玄戒 O1 据称是 3nm 手机 SoC，标志着中国大陆在该先进制程芯片设计上取得首个突破。

rss · CSDN 极客头条 · 8月24日 05:48

**背景**: 天工是一个通用人形机器人平台，中国计划将其广泛开放，部分以开源方式提供，以加速人形机器人研发。小米的芯片布局始于 2014 年前后，最初成立松果电子；经过约十年、超过 100 亿美元投入，最终推出玄戒 O1 3nm 芯片，使小米成为高通在旗舰手机处理器领域的有力挑战者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://newatlas.com/robotics/china-tiangong-general-purpose-humanoid/">China's home-grown general-purpose humanoid jogs out at 6 km/h</a></li>
<li><a href="https://interestingengineering.com/innovation/china-tiangong-electric-humanoid-robot">World's first fully electric robot boasts 550 trillion ops, 4mph speed</a></li>
<li><a href="https://www.ctol.digital/news/xiaomi-launches-first-flagship-smartphone-chip-10-billion-investment-challenge-qualcomm-dominance/">Xiaomi Launches First Flagship Smartphone Chip After $10 Billion...</a></li>

</ul>
</details>

**标签**: `#tech news`, `#AI`, `#hardware`, `#Nvidia`, `#Xiaomi`

---

<a id="item-5"></a>
## [阿里云上线 Wan3.0 视频模型，小米发布玄戒芯片](https://sspai.com/post/113813) ⭐️ 5.0/10

阿里云正式上线视频生成模型万相 3.0（Wan3.0），单次可生成 30 秒视频，并支持文档输入。小米发布了三款自研玄戒芯片，包括 AI 加速芯片 O100 和智驾芯片 D100 等。 这些发布显示中国科技巨头正加速在 AI 和自研芯片领域布局。Wan3.0 以文档输入和长视频生成能力推动视频生成模型发展，而小米的芯片同时瞄准大模型加速与智能驾驶，可能改变 AI 基础设施和汽车行业的竞争格局。 Wan3.0 支持单次生成 30 秒视频并可无缝延长，首次支持 doc、xls、ppt、pdf、md 等文档格式直接输入。小米玄戒 O100 采用 3D 堆叠工艺，实现 1.22TB/s 带宽，为 6nm AI 加速芯片；玄戒 D100 则号称国内首款 3nm 智驾芯片，支持 160GB 统一内存和 200B 参数模型，计划明年商用。

rss · 少数派 · 8月25日 00:28

**背景**: 视频生成模型利用 AI 通过文本、图像或其他输入生成逼真的视频，Wan3.0 是阿里万相模型系列的最新版本。小米多年来通过玄戒子公司自研芯片，公开资料显示累计研发投入超过 135 亿元，团队规模达 2500 人。小米此前在 2024 年底已流片 3nm 工艺芯片，如今进一步扩展产品线，覆盖 AI 加速与汽车智能两大方向。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aihot.virxact.com/story/a99af99d-0dff-4752-a453-37de2d1a0c65">Alibaba Cloud releases Wan 3 . 0 · AI HOT</a></li>
<li><a href="https://www.sina.cn/news/detail/5335460617651834.html">#小米玄戒#【小米官宣国内首款3nm智驾芯片“玄戒D100”，明年商用】8月24日下午，在小米玄戒芯片技术沟通会上，据现场工作人员透露，小米自研芯片玄戒D100，定位国内首款3nm智驾高算力AI芯片，目前已研发完成，明年将正式投入商用。在内存和模型支持方面，玄</a></li>
<li><a href="https://baike.baidu.com/item/小米玄戒芯片/65694155">小米玄戒芯片_百度百科</a></li>

</ul>
</details>

**标签**: `#AI`, `#video generation`, `#chips`, `#tech news`

---

<a id="item-6"></a>
## [用快捷指令实现 iPhone 应用独立音量](https://sspai.com/post/112983) ⭐️ 5.0/10

这篇文章介绍了一种基于 iOS 快捷指令的变通方案：在打开特定 app 时自动记住并设置对应的音量，弥补 iOS 没有原生应用独立音量控制的不足。 这件事的意义在于，许多用户会对不同 app 的音量差异感到困扰，而这个教程把快捷指令变成了无需等待苹果推出系统级功能的实用低成本方案。它也展示了自动化可以用来解决 iOS 日常使用中的限制。 这种变通方案依赖“打开 app”时触发的快捷指令自动化，通过“设定音量”操作来应用已记住的音量；它并不能实现真正的多音源并发混音或系统级的独立音量滑块。用户需要在快捷指令中为每个 app 手动定义并调整想要的音量。

rss · 少数派 · 8月24日 03:30

**背景**: 快捷指令(Shortcuts)是苹果为 iPhone 和 iPad 提供的官方自动化应用，允许用户把不同 app 和系统功能中的操作串联起来，构建自定义工作流。个人自动化可以在“打开某个 app”等触发条件发生时运行，因此这个音量方案才得以实现。iOS 至今没有原生的应用独立音量设置，所以用户一直在寻找创造性的变通办法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Shortcuts_iOS">Shortcuts (iOS)</a></li>
<li><a href="https://www.macobserver.com/tips/round-ups/best-ios-shortcuts/">10 Best iOS Shortcuts You Didn’t Know You... - The Mac Observer</a></li>

</ul>
</details>

**标签**: `#iOS`, `#Shortcuts`, `#iPhone`, `#Automation`

---