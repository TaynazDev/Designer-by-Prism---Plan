# Designer by Prism — App Plan

**Live:** [taynazdev.github.io/Designer-by-Prism---Plan/designer-plan.html](https://taynazdev.github.io/Designer-by-Prism---Plan/designer-plan.html)

A planning document for **Designer by Prism** — an AI self-improvement app targeting Gen Z and Gen Alpha, part of the Prism Suite.

---

## What it is

Designer is an AI that builds a personal profile of you through conversation and optional photo uploads, then gives honest, specific feedback on how to level up your appearance, style, vibe, and social presence. Progress is tracked via a persistent score.

---

## Sections

- **Mode system** — five modes from Relaxed to Brutal, scaling AI honesty
- **Score system** — 0–100 scale that gets exponentially harder to climb
- **Core features** — intake, photo analysis, the audit, check-ins, vibe profile, glow-up roadmap
- **AI system design** — prompt architecture for intake, check-ins, and mode tone
- **Tech stack** — Next.js, Claude Sonnet 4.6, Supabase, Prism ID, Upstash Redis
- **Suite connections** — Mood, Grind, Roast, Social integrations
- **Monetisation** — Free / Designer Pro / Prism Pass tiers
- **Roadmap** — four-phase build plan
- **Open questions** — privacy, safety, cost, body image considerations

---

## Stack

| Layer | Choice |
|---|---|
| Frontend | Next.js (WKWebView shell for iOS) |
| AI | Claude Sonnet 4.6 (vision + text) |
| Database | Supabase |
| Auth | Prism ID |
| Storage | Supabase Storage |
| Rate limiting | Upstash Redis |

---

## Part of

[Prism Suite](https://github.com/TaynazDev) — a connected set of AI-powered apps built for Gen Z.
