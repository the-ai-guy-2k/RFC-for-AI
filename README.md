# The AI RFC

**Request for Comments — Version 2**
Author: Sanil Dale Tison (Tee) · November 21, 2026 · Status: living document — comments welcome, corrections fold into version 3.

> "We need an AI RFC and for someone if there's anyone in the world that could do it is me."

## What it is

A protocol, written in plain words. It defines an AI maturity scale — five levels, no zero — and the setup that runs on it: one person's system for using an AI agent as a participant in his own software, not just a chat he talks to.

Anyone can read it, use it as a model, and argue with it. That is what an RFC is for.

The full protocol is in [`AI-RFC.md`](AI-RFC.md). This README is the short version.

Live companion page: https://taigtsp.duckdns.org/way-i-use-ai/

## The scale, plain

Five levels, 1–5, no zero. Levels 1–3 are done. Levels 4–5 are forecast — the line in the sand is the end of level 3.

- **1 — Ordinary.** Ask a question, get an answer, close the app. Reactive Q&A, writing, search, one-off errands.
- **2 — Engaged.** Real tasks with approvals — reminders, email, calendar, shopping, artifacts. The organised end of engaged: scheduled tasks, connectors, side chats as workspaces, custom skills.
- **3 — This setup.** The agent is wired into the person's own software and acts there, on a schedule, as a participant — plus custom skills and per-user state. The Hive watcher reading comments and replying on the projects is level 3 in action.
- **4 — Cutting edge.** Autonomous execution, agent swarms, event-driven instead of polling, multi-user, self-improving.
- **5 — Past cutting edge.** The system doesn't just work for the person — it works for other people too, and gets better from all of them. The setup becomes the service.

The official term is **AI maturity model**. Gartner's version has five levels too: Awareness, Active, Operational, Systemic, Transformational. This scale maps onto it, roughly — that mapping is a proposed read, not the author's words. Gartner's model is built for organisations; this one is built for one person, and it covers the past *and* the future, including a level nobody has reached yet.

Numbering, settled by the author: plain 1–5, five levels, no zero — and 5 being a Fibonacci number is the Fibonacci reference.

## Three lenses

One number alone does not describe a setup. The scale rates three things at once, on the same five levels. A rating is a triple: (system, architect, user).

1. **The system** — the maturity/knowledge level of the AI system itself.
2. **The engineer/architect** — the knowledge level of the person building or working on the system.
3. **The user** — the knowledge level of the person actually using the system.

The three ratings together say where the whole thing stands.

## Where Tee sits

- **His setup: level 3**, building toward 5.
- **Tee himself: 3.5** — between level 3 and level 4, his words: "Level 3 or 4, not sure... 3.5." That is his self-rating, recorded as he said it, not forced into a single lens. The user lens remains unrated.

Level 5 is not a claim. It is the goal: "there is a fifth level, trust me, I'll invent it if I need to." Nobody is there yet. Tee is the first to define it. Documenting this RFC is itself what pushes the momentum into level 5.

## What's in this repo

- `AI-RFC.md` — the full protocol, v2. The Nebula Pack's 11 sections are its normative core, plus the maturity scale, the terms, the setup, watch-and-reply, the PIO, the continuity store, the rules, the road to 5, and nine appendices from the Kobe-folder survey.
- `README.md` — this file.
- `SETUP.md` — suggested repo name, license choice (yours to pick), and step-by-step instructions to create the repo on github.com and push these files. Nothing here publishes itself.

## How to use it

Read it. Test it against your own setup. Argue with it — that is the point of an RFC. If a line in here does not match the running system it came from, the running system wins and the line gets fixed.

*The AI RFC — v2 · Sanil Dale Tison · November 21, 2026 · Companion page: https://taigtsp.duckdns.org/way-i-use-ai/ · Plain AI, my way.*
