# Ilyas Baiduanov

**AI-first developer.** I build web and mobile apps, backends and automations — from idea to release — working with AI agents: Claude Code, Codex and Hermes.

Almaty, Kazakhstan · remote · [i01.kz](https://i01.kz) · [ilyas@baiduanov.kz](mailto:ilyas@baiduanov.kz) · Telegram [@ilyas_qz](https://t.me/ilyas_qz)

## Shipped

| Product | Platform | What it is |
|---|---|---|
| [STDIO](https://apps.apple.com/app/id6771886622) | iOS · 2026 | AI photo studio. First commit to the App Store in 9 days: React Native app, Cloudflare Workers backend (D1, KV, cron), OpenAI gpt-image-2, RevenueCat subscriptions. |
| [Dosefy](https://apps.apple.com/app/id6760745705) | iOS · 2026 | Offline-first GLP-1 therapy tracker with a weekly GPT-4o summary via Supabase Edge Functions. 141 users in the first 10 weeks. |
| [Dream Journal](https://apps.apple.com/app/id6760018724) | iOS · 2026 | Dream interpretation with GPT-4o and voice input transcribed by Whisper. |
| [Xplain AI](https://apps.apple.com/app/id6759371891) | iOS · 2026 | AI tutor that explains any topic in 5 styles, with follow-up chat. |
| [Picscope](https://apps.apple.com/app/id1441105890) | iOS · 2018, v2.0 in 2026 | Splits panoramas into seamless Instagram carousels; rebuilt on Expo. |
| [vg.kz](https://www.vg.kz) | Web · 2026 | Corporate website of Volkovgeology JSC: 328 pages in Russian, Kazakh and English on static Next.js, audited by 25 AI agents. |
| [BalaSpace](https://balaspace.app) | iOS, Android, web · TestFlight | Platform for private kindergartens: directors, teachers and parents. Supabase with RLS, 12 Edge Functions, Jest and Maestro e2e tests. |

Also **BusCore** — a safety-monitoring backend for a bus fleet: telemetry, 6 violation detectors, live SSE feed, Telegram alerts. FastAPI, PostgreSQL, Docker, 46 tests.

Most product code lives in private repositories. Happy to walk through the architecture and the code on a call.

## How I build with AI

- **Spec → plan with tests → an agent implements → a second agent reviews → CI → on-device check → release.**
- **Claude Code** writes the code and **Codex** reviews it in read-only mode. **Hermes**, my always-on agent on a Mac mini, plans the work, hands code to Codex in isolated git worktrees and accepts it only on evidence.
- **Obsidian** is the shared memory for every agent: each project keeps a brief, status, decisions, handoffs and a verification log.
- **Models:** Claude Opus 5.5 and Fable 5.1, GPT-6.1 Sol and GPT-6 Astra for development; gpt-image-2, GPT-4o and Whisper inside products.

## Stack

TypeScript · React Native / Expo · Next.js · Node.js · Python (FastAPI, aiogram) · Supabase · Cloudflare Workers · PostgreSQL · Docker · Vercel · GitHub Actions · RevenueCat · Sentry · PostHog
