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

### [ROCmPort AI](https://github.com/tazwaryayyyy/rocmport-ai)
Multi-agent pipeline that migrates CUDA kernels to AMD ROCm/HIP — catching the wavefront-64 bugs hipify misses, compiling with hipcc, profiling with rocprof on real MI300X hardware, and iterating until the output is correct and fast. Includes a 170-example correctness dataset and a fine-tuned Qwen2.5-Coder-7B model trained on AMD hardware.

![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-111827?style=flat-square&logo=groq&logoColor=white)
![ROCm](https://img.shields.io/badge/ROCm-111827?style=flat-square&logo=amd&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=flat-square&logo=python&logoColor=white)

---

## Selected Work

| Project | What It Does | Stack |
|---|---|---|
| [PostMortem.ai](https://github.com/tazwaryayyyy/postmortem-ai) | Streams a full incident RCA in ~93 seconds via SSE | FastAPI, Groq, SSE, Vanilla JS |
| [BlastRadius](https://github.com/tazwaryayyyy/blastradius) | Two-stage reasoning pipeline (TraceAgent + RemediationAgent) powered by IBM Bob; traces transitive call chains across any GitHub PR and issues a BLOCK/PROCEED verdict with missing test stubs in 30s | FastAPI, IBM watsonx.ai, D3.js |
| [QuotaDrift](https://github.com/tazwaryayyyy/quotadrift) | Enforces per-request latency/cost/reliability contracts across LLM providers | FastAPI, LiteLLM, Prometheus |
| [ProxyMe](https://github.com/tazwaryayyyy/ProxyME) | AI meeting assistant that requires explicit Auth0 CIBA push approval before acting | Auth0 FGA, Groq, WebSocket |
| [AegisMorpheme-X](https://github.com/tazwaryayyyy/Aegis-Morpheme-X) | Governance layer for AI agents: every decision sealed on Hedera HCS, anomalous outputs trigger on-chain HTS token slashing, no manual review required | Hedera, FastAPI, React, LangGraph |
| [WillSpend](https://github.com/tazwaryayyyy/willspend) | Computes the real cost of delayed financial decisions with Monte Carlo projection | FastAPI, Groq, Chart.js |
| [Sativus AI](https://github.com/tazwaryayyyy/sativus-ai) | Plant diagnosis via Groq vision with live voice using Deepgram STT + ElevenLabs TTS | FastAPI, WebSocket, PWA |
| [Constit](https://github.com/tazwaryayyyy/constit) | End-to-end constituent outreach: CSV contact import, Groq-generated SMS variants, Twilio delivery, reply inbox, campaign analytics, and Stripe-billed team workspaces | Next.js, Supabase, Twilio, Groq, Stripe |
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