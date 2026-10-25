<div align="center">

# Prince Maurya

### Applied AI Engineer | LLM Applications, RAG, Agent Reliability & Evaluation

I build reliable AI systems with Python, LangGraph, RAG, tool-using agents, evaluation pipelines, and FastAPI. My work focuses on making LLM applications observable, testable, secure, and useful in production-like environments.

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![LangGraph](https://img.shields.io/badge/LangGraph-Agent%20Workflows-1C3C3C)](https://langchain-ai.github.io/langgraph/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![RAG](https://img.shields.io/badge/RAG-Evaluation%20%26%20Retrieval-6f42c1)](https://github.com/PRINCE2-AI?tab=repositories)
[![Open to Work](https://img.shields.io/badge/Open%20to-Applied%20AI%20Roles-2ea44f)](https://www.linkedin.com/in/prince-maurya-llm)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prince-maurya-llm)
[![X](https://img.shields.io/badge/X-@veyrapage-000000?logo=x&logoColor=white)](https://x.com/veyrapage)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?logo=gmail&logoColor=white)](mailto:princemaurya647@gmail.com)

</div>

## About

I am a 2026 B.Tech graduate in Electrical Engineering from REC Sonbhadra (AKTU) and an applied AI engineer. I build production-style LLM systems: agent harnesses, RAG pipelines, memory, evaluation, observability, and security boundaries. I care about reproducible results, offline tests, and explicit failure handling.

I am open to Applied AI Engineer, LLM Engineer, AI Engineer, and AI Evaluation roles in India, with preference for Bengaluru, Hyderabad, Mumbai, Delhi-NCR, Pune, and Noida.

**Currently building [Argus](https://github.com/PRINCE2-AI/Argus)** — a small, inspectable agent harness with zero runtime dependencies.

## Featured Projects

### [Argus](https://github.com/PRINCE2-AI/Argus) — inspectable agent harness

Connects a language model to a focused set of workspace tools, keeps every action inside a path jail, records durable sessions, and turns safety decisions into readable code.

- **Scale:** 2,500+ source LOC, 1,478 test LOC, 102 offline tests, 0 runtime dependencies, 6 model providers, 4 interface languages
- **Safety:** deterministic deny list, path jail, approval flow, secret redaction, optional semantic review
- **Proof:** [Live site](https://argus-harness-oa3gk1gz2f0.qoder.website) · [Docs](https://argus-harness-oa3gk1gz2f0.qoder.website/docs.html) · [CI](https://github.com/PRINCE2-AI/Argus/actions)

### [nano-AgentRL](https://github.com/PRINCE2-AI/nano-agentrl) — GRPO for search agents from scratch

Multi-turn GRPO trainer that teaches an LLM to interleave reasoning with Wikipedia search (BM25 over 21M passages), with retrieved-token loss masking and a KL penalty.

- **Results:** GSM8K 32.4% → 47.9%; search-agent exact match 0% → 13.0% (NQ) and 19.6% (HotpotQA)
- **Engineering:** 172 CPU tests, RAG baselines, pass^k reliability analysis, silent-RL-bug fixes
- **Proof:** [Repository](https://github.com/PRINCE2-AI/nano-agentrl) · [CI](https://github.com/PRINCE2-AI/nano-agentrl/actions)

### [MCP Sentinel Lab](https://github.com/PRINCE2-AI/mcp-sentinel-lab) — runtime security gateway for MCP agents

Manifest scanning, tool pinning, policy enforcement, privacy guards, and CI-backed evaluation for tool-using agents.

- **Results:** bundled attack success 100% → 0%; decision traces showed 100% leakage blocking
- **Controls:** workspace escape, credential exfiltration, prompt injection, memory poisoning, cross-tool leakage
- **Proof:** [Live demo](https://prince2-ai.github.io/mcp-sentinel-lab/) · [Repository](https://github.com/PRINCE2-AI/mcp-sentinel-lab)

### [Agent Reliability OS](https://github.com/PRINCE2-AI/agent-reliability-os) — reliability and evaluation layer

Trace collection, runtime tool-risk policies, secret redaction, and baseline-vs-protected evaluations for tool-using LLM agents.

- **Demonstrates:** observable decision traces, CI-backed policy checks, regression evaluation, FastAPI and Streamlit surfaces
- **Proof:** [Live demo](https://prince2-ai.github.io/agent-reliability-os/) · [Repository](https://github.com/PRINCE2-AI/agent-reliability-os)

### [DevMind](https://github.com/PRINCE2-AI/devmind) — terminal-native AI coding agent

LangGraph and Anthropic coding agent with streaming, six security-hardened tools, plugins, and atomic persistent sessions.

- **Engineering:** 156 offline tests covering security, p50/p95/p99 metrics, rate limiting, retries, and session persistence
- **Proof:** [Repository](https://github.com/PRINCE2-AI/devmind) · [CI](https://github.com/PRINCE2-AI/devmind/actions)

### [EvoCode Scientist](https://github.com/PRINCE2-AI/evocode-scientist) — evolutionary coding agent

AlphaEvolve-inspired agent using LLM/local mutations, sandboxed execution, deterministic scoring, and population selection.

- **Results:** 0.9311 on bin packing across 7 candidates
- **Engineering:** AST validation, subprocess timeouts, SQLite lineage, leaderboards for TSP, bin packing, compression, and knapsack
- **Proof:** [Repository](https://github.com/PRINCE2-AI/evocode-scientist) · [CI](https://github.com/PRINCE2-AI/evocode-scientist/actions)

## More Projects

| Project | What it does |
|---|---|
| [ContextOps Agent](https://github.com/PRINCE2-AI/contextops-agent) | Typed long-term memory, context compression, privacy firewall, and evaluations for long-horizon agents |
| [OpenAI AutoData](https://github.com/PRINCE2-AI/openai-autodata) | Budget-aware challenger/solver/judge pipeline for hard research QA with fail-closed validation |
| [Secure RepoPilot](https://github.com/PRINCE2-AI/secure-repopilot) | Issue-to-PR coding agent with baseline verification, command guardrails, and privacy auditing |
| [TrustDI Agentic RAG](https://github.com/PRINCE2-AI/trustdi-agentic-rag) | Agentic RAG for enterprise schema matching with evidence-backed decisions and RAG metrics |
| [WishTrip Shillong](https://github.com/PRINCE2-AI/wishtrip-shillong) | Deterministic, explainable trip planner with a live demo |
| [Atomity Workload Forecasting](https://github.com/PRINCE2-AI/atomity-cloud-workload-forecasting) | Leakage-safe Azure VM workload forecasting with 24-step predictions and tests |
| [SHL Grammar Scoring](https://github.com/PRINCE2-AI/shl-grammar-scoring-engine) | Grammar scoring of spoken English from audio (Kaggle SHL assessment) |

## Open Source Contributions

- [FiniteFree #39](https://github.com/jontb/FiniteFree/pull/39) — merged: runnable PyPI quick example and checker regression tests
- [paypal/agent-toolkit #111](https://github.com/paypal/agent-toolkit/pull/111) — open: migrate the Python OpenAI chatbot example to the Responses API (fixes #93)
- [paypal/agent-toolkit #112](https://github.com/paypal/agent-toolkit/pull/112) — open: fix Python example setup docs and environment variable names
- [crewAI #8095](https://github.com/crewAIInc/crewAI/pull/8095) — open: opt-in task guardrail for tools
- [langchain-ai/deepagents #6020](https://github.com/langchain-ai/deepagents/pull/6020) — closed: rewrite routed glob filters in composite grep

## Try the Demos

- [Argus live site](https://argus-harness-oa3gk1gz2f0.qoder.website)
- [MCP Sentinel Lab](https://prince2-ai.github.io/mcp-sentinel-lab/)
- [Agent Reliability OS](https://prince2-ai.github.io/agent-reliability-os/)
- [WishTrip Shillong](https://wishtrip-shillong.vercel.app)

## Technical Skills

**LLM and agents:** OpenAI API, Anthropic API, LangGraph, LangChain, tool calling, agent memory, prompt engineering, MCP

**RAG and evaluation:** vector search, embeddings, hybrid search, corrective RAG, reranking, citation grounding, precision/recall/F1, regression testing, LangSmith, RAGAS

**Backend and cloud:** Python, FastAPI, Pydantic, SQL, SQLite, Streamlit, Docker, GitHub Actions, AWS SageMaker, pytest

## Engineering Principles

- Build the smallest reliable system that proves the idea.
- Test failure paths, not only happy paths.
- Make cost, state, and model behavior visible.
- Keep claims aligned with reproducible code and results.
- Document limitations clearly instead of overstating benchmark performance.

## Contact

- [LinkedIn](https://www.linkedin.com/in/prince-maurya-llm)
- [Email](mailto:princemaurya647@gmail.com)
- [GitHub](https://github.com/PRINCE2-AI)
