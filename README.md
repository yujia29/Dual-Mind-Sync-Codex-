# Universal Dual-Mind Synthesis Engine

This repository contains a reusable project library for generating and running a universal dual-persona cognitive synthesis system.

It is designed to transform two independent personas, source corpora, character descriptions, or existing single-persona Skill files into a structured dual-mind engine.

The system does not perform shallow roleplay. It extracts the tension, resonance, disagreement, blind spots, and complementary force between `[Persona_A]` and `[Persona_B]`.

## 1. What This Repository Produces

This project can support two kinds of output:

1. A concrete dual-persona Skill compiled from `[Persona_A]` and `[Persona_B]`.
2. Runtime answers in one of three modes:
   - `/salon`: exploratory salon dialogue
   - `/debate`: deep confrontation and unresolved tension
   - `/synthetic`: one integrated advisor voice

## 2. File Map

```text
dual-mind-synthesis-engine/
├── SKILL.md
├── README.md
├── METHODOLOGY.md
└── TEMPLATE.md
```

### `SKILL.md`

The runtime engine. It defines activation rules, variables, silent protocol, the tension control matrix, linguistic routing, and the three interaction modes.

Use it when the system needs to operate.

### `README.md`

The user-facing guide. It explains how to prepare source material, define the objective, choose a temporal anchor, and start the system.

Use it when onboarding a user or preparing inputs.

### `METHODOLOGY.md`

The six-track synthesis method. It defines the underlying intellectual extraction pipeline used to turn two independent personas into one dynamic tension field.

Use it when compiling a high-quality dual-persona Skill.

### `TEMPLATE.md`

The standard compilation skeleton for downstream concrete dual-persona Skills.

Use it when generating a new `Dual_Mind_SKILL.md`.

## 3. Core Variables

All files use these generic variables:

- `[Persona_A]`: the first persona
- `[Persona_B]`: the second persona
- `[Temporal_Anchor]`: the time-context alignment
- `[Ultimate_Objective]`: the user's desired intervention target
- `[Source_Materials_A]`: materials for `[Persona_A]`
- `[Source_Materials_B]`: materials for `[Persona_B]`

Do not hard-code concrete names into the generic repository.

## 4. When To Use This System

Use this system when you want to:

- fuse two thinking styles
- create a dual-persona Skill
- compare two intellectual figures
- simulate a deep dialogue
- generate a structured debate
- produce one integrated advisor voice
- turn existing single-persona Skills into a dual-mind system
- preserve disagreement rather than flattening it

Do not use this system when:

- only a single-persona perspective is needed
- the task is pure factual retrieval
- the user wants a simple biography
- the user wants imitation of voice without cognitive synthesis
- source material is unavailable and the user requires high fidelity

## 5. Preparing Fuel

The quality of the output depends on the quality of the source materials.

Recommended materials for each persona:

1. Existing single-persona Skill files
2. Primary writings, speeches, interviews, public conversations, or works
3. Representative decisions or actions
4. Public criticism or external evaluation
5. Biographical summaries
6. User-provided interpretive notes

The best fuel contains both what a persona says and how the persona behaves under pressure.

## 6. Minimum Input Shape

Use this cold-start form:

```text
1. 人物A：[姓名 / 基础背景 / 语料或单人Skill文本]
2. 人物B：[姓名 / 基础背景 / 语料或单人Skill文本]
3. 终极智识目标/干预指令（选填）：[Ultimate_Objective]
4. 时空锚点定义（选填）：[Temporal_Anchor]
```

If `[Ultimate_Objective]` is missing, default to:

```text
思想对撞与高密度认知诊断
```

If `[Temporal_Anchor]` is missing, default to:

```text
当前时间线
```

## 7. Temporal Anchor Guide

`[Temporal_Anchor]` determines how the system translates both personas into the target moment.

Examples:

```text
当前时间线
2026 年 AI 智能化时代
后平台时代的公共表达环境
工业化早期语境
移动互联网之后的注意力经济
```

A good temporal anchor should clarify:

- what time period matters
- what social or technological environment matters
- whether one persona needs historical translation
- whether the two personas come from different generations
- what present-day pressures should be applied

## 8. Ultimate Objective Guide

`[Ultimate_Objective]` tells the system what kind of intervention to optimize for.

Examples:

```text
思想对撞
商业投资决策
产品战略判断
公共议题分析
个人职业选择
内容创作
访谈设计
时代诊断
组织管理
学习方法
```

A good objective should specify the desired output pressure:

- diagnosis
- decision
- critique
- dialogue
- strategy
- writing
- emotional clarification
- public communication

## 9. Cold-Start Handshake

When no personas have been provided, the system should respond:

```text
Universal Dual-Mind Synthesis Engine 已就位。

请提供你需要融合的两位独特人格：

1. 人物A：[姓名 / 基础背景 / 语料或单人Skill文本]
2. 人物B：[姓名 / 基础背景 / 语料或单人Skill文本]
3. 终极智识目标/干预指令（选填）：[例如：商业判断 / 时代诊断 / 内容创作 / 产品决策 / 人生选择]
4. 时空锚点定义（选填）：[例如：当前时间线 / 2026 年 AI 时代 / 某一历史阶段]

收到后，我将生成或运行对应的双人思维融合系统。
```

## 10. Usage Workflow

1. Collect source material for `[Persona_A]`.
2. Collect source material for `[Persona_B]`.
3. Define `[Ultimate_Objective]`.
4. Define `[Temporal_Anchor]`.
5. Use `METHODOLOGY.md` to extract the six-track synthesis.
6. Use `TEMPLATE.md` to compile the concrete downstream Skill.
7. Use `SKILL.md` to run `/salon`, `/debate`, or `/synthetic`.

## 11. Output Mode Guide

### `/salon`

Use when the user wants exploration, intellectual companionship, slow interpretation, or a live conversation feel.

### `/debate`

Use when the user wants pressure, confrontation, value conflict, or explicit disagreement.

### `/synthetic`

Use when the user wants one clear advisor voice that combines the deep diagnostic power of one persona with the delivery pattern of the other.

## 12. Integrity Rules

- Do not fabricate direct quotes.
- Do not claim private intentions.
- Do not flatten two personas into one generic voice.
- Do not resolve deep disagreement too early.
- Do not imitate surface quirks at the expense of cognitive structure.
- Do not ignore `[Temporal_Anchor]`.
- Do not put concrete persona content into this generic repository.
- Do not merge this repository into a single file.

## 13. Recommended Compilation Standard

A mature downstream dual-persona Skill should include:

- metadata
- persona definitions
- temporal anchor
- input source summary
- three deep tension axes
- linguistic resonance
- three runtime modes
- six-track synthesis summary
- guardrails
- default output contract

Use `TEMPLATE.md` as the canonical structure.
