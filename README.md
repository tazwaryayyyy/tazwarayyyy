# TAZWAR AHNAF ENAN

I build agentic backends and governance infrastructure. The systems I care about are ones where the AI's decision is logged somewhere immutable and wrong behavior has a cost attached to it. I work in Rust, Python, and TypeScript, ship solo, and use free-tier infrastructure for everything. Most of this comes out of hackathon work, but the architecture is real.
Right now I'm focused on the gap between "the model returned something" and "the model did the right thing, verifiably."
---

## Signature Projects

### [Memoire](https://github.com/tazwaryayyyy/Memorie-AI)
A Rust memory engine that scores every lesson at ingestion, tracks trust via EMA across reinforcement cycles, and tells agents whether to FOLLOW, HINT, or IGNORE each recalled memory.

![Rust](https://img.shields.io/badge/Rust-111827?style=flat-square&logo=rust&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-111827?style=flat-square&logo=sqlite&logoColor=white)
![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-111827?style=flat-square&logo=onnx&logoColor=white)

---

### [AegisMorpheme-X](https://github.com/tazwaryayyyy/Aegis-Morpheme-X)
Governance layer for AI agents: every decision is sealed on Hedera HCS, anomalous outputs trigger on-chain HTS token slashing, no manual review required.

![Hedera](https://img.shields.io/badge/Hedera-111827?style=flat-square&logo=hedera&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=flat-square&logo=python&logoColor=white)

---

### [ArcReflex](https://github.com/tazwaryayyyy/arcreflex)
Multi-agent orchestrator that withholds USDC micropayments until agent output clears a quality gate; settlement runs via EIP-3009 authorization on Arc with a Vyper contract enforcing the rules.

![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white)
![Vyper](https://img.shields.io/badge/Vyper-111827?style=flat-square&logo=ethereum&logoColor=white)
![Circle USDC](https://img.shields.io/badge/Circle_USDC-111827?style=flat-square&logo=circle&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-111827?style=flat-square&logo=d3dotjs&logoColor=white)

---

### [AuthBridge](https://github.com/tazwaryayyyy/authbridge)
Prior authorization agent that reads a patient's FHIR R4 record, scores clinical evidence against payer criteria (0–100), and drafts a submission-ready letter in under 30 seconds.

![FastAPI](https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=white)
![FHIR R4](https://img.shields.io/badge/FHIR_R4-111827?style=flat-square&logo=data&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111827?style=flat-square&logo=anthropic&logoColor=white)
![A2A](https://img.shields.io/badge/A2A-111827?style=flat-square&logo=google&logoColor=white)

---

## Selected Work

| Project | What It Does | Stack |
|---|---|---|
| [PostMortem.ai](https://github.com/tazwaryayyyy/postmortem-ai) | Streams a full incident RCA in ~93 seconds via SSE | FastAPI, Groq, SSE, Vanilla JS |
| [BlastRadius](https://github.com/tazwaryayyyy/blastradius) | Traces downstream PR impact as a D3 call graph before merge | FastAPI, IBM Bob, D3.js |
| [QuotaDrift](https://github.com/tazwaryayyyy/quotadrift) | Enforces per-request latency/cost/reliability contracts across LLM providers | FastAPI, LiteLLM, Prometheus |
| [ProxyMe](https://github.com/tazwaryayyyy/ProxyME) | AI meeting assistant that requires explicit Auth0 CIBA push approval before acting | Auth0 FGA, Groq, WebSocket |
| [ROCmPort AI](https://github.com/tazwaryayyyy/rocmport-ai) | CUDA-to-HIP migration loop with per-step compile/profile evidence | Groq, CrewAI, FastAPI, SSE |
| [WillSpend](https://github.com/tazwaryayyyy/willspend) | Computes the real cost of delayed financial decisions with Monte Carlo projection | FastAPI, Groq, Chart.js |
| [Sativus AI](https://github.com/tazwaryayyyy/sativus-ai) | Plant diagnosis via Groq vision with live voice using Deepgram STT + ElevenLabs TTS | FastAPI, WebSocket, PWA |
| [Constit](https://github.com/tazwaryayyyy/constit) | Generates compliant civic campaign outreach copy for political candidates | Next.js, Supabase, Groq |
| [Debt Spiral](https://github.com/tazwaryayyyy/debt-spiral) | Debt risk visualization with emergency-state UX switching | FastAPI, JavaScript, Chart.js, Groq |

---

## Stack

![Rust](https://img.shields.io/badge/Rust-111827?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=white)
![Hedera](https://img.shields.io/badge/Hedera-111827?style=flat-square&logo=hedera&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-111827?style=flat-square&logo=sqlite&logoColor=white)

---

Everything deploys on free tier. The constraints are real; so is the output.