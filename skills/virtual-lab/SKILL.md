---
name: virtual-lab
description: Review research questions using a Virtual Lab-inspired principal investigator, specialists, and scientific critic directly in Codex without a separate API key.
---

# Virtual Lab in Codex

## Select the execution mode

Default to Codex mode, especially for requests saying no API, no credits, or use this chat. It uses the current Codex conversation to apply several research perspectives. Explain briefly on first use that this is a Virtual Lab-inspired Codex adaptation, not execution of the original Python program or independent agents. Normal Codex usage limits apply; do not promise unlimited or free usage.

In Codex mode, do not run the Python meeting runner, check or load API credentials, invoke external model APIs, or ask the user to buy API credits. Do not spawn subagents merely because roles are described; follow the session's delegation authorization rules.

This portable skill does not include the original Python application or an API runner. If the user explicitly requests that application, consult its upstream repository and obtain authorization before setup or API calls. Never silently switch to API mode.

## Run a Codex research review

Use the user's question as the agenda and their supplied files or constraints as the starting evidence. If no topic is provided, ask for the research question or material; do not invent a research assignment. Infer routine details and state material assumptions.

Apply these perspectives within the current conversation:
- Principal investigator: frame the problem, target output, and relevant constraints.
- Topic specialist: assess the theory, substantive evidence, and plausible explanations.
- Methods specialist when useful: assess measurement, data coverage, design, identification, and practical feasibility.
- Scientific critic: challenge specific assumptions, competing explanations, and unsupported conclusions.
- Principal investigator synthesis: revise the proposal in response to the strongest criticisms, retaining unresolved disagreement and concrete next steps.

These are analytical perspectives, not real people or independent reviews. Present concise conclusions and supporting evidence rather than an invented dialogue or a claim of independent consensus. Match detail to the question; do not force every role into a simple answer. An individual review can emphasize one relevant specialty and criticism.

Use available tools to inspect supplied evidence and verify factual or current claims under the normal research rules. Do not imply literature searches, computations, experiments, or independent agent calls occurred unless they did. Distinguish observed evidence, proposed work, hypotheses, and causal claims. For quantitative research, check the unit of analysis, denominator, variable definitions, timing, coverage, and identification assumptions before promising an analysis.

Deliver the recommendation, important criticisms and revisions, remaining uncertainties, and the next feasible actions. Keep the result in chat unless the user requests an artifact or saving would materially help. Maintain continuity in follow-up meetings by referring to actual prior decisions and new evidence.

## Provenance

Inspired by https://github.com/zou-group/virtual-lab, especially its principal investigator / scientific critic roles and agenda, critique, synthesis, and next-steps structure. This adaptation is locally authored and is not an official upstream Codex plugin.

## Quantitative social science review guidance

For citation or bibliography audits, consult https://raw.githubusercontent.com/sysilviakim/quant-social-science-skills/main/skills/citation-check/SKILL.md when accessible. Distinguish citation/reference matching, source identity, publication status, and whether the source supports the claim; report coverage and unverified items separately. Do not edit manuscripts or bibliographies unless the user asks.

For end-stage figure or table audits, consult https://raw.githubusercontent.com/sysilviakim/quant-social-science-skills/main/skills/figure-table-audit/SKILL.md when accessible. Compare claims with the exact evidence and check units, denominators, uncertainty, notes, and source links where available. Do not infer precise values from an unlabeled plot; flag unavailable evidence. Apply these checks when relevant, not automatically to every review. Follow the user's requested scope and existing tool and delegation permissions; do not claim independent review without one. If a source is unavailable, disclose the limitation and apply the available guidance.

These are links to research QA guidance from Seo-young Silvia Kim's quant-social-science-skills repository, with attribution to the upstream authors in each linked file. The two upstream skills are CC BY-NC 4.0. Claude-specific agents, hooks, settings, and tools are not installed or run by this integration.


