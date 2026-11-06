# Yuvrajsinh Jadav

**Full-stack + AI engineer who ships complete products solo** — web, mobile, backend, and production agentic-AI systems.

~500k lines across ~10 shipped products, built end to end by one engineer: schema → backend → UI → deploy. I specialize in **agentic AI with real guardrails** — LLM systems wired into production with the safety and reliability that keeps them trustworthy at the edges — with founding-engineer velocity across the rest of the stack.

📫 devyuvrajsinh@gmail.com · 📍 India (remote) · 🌐 legendev.org

---

## 🔧 Selected work

**VRON** — agentic org-intelligence layer
A ReAct tool-use loop over the Claude CLI: it investigates live system/project state through read-only tools, then answers. Guardrails live in the executor (SQLite `mode=ro`, step caps) so a hallucinating model *cannot* mutate a project. FastAPI + WebSocket streaming, psutil telemetry, canvas-rendered live map.
`Python · FastAPI · WebSockets · asyncio · structured tool-use · SQLite`

**ToCoach** — on-device AI voice coach
Two-way spoken conversations with an AI persona, coaching feedback after. The speech loop runs **entirely on-device**: local Whisper STT (ONNX) → Claude reasoning → Kokoro TTS, behind a stateful behavioral engine. Electron desktop app.
`Electron · React · Whisper · Kokoro · SQLite`

**leadgen** — zero-paid lead-gen platform
Scrapes ICP-fit leads from free sources, scores them by revenue potential, enriches a named decision-maker, runs deliverability-engineered 1:1 outreach (bounce kill-switch, suppression, MX pre-verify), triages replies with a deterministic no-LLM classifier, and surfaces a live CRM. Multi-agent architecture.
`Flask · Next.js · Python · multi-armed-bandit source selection · IMAP`

---

## 🧰 Stack

**Languages** JavaScript/TypeScript · Python
**Frontend** React · Next.js · Electron · React Native
**Backend** Node/Express · FastAPI · Flask · WebSockets · REST
**Data** PostgreSQL · MongoDB · SQLite
**AI** Agentic loops (ReAct) · structured tool-use · on-device STT/TTS (Whisper, Kokoro) · guardrail design · RAG-vs-deterministic judgment
**Infra** Docker · CI/CD · Stripe/Razorpay · Twilio · socket.io

## 📦 Also shipped
Enterprise procurement SaaS (~286k LOC) · a React Native app live on the App Store (Twilio + real-time) · a salon marketplace · healthcare platform + patient app.

*Client products are private — happy to walk through the architecture on a call.*

---

⚡ Available for remote roles and contract work.
