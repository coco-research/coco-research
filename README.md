# Coco Research

Coco Research: local-first tools for people who work with AI agents.

What this work is about: governed memory, agents that follow rules and verify their own work, data sovereignty, and shipping fast without hand-waving.

## Coco, the flagship

**[coco](https://github.com/coco-research/coco)** is an agentic-AI orchestration framework that turns Claude Code, Cursor, or Codex into a full engineering department: an advisory board, skills, and commands. Open-core — the framework is MIT; the Super Intelligence board is proprietary.

## The Coco suite

Original work, grouped by what it does.

**Platform and memory**
- **Coco Platform**, a local-first control plane for AI coding agents that pairs a React UI with a FastAPI backend and a governed memory architecture (private).
- **Coco Hermes**, the backend intelligence layer — API, RAG, a canonical entity spine (deduplicated), a hierarchical memory tree, and a citation-gated retrieval router (private runtime).
- **Coco Memory**, a deduplicated entity spine plus a cross-tool operational thread that lets Claude Code and Cursor share one live context (private runtime).
- **Coco Router**, sovereign model routing that dispatches every call by task, cost, and load and hard-blocks raw public-cloud egress for regulated content (private runtime).
- **Coco Connect**, a one-command installer that wires Coco into Claude Code and Cursor with idempotent, backed-up, health-checked connections (private runtime).

**Governance and reasoning**
- **[coco-loops](https://github.com/coco-research/coco-loops)**, a governed autonomous-loop framework: a verifier that defaults to reject, an immutable eight-invariant constitution only a human can amend, a bounded-lifetime kill switch, and a promotion gate. Source-available.
- **Coco Superintelligence Teams**, attributed decision panels, used for real architecture and product decisions. Ships inside `coco` as the proprietary core of the open-core split.
- **[coco-fusion](https://github.com/coco-research/coco-fusion)**, a bring-your-own-key multi-model persona council, parked after an honest null-result evaluation against a single frontier model. Source-available.

**Apps and tools**
- **[Coco-Voice](https://github.com/coco-research/Coco-Voice)**, an on-device speech-to-text desktop app.
- **Coco-PDF**, a one-click desktop PDF editor (private).
- **[PM-Studio](https://github.com/coco-research/PM-Studio)**, a product-management deliverable and document studio.
- **StoryDeck**, a local-first, on-device sprint deck tool (private).
- **PM-with-AI**, a tool-agnostic methodology for working with AI as a product manager (private).
- **Mira**, a local-first short-form-video engine (English and Hindi, human in the loop). Private; will publish under AGPL-3.0.
- **Coco Graphify**, a managed code-knowledge-graph; and **Coco Ads**, a fully local launch-video skill adapted from the open-source `brag` skill (credited).

## A note on this account

Alongside the original work above, this account keeps a curated set of forks we study to benchmark our own product decisions (model routers, agent harnesses, memory systems, and video tools). Those are other people's projects, kept for reference, and are not represented as ours.
