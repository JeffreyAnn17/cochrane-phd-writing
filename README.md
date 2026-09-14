# Cochrane PhD Writing Skill

## 中文

这是一个面向博士生论文与学术报告的 Codex skill，依据 John H. Cochrane 的 *Writing Tips for Ph.D. Students* 整理，并结合实际论文编辑工作改写为可执行流程。

它帮助你：

- 提炼唯一、具体、可检验的核心贡献；
- 用倒三角结构让主要结果先行，支持读者跳读；
- 重写摘要、引言、文献综述、主体、结论和附录；
- 审查实证识别、因果方向、控制变量、工具变量和经济量级；
- 改进句子、主动语态、脚注、表格、图形和可复现性；
- 设计更紧凑的研讨会报告和问答流程。

### 使用方式

在 Codex 中使用 `$cochrane-phd-writing`，例如：

> 使用 `$cochrane-phd-writing` 审阅我的论文引言，提炼核心贡献，并给出按优先级排列的修改稿。

详细工作流见 [SKILL.md](SKILL.md)，模板和核对表见 [references/checklists-and-templates.md](references/checklists-and-templates.md)。

### 文件结构

```text
cochrane-phd-writing/
├── SKILL.md
├── agents/openai.yaml
└── references/checklists-and-templates.md
```

## English

This Codex skill helps PhD students write and revise research papers and seminar presentations. It is based on John H. Cochrane's *Writing Tips for Ph.D. Students*, translated into an actionable workflow for real editing tasks.

It helps you:

- distill one concrete, testable central contribution;
- use a triangular or newspaper structure that puts the main result first;
- revise the abstract, introduction, literature review, body, conclusion, and appendices;
- audit empirical identification, causal direction, controls, instruments, and economic magnitude;
- improve sentence clarity, active voice, footnotes, tables, figures, and reproducibility;
- design concise seminar presentations and better Q&A practice.

### Usage

Invoke `$cochrane-phd-writing` in Codex. For example:

> Use `$cochrane-phd-writing` to review my introduction, identify the central contribution, and propose prioritized revisions.

See [SKILL.md](SKILL.md) for the workflow and [references/checklists-and-templates.md](references/checklists-and-templates.md) for checklists and reusable templates.

### Structure

```text
cochrane-phd-writing/
├── SKILL.md
├── agents/openai.yaml
└── references/checklists-and-templates.md
```

## Source and scope

The attached source document is used as the intellectual basis for this skill. The skill treats its advice as adaptable principles rather than universal journal rules; explicit requirements from a target journal, discipline, supervisor, or author take precedence.
