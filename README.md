# Academic Rebuttal

一个用于学术作者回复的通用 skill：分析审稿疑虑、选择证据和实验、起草回复，并在会议允许的讨论窗口内主动推进关键问题。

入口为 [`SKILL.md`](SKILL.md)，调用名称为 `academic-rebuttal`。

## 使用方式

将本仓库放到支持 `SKILL.md` 的助手的 skills 目录中，并将文件夹命名为 `academic-rebuttal`。例如，在 Codex 环境中，可以克隆到实际配置的 `$CODEX_HOME/skills/academic-rebuttal`；不要覆盖已有版本而不先检查本地修改。

示例请求：

```text
使用 academic-rebuttal 分析以下 reviews。
会议/年份/赛道与讨论阶段：……
规则与截止时间：……
论文主张及已有证据：……
审稿意见：……
先指出决定性问题，安排必要验证，再起草有证据支持的回复。
```

也可以只要求润色一句话、判断一个实验是否必要，或起草一次讨论期跟进；无需每次启动完整工作流。

## 核心判断

- 把技术核查优先级与沟通篇幅分开：低置信或少数意见也可能指出致命问题。
- 检查回答是否对应 reviewer 的具体对象、阶段和证据要求，避免答到相邻问题。
- 按科学必要性、可行性和报告许可选择实验，不按结果是否可能有利选择验证。
- 发现重大故障后检查共享流程的影响范围，优先审计已有记录，再决定重跑范围。
- 新证据改变核心结论时，同步更新主张、摘要、主表和对接收的论证。
- 在规则允许的双向讨论期，可以做一次针对关键问题的礼貌跟进；必要时请 chair 协助讨论。反复催改分与一次合理跟进不同。
- 不从 reviewer 类型、历史涨分率或沉默推断当前稿件的录用概率。

## 讨论节奏不是硬编码政策

七天开放讨论中，第 3 天跟进、必要时第 5 天请 chair 协助，是一个可调整的计划示例。应从 reviewer 能看到回复且双向讨论开放时计时；实际回复限额、周期通知和渠道权限优先。Skill 只帮助分析和起草，不自动发送消息、提交回复或创建定时任务。

## 文件

- [`references/decisions-and-evidence.md`](references/decisions-and-evidence.md)：实验取舍、问题对齐、审计范围、主张变化。
- [`references/writing-and-discussion.md`](references/writing-and-discussion.md)：回复表达、chair 沟通、主动跟进与事后复盘。
- [`references/venue-mechanisms.md`](references/venue-mechanisms.md)：运行时规则适配及带日期的历史例子。
- [`references/source-notes.md`](references/source-notes.md)：公开来源、取舍与证据限制。
- [`tests/scenarios.md`](tests/scenarios.md)：完全虚构的回归情境与检查标准。

## 验证与边界

这是策略辅助工具，不保证接收，也不代替作者核对数据和最终学术判断。机制例子必须针对实际年份、赛道和阶段重新核实。

本次发布不含任何真实投稿案例的名称、作者身份、reviewer 标识、实验结果、评审原文或本地路径。公开来源论文和文章保留必要归属。
