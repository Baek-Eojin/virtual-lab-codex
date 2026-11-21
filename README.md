# Virtual Lab for Codex

A portable Codex skill for examining research questions through the perspectives of a principal investigator, a topic specialist, a methods specialist, and a scientific critic. It synthesizes these perspectives in a conversation and clearly distinguishes evidence, assumptions, and proposed research.

This is a locally authored adaptation inspired by [zou-group/virtual-lab](https://github.com/zou-group/virtual-lab). It is not the original Virtual Lab program, an official upstream plugin, or a claim that the perspectives are independent agents. It does not require a separate API key in Codex mode; normal Codex limits apply.

## Install

Copy `skills/virtual-lab` to your Codex skills directory (`~/.codex/skills/virtual-lab`). Restart Codex if needed for skill discovery. Invoke it in a chat, for example:

> Use $virtual-lab to review my research question and suggest a feasible identification strategy.

Provide the question, data and constraints you want reviewed. The skill will not invent a research assignment. It uses available tools to verify claims where appropriate and reports limitations.

## Quantitative research checks

For relevant citation checks or end-stage figure and table audits, the skill links to [quant-social-science-skills](https://github.com/sysilviakim/quant-social-science-skills). Those two upstream instructions are available under CC BY-NC 4.0 and retain their own attribution. They are linked, not bundled; availability depends on network access. Claude-specific hooks, settings, and agents are not installed by this repository.

## Scope

This repository contains instructions for Codex, not an executable multi-agent meeting system. It does not bundle or configure the upstream Python application or its API runner. If you want the original program, consult its repository separately. No credentials, personal research files, or computer-specific paths are included.
