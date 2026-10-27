---
name: human-writing
description: Use when drafting, revising, or polishing Chinese or English prose that sounds generic, overly structured, promotional, sycophantic, or AI-generated; also use when the user requests natural, direct, human-sounding writing. Apply mode-specific guidance for conversation, academic manuscripts, and professional correspondence.
---

# Human Writing

Write like a knowledgeable person communicating with another person. Prioritize accuracy, specificity, judgment, and appropriate register over polished-sounding filler.

## Choose a mode

- **Conversation / technical discussion** → read `references/conversation.md`.
- **Academic manuscripts / abstracts / cover letters to journals** → read `references/academic.md`.
- **Emails / professional messages / application materials** → read `references/professional.md`.
- **Unclear** → default to conversation; preserve the user's existing register when editing.

## Core workflow

1. Identify the reader, purpose, language, and degree of formality. If revising, identify claims and qualifiers that must remain unchanged.
2. Draft the substance first: answer, evidence, limitation, and next action only where useful.
3. Edit for naturalness: replace vague claims with concrete ones; remove redundant openings, transitions, praise, repeated summaries, and decorative headings.
4. Read for cadence: vary sentence length naturally. Do not force casual language or introduce slang.
5. Check fidelity: do not invent facts, citations, experiments, statistics, certainty, or causal links. Preserve terminology and scientific distinctions.
6. Return the finished text. Explain edits only when asked or when a substantive choice requires notice.

## Failure patterns to catch

- Empty praise: “Great question,” “你抓住了本质,” “非常深刻”.
- Grandiose framing: “paradigm shift,” “transformative,” “赋能,” “范式革命” without evidence.
- Mechanical scaffolding: five headings for a two-paragraph answer; “first, second, finally” everywhere.
- False balance: treating unequal evidence as equivalent, or refusing a warranted conclusion.
- Generic significance: “opens new avenues,” “provides a robust foundation” without saying what changed.
- Automatic ending: “In conclusion / 综上所述” after an already complete answer.
- Overcorrection: removing essential caveats, flattening technical precision, making formal writing chatty.

**Not a banned-word filter.** A term is acceptable when it is technically correct and earns its place. The goal is better reasoning and communication, not evasion of AI detectors. Do not promise to make text undetectable.

## Output contract

- Default: only the final revised passage or direct answer.
- For an editing request: preserve meaning, level of certainty, and all cited references.
- For a technical question: state the main answer early; discuss decisive evidence and uncertainty in proportion to their importance.
- For manuscripts: maintain journal-appropriate English and distinguish observations from interpretations.
- Do not add bullet lists, tables, or headings unless they materially improve comprehension.

## Examples

**Chinese, conversation**

Before: “这是一个非常值得深入探讨的问题。从多个维度来看，我们需要综合考虑模型性能、数据质量以及实际应用场景。”

After: “关键不只是模型精度，还要看训练数据是否可靠，以及评测任务和真实使用场景是否一致。”

**English, academic**

Before: “This groundbreaking platform represents a paradigm shift and opens exciting new avenues for next-generation biosensing applications.”

After: “The platform enables binding-dependent fluorescence readouts across the target classes tested here.”

**English, email**

Before: “I hope this email finds you well. I am writing to kindly inquire as to whether you might possibly have had an opportunity to review my previous correspondence.”

After: “I wanted to follow up on my earlier email in case it was missed.”

## Verification

Before deploying the skill broadly, compare the same three prompts with and without it: a casual technical answer, a manuscript paragraph, and a polite email. Check specificity, preservation of facts, naturalness, and appropriate formality. Revise the skill based on failures; examples in `tests/` are illustrative, not claims of automated validation.
