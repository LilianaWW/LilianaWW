# Awesome Applied AI

[← Profile](./README.md)

A growing collection of projects, papers, and notes across **AI Builds Itself · Eval · Moderation Policy**.

## AI Builds Itself

Self-improving agents, evolutionary coding, and feedback loops that help AI systems improve their own tools and workflows.

| Resource | Why collect it | Question to investigate |
| --- | --- | --- |
| [Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents](https://arxiv.org/abs/2505.22954) | Research on agents that modify their own code and assess changes empirically. | How are candidate improvements evaluated, retained, and checked for regressions? |
| [AlphaEvolve](https://deepmind.google/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/) | Evolutionary coding that combines proposed programs with automated evaluation. | What makes an evaluator informative enough to guide iterative improvement? |

## Eval

Task design, scoring, error analysis, and reproducible comparisons for models and agents.

| Resource | Why collect it | Question to investigate |
| --- | --- | --- |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) | A framework for language model evaluations. | How should tasks, model interactions, and scoring be separated? |
| [Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness) | Shared tooling for evaluating language models across tasks. | Which configuration choices must be recorded to make comparisons meaningful? |

## Moderation Policy

Policy definitions, labeling criteria, ambiguous cases, and evaluation of moderation decisions.

| Resource | Why collect it | Question to investigate |
| --- | --- | --- |
| [TikTok Community Guidelines](https://www.tiktok.com/community-guidelines/en/) | A public example of platform policy categories and contextual rules. | How can written policy be translated into explicit decision criteria and test cases? |
| [Llama Guard: LLM-based Input-Output Safeguard for Human-AI Conversations](https://arxiv.org/abs/2312.06674) | Research on taxonomy-based classification of conversational inputs and outputs. | How do category definitions and policy adaptation affect moderation decisions? |

## Collection notes

Initial entries collected on **23 October 2026**. These are external references to explore, not claims of completed reproductions. Platform-content policy and conversational safeguards address different settings; their taxonomies should be compared in context.

For each new entry, record: **source → problem → relevant method → open question**. Add experiment results separately, with the task, data, model or version, metric, and failure cases. Public policy references may change; record the version or access date when using them in an experiment.
