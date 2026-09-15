---
title: Content format / 内容格式
type: principle
status: working
languages: [zh-CN, en]
updated: 2026-09-15
---

# 内容格式｜Content format

本文件是面向人和 AI 的最小内容协议，用来降低歧义和版本漂移。

This is the minimum content convention for humans and AI systems. It reduces ambiguity and version drift.

## 推荐 front matter｜Recommended front matter

```yaml
title: "中文标题 / English title"
type: question | dialogue | essay | argument | counterargument | evidence | principle | history
status: open | working | provisional | revised | archived
languages: [zh-CN, en]
updated: YYYY-MM-DD
```

## 正文顺序｜Body order

1. **状态与范围 / Status and scope**：说明这是问题、假设、论证还是记录。
2. **内容 / Content**：先中文，再英文；两者含义保持一致。
3. **证据 / Evidence**：列出来源、来源能支持什么，以及不能支持什么。
4. **反方意见 / Counterarguments**：用尽可能强的形式表达不同看法。
5. **修订条件 / Revision conditions**：说明什么新证据会改变本文。

1. **Status and scope**: identify whether the entry is a question, hypothesis, argument, or record.
2. **Content**: Chinese first, then English, with equivalent meaning.
3. **Evidence**: state sources, what they support, and what they do not support.
4. **Counterarguments**: express disagreement in its strongest reasonable form.
5. **Revision conditions**: state what new evidence would change the entry.

## 术语标签｜Epistemic labels

- `Fact / 事实`：可由来源核验的陈述。
- `Inference / 推论`：从事实推导出的解释，不等于事实本身。
- `Value judgment / 价值判断`：关于应然、好坏或优先级的判断。
- `Working hypothesis / 工作假设`：暂时用于思考、允许被推翻的主张。

- `Fact`: a claim that can be checked against a source.
- `Inference`: an interpretation derived from facts, not a fact itself.
- `Value judgment`: a judgment about what ought to be, what is good, or what should have priority.
- `Working hypothesis`: a temporary claim used for inquiry and open to refutation.
