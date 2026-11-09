# Hi, I'm 蔡智豪 · sefanty17

软件工程本科生，做后端工程、AI Agent 与本地优先工具。

---

## 🧩 Projects

| 项目 | 简介 |
|---|---|
| [local-life-engine](https://github.com/sefanty17/local-life-engine) | 高并发本地生活交易引擎：秒杀异步化、优惠券、LBS 商铺、多级缓存与滑动窗口限流 |
| [java-go-learning-workspace](https://github.com/sefanty17/java-go-learning-workspace) | Java / Go 双栈后端工程实验室：Spring Boot 重写、go-zero 源码走读、282 道面试追问树 |
| [dsh-recall](https://github.com/sefanty17/dsh-recall) | 面向 LLM Agent 的项目记忆检索层：span / topic 双层索引与选择器注入 |
| [interview-copilot](https://github.com/sefanty17/interview-copilot) | AI 模拟面试工作台：多角色对话、剧本化流程与流式 SSE |
| [wechat-insight](https://github.com/sefanty17/wechat-insight) | 本地优先的聊天洞察引擎：年度报告、关系事件分析、消费账本 |
| [companion](https://github.com/sefanty17/companion) | 本地优先的桌面 AI 伙伴：人格化对话、语音合成、长期记忆与日程交互 |

---

## 🤝 Open Source Contributions

> 只列出已提交或已合并的 PR；上游项目版权归原作者，这里不声称作者身份。

### [LingChat](https://github.com/SlimeBoyOwO/LingChat) · 贡献者

- **玩家身份系统**：身份卡、每身份好感度、称呼覆写链、关系注入与存档绑定
  — [#896](https://github.com/SlimeBoyOwO/LingChat/pull/896) · [#904](https://github.com/SlimeBoyOwO/LingChat/pull/904)（已合并）
- **剧作 Agent 四角色分工**：任务队列、素材定位、章节自检与上下文预算
  — [#864](https://github.com/SlimeBoyOwO/LingChat/pull/864)（已合并）
- **稳定性修复**：设置页空白与老角色卡玩家身份迁移
  — [#928](https://github.com/SlimeBoyOwO/LingChat/pull/928)（已合并）
- **提示词前缀稳定化**：任务块拆为固定段与变量段
  — [#939](https://github.com/SlimeBoyOwO/LingChat/pull/939)（评审中）

### [dsh-ops](https://github.com/T-Auto/dsh-ops) · 贡献者

- **PDF 文本层读取扩展**（设计提案 [#811](https://github.com/T-Auto/dsh-ops/issues/811)，首个切片 PR [#812](https://github.com/T-Auto/dsh-ops/pull/812) 评审中）
  - xref 流、对象流与间接 `/Length` `/Size` `/Count`
  - TIFF / PNG predictor、增量 `/Prev` 链与 hybrid `/XRefStm`
  - ToUnicode CMap、Type0 Identity 与简单字体编码
  - 绘图操作符容忍、Form XObject 遍历、页窗口与 `failedPages`
- **测试体系重构**：测试从 140 个合并为 56 个矩阵化用例，抽出共享 PDF fixture 构造器，测试/实现比 1.4 → 0.6
- **完整切片栈（fork 暂存）**：[#13 集成 PR](https://github.com/sefanty17/dsh-ops/pull/13)，含 7 个功能片（xref/对象流、predictor+增量、CMap、字体、操作符/Form、页窗口）
- **真实样本验证**：WPS、Word 2021（增量）、LibreOffice、Microsoft Print to PDF、Firefox 打印等 22 份 PDF

---

## 🛠 Stack

Java · Spring Boot · Go · Rust · TypeScript · Python · Redis · Kafka · MySQL · SQLite · Vue · Tauri
