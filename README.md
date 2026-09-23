<!-- Background banner -->
<img src="imgs/GitBack.png" alt="Egor Folley" width="100%">

<p align="center">
  <a href="https://efolley.com/"><img src="https://img.shields.io/badge/Website-efolley.com-0F172A?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/efolley"><img src="https://img.shields.io/badge/LinkedIn-efolley-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.twitter.com/_efolley"><img src="https://img.shields.io/badge/X-@__efolley-000000?style=flat-square&logo=x&logoColor=white" alt="X"></a>
</p>

# Egor Folley
**FDE AI** | New York

Client-facing AI engineer building production agentic systems end-to-end, from C-level discovery to architecture and deployment. Led a $2M AI transformation for $90B AUM PE firm with a team of 8. Deployed 12+ GenAI systems with production architecture, evals, governance, and observability. 2X AI and robotics founder (Techstars, NVIDIA Inception).

## Results

| Outcome | Where |
| --- | --- |
| Due diligence **4 months → ~1 hour** | $2M program, $90B AUM PE firm |
| **93% Recall@10** on a 100+ question golden set | Regression-gated enterprise RAG-KAG |
| Technology adoption **6 weeks → 3** | 5-agent platform, 750 documents |
| Integration effort **−60%** | MCP server over 18 internal APIs |
| Data retrieval **hours → minutes** | GraphRAG copilot, ~3,000-entity graph |
| **~15 h/week** returned to supervisors | Multimodal vision AI, 5 VLM agents |

## How I work

Discovery with the people who own the P&L. Scope to one workflow with a measured baseline. Ship the thin production path first: retrieval, evals, guardrails, tracing. Prove it against the baseline and publish the misses. Hand off a runbook, eval gates, and owners.

Regulated, NDA-bound environments. Client code stays private, so the repos below are open rebuilds of the same patterns on public data.

## Building in public

| Project | What it is | Status |
| --- | --- | --- |
| [Rivet-KAG](https://github.com/efolley/rivet-kag) | Hybrid KAG over your documents, answers cited to source | 🟢 In progress |
| [AgentGate](https://github.com/efolley/agentgate) | Auth, routing, and audit for every agent and MCP call | 🟡 Design |
| [EvalForge](https://github.com/efolley/evalforge) | Auto-generated golden sets and red-team evals | ⚪ Planned |
| [OpenDiligence](https://github.com/efolley/opendiligence) | Multi-agent diligence over SEC EDGAR filings | ⚪ Planned |
| [RegGraph](https://github.com/efolley/reggraph) | Regulatory change mapped onto policy and controls | ⚪ Planned |

Each ships with an architecture diagram, ADRs, an eval scorecard with real numbers, and cost/latency per query. If a number is bad, it goes in the README anyway.

## Stack

Python · TypeScript · LangGraph · LangChain · LangSmith · MCP · GraphRAG · ontologies · Neo4j · Milvus · FastAPI · PostgreSQL · Redis · Docker · Azure · AWS · GCP · Palantir AIP

---

**egor@efolley.com** · [efolley.com](https://efolley.com)
