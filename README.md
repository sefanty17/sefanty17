# Hi, I'm  · sefanty17

软件工程本科生 · 后端工程 / AI Agent / 本地优先工具

---

## 🤝 Open Source Contributions

> Contributor, not maintainer. 只列真实提交/合并的 PR。

### [LingChat](https://github.com/SlimeBoyOwO/LingChat) · 2.4k stars · 145 forks

**是什么**：沉浸式 AI Galgame 聊天桌面应用 —— 情绪立绘、桌宠、日程、互动剧情，Rust 桌面端。

**我做了什么**（4 个已合并 + 1 个评审中）：

- **玩家身份系统**：身份卡、每身份独立好感度、称呼覆写、关系注入、存档迁移
  → [#896](https://github.com/SlimeBoyOwO/LingChat/pull/896) · [#904](https://github.com/SlimeBoyOwO/LingChat/pull/904)（已合并）
- **剧作 Agent**：拆成四个角色并行分工，任务队列 + 素材定位 + 章节自检
  → [#864](https://github.com/SlimeBoyOwO/LingChat/pull/864)（已合并）
- **稳定性修复**：设置页空白、老角色卡身份迁移失败
  → [#928](https://github.com/SlimeBoyOwO/LingChat/pull/928)（已合并）
- **提示词前缀稳定化**：任务块拆固定段 / 变量段，提升缓存命中
  → [#939](https://github.com/SlimeBoyOwO/LingChat/pull/939)（评审中）

### [dsh-ops](https://github.com/T-Auto/dsh-ops) · 5.6k stars · 196 forks

**是什么**：DSH 底层操作插件工具箱 —— 降低 Token 消耗、缩短任务耗时，含 Rust 原生 worker。

**我做了什么**：

- **PDF 文本层读取扩展**（设计提案 [#811](https://github.com/T-Auto/dsh-ops/issues/811)，首个切片 [#812](https://github.com/T-Auto/dsh-ops/pull/812) ，完整 7 片栈在 [fork #13](https://github.com/sefanty17/dsh-ops/pull/13)）
  - 支持 xref 流 / 对象流 / 增量 `/Prev` / hybrid `/XRefStm`
  - TIFF、PNG predictor 与间接 `/Length` `/Size` `/Count`
  - ToUnicode CMap、Type0 Identity、嵌入字体与 WinAnsi/Standard
  - 绘图操作符容忍、Form XObject 遍历、页窗口与 `failedPages`
- **规模**：3,208 行实现，跨 7 个可独立评审的切片
- **测试体系重构**：140 → 56 个矩阵化用例，抽出共享 PDF fixture 构造器，测试/实现比 1.4 → 0.6
- **真实样本**：22 份 PDF（WPS / Word 2021 增量 / LibreOffice / Microsoft Print to PDF / Firefox），20 份完整读出

---

## 🧩 My Projects

| 项目 | 一句话 |
|---|---|
| [local-life-engine](https://github.com/sefanty17/local-life-engine) | 高并发本地生活交易引擎：秒杀异步化、优惠券、LBS 商铺、多级缓存与限流 |
| [java-go-learning-workspace](https://github.com/sefanty17/java-go-learning-workspace) | Java / Go 双栈后端实验室：Spring Boot 重写 + go-zero 源码走读 + 282 道面试追问树 |
| [dsh-recall](https://github.com/sefanty17/dsh-recall) | 给 LLM Agent 的项目记忆检索层：span/topic 双层索引与选择器注入 |
| [interview-copilot](https://github.com/sefanty17/interview-copilot) | AI 模拟面试工作台：多角色对话、剧本化流程、流式 SSE |
| [wechat-insight](https://github.com/sefanty17/wechat-insight) | 本地优先的聊天洞察引擎：年度报告、关系事件分析、消费账本 |
| [companion](https://github.com/sefanty17/companion) | 桌面 AI 伙伴：人格化对话、语音合成、长期记忆、日程主动交互 |

---

## 🛠 Stack

Java · Spring Boot · Go · Rust · TypeScript · Python · Redis · Kafka · MySQL · SQLite · Vue · Tauri
