# Nekhil Kumar Agarwal

Product Engineer, applied AI. I build LLM data pipelines, the checks that keep them honest, and the product around
them.

Bhubaneswar, India · open to relocation and remote work · available now

## Frep (formerly Tiffyn), March to September 2026

First engineering hire at Frep, a meal planner for Indian families in closed beta on iOS and Android; the only
full-time engineer until June, working with the founders.

- **Meal-planning engine.** Moved the planner from ~15,000 fixed main-and-side pairs to meals of one to four dishes
  built for each home, on plate rules I designed, and led the TypeScript rebuild (live for the beta in August). The
  next version, after benchmarking a co-founder's prototype, logs every substitution and reports what was and wasn't
  delivered; repeats on a regenerated week fell by about 90% in tests.
- **Recipe catalogue.** A 17-stage Python and LLM pipeline turned 8,000+ recipes into nearly 7,000 live ones, with
  diet and allergens computed from ingredients and every image checked by a vision LLM.
- **Speed and data.** Weekly plans took nearly a minute; I traced it to loading recipe data, not the engine, and
  cached it: under half a second. Designed the PostgreSQL recipe schema.
- **Support.** Rebuilt the RAG support bot (one LLM call drafts, a second checks, doubts go to a human) on a help
  centre I rewrote as its knowledge base.
- **Backend.** Took the inherited NestJS backend to launch: security hardening, CI, and deploys moved to GitHub
  Actions.

Frep's code is private, so this work doesn't show on the contribution graph here.

## How I work with AI coding agents

Claude Code agents write code to my specs; I make the decisions and check the result, not the agent's report. CI and
a hook that blocks production migrations keep them in bounds, and I keep a written log of decisions, including the
calls I got wrong.

## Selected work

- **[invoice-reader](https://github.com/Agarwal-Nekhil/invoice-reader)**: invoice PDF to JSON, with an OCR fallback
  for scans and an LLM filling the caller's template; FastAPI, Docker. 2025.
- A merged fix to [QtScrcpyCore](https://github.com/barry-ran/QtScrcpyCore/pull/17): re-centring the mouse cursor on
  macOS. July 2026.

## Stack

TypeScript, Node.js, React Native, Next.js, PostgreSQL, Redis, Python; Claude, OpenAI, Gemini.

## Contact

agrawalnikhil1900@gmail.com · [LinkedIn](https://www.linkedin.com/in/nekhil-k-agarwal/)
