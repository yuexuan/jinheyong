---
title: 我的交易与量化路线时间线：从 AI Trader 到 Human Thesis
date: 2026-09-24 15:30:00
categories:
  - 投资笔记
tags:
  - 交易学习
  - Alpha
  - Wyckoff
  - Price Action
  - Order Flow
  - AI Trader
  - Human Thesis
---

> 这是一篇长期更新的路线记录。以后交易认知或量化体系发生重要变化时，我会继续按时间往下追加，而不是重新写一篇新的总结。

2026 年到现在，我对交易这件事的理解发生了好几次变化。

如果回头看，最大的变化并不是我又学会了多少指标、多少模型，而是我逐渐弄清楚了一个问题：

**人在交易里到底应该做什么，机器又应该做什么。**

到今天，我基本确定了未来会长期并行的两条路线：

**第一条，是我自己成为一个真正懂市场、能够独立交易的人。**

**第二条，是继续迭代 Alpha → Strategy → Portfolio / Risk Management 这套量化体系。**

这两条路线不再互相竞争。

相反，它们正在开始汇合。

---

## 2026 年 4 月：从 Wyckoff 开始系统学习市场

今年比较早的时候，我开始系统学习 Wyckoff。

当时我的注意力主要还是放在模型本身：

Accumulation、Distribution、Phase A/B/C/D/E、Spring、UTAD、SOS、SOW……

我的想法很简单：

如果市场存在一些反复出现的结构，那么是不是把这些结构理解透，就能够提高交易胜率？

所以那一阶段，我还比较关注：

**“现在到底处于哪个 Phase？”**

**“这里是不是 Spring？”**

**“这里是不是吸筹？”**

今天再回头看，这是一个很正常的学习阶段。

刚开始学习交易，人总希望市场能够被一套完整模型解释。

---

## 2026 年 7 月：开始接受交易是一项长期职业能力

到了 7 月，我开始意识到，交易和我过去做软件、做产品完全不是一个节奏。

软件开发很多时候可以依靠工程能力快速推进。

但交易不是。

它需要大量市场暴露、经验、复盘以及真实风险环境中的训练。

也是在这个阶段，我开始真正接受：

**交易不是学几个月技术分析就能毕业的事情。**

与此同时，Alpha Research 这条路线也越来越清晰。

我把 Alpha 挖掘形容成“挖金矿”。

只不过这个矿非常难挖。

数据、因子、回测、验证、过拟合、Regime、执行成本、策略衰减……

每一个问题都需要长期建设。

这时第一次出现了明显矛盾：

> 量化的长期价值很高，但 Time-to-Alpha 太长。

它可能是几年尺度的事情。

而我又希望能够尽早具备真正理解市场、甚至通过交易获得一定收入的能力。

这埋下了后来“双路线”的伏笔。

---

## 2026 年 8 月：第一次认真尝试构建 AI Trader

8 月份，我一度把大量注意力放到了 AI Trader 上。

当时的想法其实非常自然：

既然 AI 已经能够理解文字、图片、市场理论，为什么不能把 Wyckoff、Price Action、Order Flow、趋势跟踪这些理论全部交给 AI？

于是最早的方向是：

> Machine 提供市场数据，AI 理解市场，然后 AI 自己产生交易决策。

后来这个架构逐渐演化成：

**Market Context → Trading Skills → Thesis → Opportunity → Trigger → Risk → Execution**

我甚至开始把 Wyckoff、Price Action、Order Flow 等做成独立 Trading Skills。

当时我认为：

AI 负责认知和判断；

确定性程序负责数据、风控、执行和审计。

特别是风险层，我很早就确定了一条原则：

> **AI 可以犯判断错误，但不能拥有犯风险错误的权限。**

这条原则今天仍然成立。

但后来的问题出现在更上游。

---

## 2026 年 8 月底：机器研究与人工交易开始分离

随着系统越来越复杂，我开始发现：

AI Trader 和 Alpha Research 并不是同一件事情。

Alpha Research 的优势非常明确。

机器特别擅长：

- 搜索大量数据；
- 构造特征；
- 做历史验证；
- 进行分组；
- 比较不同 Regime；
- 做样本外检验；
- 检查稳定性；
- 7×24 小时重复实验。

于是 AegisTrade / AHotFlow 的重心逐渐开始向 Research Factory 靠拢。

这个时候我已经开始形成一个新的分工：

> **Research 可以 7×24 小时运行，但真正的交易暂时由人完成。**

这是一个很重要的变化。

此前我的想法是：

**最终让机器学会交易。**

这时候开始变成：

**机器负责研究，人负责判断和执行。**

但当时我还没有完全理解，为什么这会更加合理。

---

## 2026 年 9 月初：Alpha 系统越来越成熟，但周期也越来越长

进入 9 月后，Alpha Research 的路线进一步展开。

Factor Research、Validation、Dry-run、Strategy、Portfolio……

我越来越能看清楚完整的量化体系：

> **Data → Feature → Alpha → Strategy → Portfolio → Risk → Execution**

同时也越来越清楚它为什么慢。

真正可信的 Alpha 不是写一个公式、跑一次回测就结束。

它必须经过大量证伪。

很多实验最后得到的结论甚至只是：

**NO INCREMENTAL EDGE。**

但这并不是失败。

能够可信地证明一个 hypothesis 没有价值，本身就是 Research Factory 的价值。

问题也因此更加现实：

**Alpha 很强，但远水解不了近渴。**

如果整个 Research Factory 真正成熟需要几年，那么我不能把自己所有的市场学习都押在“等机器发现 Alpha”上。

---

## 2026 年 9 月 10 日：双路线第一次真正成型

这个阶段是一个非常明显的转折。

我重新开始认真学习 Order Flow。

原因很直接。

相比完整 Alpha Factory，Order Flow 更接近真实交易现场。

它迫使我理解：

谁在主动成交？

谁在吸收？

价格为什么没有继续移动？

Liquidity 在哪里？

Aggressive buyers / sellers 到底有没有取得结果？

于是路线第一次变得非常清楚。

### 路线一：人工交易能力

重点学习：

**Price Action + Market Structure + Wyckoff Context + Order Flow**

目标不是让 AI 替我交易。

而是我自己能够真正看懂市场。

### 路线二：机器研究能力

继续建设：

**Alpha → Strategy → Portfolio / Risk**

让机器负责搜索、验证、回测、淘汰和长期运行。

也是在这个阶段，我发现了一个非常重要的接口：

**Human Thesis。**

我不需要把自己的完整盘感编码成程序。

我只需要观察到：

> “某一种市场现象似乎反复有效。”

然后把这个观察提交给 Research Factory。

机器再去验证：

它到底是不是 Alpha？

这一下，人和机器第一次真正连接起来了。

---

## 2026 年 9 月 11 日：重新理解 Wyckoff

随后我又经历了一次对 Wyckoff 的否定。

因为越学越感觉：

很多 Accumulation / Distribution 的解释，很容易变成事后讲故事。

图走完了以后，怎么看都像 Wyckoff。

于是我开始认为：

也许 Wyckoff 没有那么重要。

趋势、结构本身 Price Action 就能看到。

成交量变化又可以由 Order Flow 更细致地分析。

所以当时我把交易学习路线压缩成：

> **Trend / Structure → Price Action → Order Flow**

Wyckoff 被降级成一个模式词典。

但继续学习之后，我现在又把它重新捡了回来。

只是用途完全不同。

我已经不再执着：

> “这里到底是不是 Phase C？”

现在更重要的问题变成：

> 当前 Regime 是什么？

> Market Context 是什么？

> 价格来到什么 Location？

> 是否发生了 C-like event？

> 原来的 Auction 是否失败？

> 有没有 Confirmation？

这时候 Wyckoff 不再是预测工具。

而变成了一套非常好用的 **Context Framework**。

特别是 Phase C 附近那些 Spring、UTAD、Test、SOS/SOW，本质上是在寻找：

**一个旧方向尝试失败，新方向开始得到确认的时间窗口。**

这和 Price Action 并不冲突。

---

## 2026 年 9 月 24 日：终于理解左侧与右侧交易

今天又解决了一个我以前一直模糊的问题。

左侧和右侧交易的本质，并不是：

**抄底 vs 追涨。**

真正的区别是：

> **在市场完成证明之前下注，还是等待市场完成部分证明以后再下注。**

左侧交易获取的是：

**Price Advantage。**

右侧交易获取的是：

**Information Advantage。**

我很快意识到：

自己的风格明显更加偏向右侧交易。

我不喜欢连续不断地试错止损。

相比用很多小止损去赌一次大行情，我更愿意：

**等待、观察、过滤，然后做更有把握的事情。**

代价是入场价格会差一点，潜在 R:R 也可能稍微下降。

但这符合我的决策方式。

于是又形成了一个新的执行规则：

**Confirmation Budget。**

不是无限等确认。

而是：

> 一个强确认可以交易；

> 两个中等的独立确认可以组合；

> 最多三个确认。

第三个确认出现以后：

**要么 Execute，要么 Pass。**

禁止继续寻找第四个、第五个证据。

因为右侧交易最大的危险，不一定是止损。

而是：

**Analysis Paralysis。**

等着等着，行情已经结束了。

---

## 2026 年 9 月 24 日：真正困难的是动态权重

今天还有一个更重要的发现。

为什么交易这么难？

因为盘面上永远存在大量参数。

Trend、Structure、Volume、Delta、CVD、VWAP、Liquidity、Sweep、Absorption、Volatility、Session、HTF Level……

真正优秀的交易者，不可能每一次都机械计算上百个参数。

长期训练之后，大脑实际上完成的是 **Information Compression**：

> Regime  
> Location  
> Pressure  
> Response  
> Confirmation

几十甚至上百个变量，被压缩成几个高阶状态。

然后最困难的一步出现了：

**Dynamic Weighting。**

同一个 Delta Divergence：

发生在随机位置，可能几乎没有意义。

但如果它发生在：

HTF Range Low  
+ Liquidity Sweep  
+ Price Refuses Lower

它的权重可能突然非常高。

所以交易真正难的并不是：

> “认不认识这个信号？”

而是：

> **“现在这个信号到底值多少钱？”**

这就是所谓盘感里面非常重要的一部分。

---

## 2026 年 9 月 24 日：这也解释了为什么 AI Trader 很难推进

这个认知终于解释了此前 AI Trader 为什么一直难以真正推进。

AI 并不是不知道交易知识。

相反，它知道很多。

它知道什么是 Spring。

知道什么是 BOS。

知道什么是 Delta Divergence。

知道什么是 Absorption。

它的问题是：

> **在某一个具体时间横截面，无法稳定地把所有参数重新动态加权。**

它拥有大量 **Static Knowledge**。

但真实交易要求的是：

> **State Estimation → Feature Selection → Dynamic Weighting → Hypothesis Ranking → Risk Decision**

这完全是另一种能力。

市场状态发生变化以后：

`f(t) ≠ f(t+1)`

昨天重要的信号，今天可能只是噪音。

同一个 BOS，在趋势行情和 Range Low Sweep 后，意义完全不同。

于是我终于接受：

现阶段没有必要强行让 AI 成为一个完整的自主 Trader。

更合理的结构是：

> **Human Thesis → Machine Validation → Alpha**

---

# 目前收敛出的两条长期路线

所以到 2026 年 9 月 24 日，我的交易路线已经非常清楚。

## 路线一：训练我自己

目标是成为一个真正理解市场的人。

核心：

**Wyckoff Context + Price Action + Order Flow**

训练的重点不是记住更多 Pattern。

而是：

- 判断 Regime；
- 判断 Location；
- 理解 Liquidity；
- 观察 Effort vs Result；
- 判断 Failed Auction；
- 给不同 Evidence 动态分配权重；
- 找到 Minimum Sufficient Confirmation；
- 到了该出手的时候真正执行。

最终形成属于自己的 discretionary framework。

这件事情我已经不准备赶时间。

**三年不行，就练十年。**

---

## 路线二：继续建设机器

机器这条线继续按照：

> **Alpha → Strategy → Portfolio → Risk Management**

长期迭代。

Alpha 负责寻找 Edge。

Strategy 负责把 Edge 转换成可执行规则。

Portfolio / Risk Management 负责决定：

**什么值得下注，下注多少，以及同时承担多少风险。**

之后再连接 Execution、Cost、Capacity、Decay Monitoring。

我不再要求这条路线快速给出答案。

Research Factory 的意义本来就是：

**持续发现、持续验证、持续淘汰。**

---

# 两条路线最终会汇合

现在我终于不再纠结：

到底应该学主观交易，还是做量化？

因为它们解决的是两个不同的问题。

人负责：

> **观察市场，理解市场，提出真正有价值的问题。**

机器负责：

> **把这些问题放到历史数据和真实市场中反复证伪。**

未来有一天，我可能观察到：

> 某种 Liquidity Sweep + Failed Auction + Absorption，在特定 Volatility Regime 和 Session Structure 下特别有效。

过去，这可能只是“盘感”。

现在我可以把它写成 Human Thesis。

然后交给 Research Factory：

做历史搜索。

做 Feature Extraction。

做 Regime 分组。

做 Robustness。

做 OOS。

做 Dry-run。

最后决定：

它究竟只是我的错觉，

还是一个真正存在的 Alpha。

所以最终我想成为的，也许既不是传统意义上的主观交易员，也不是传统意义上的 Quant。

更像是：

> **Human Market Researcher + Machine Research Infrastructure**

我负责发现问题。

机器负责证明或者杀死它。

机器挖出的异常，又反过来帮助我重新理解市场。

这可能才是 AI 时代真正适合我的交易路线。

至少到今天，这是今年走了很多弯路以后，得到的最清楚的一次答案。

**学交易这件事情，本身非常有意义。**

而 Alpha Factory 也没有白做。

**一条路线在训练我。**

**另一条路线在放大我。**

剩下的，大概就只需要时间了。
