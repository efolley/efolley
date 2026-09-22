<!-- Background banner -->
<img src="imgs/GitBack.png" alt="Egor Folley banner" style="width:100%; height:auto; display:block;">

<p align="center" style="margin-top:16px;">
  <a href="https://efolley.com/">
    <img src="https://img.shields.io/badge/EFolley-EFolley-2563EB?style=for-the-badge&logo=nucleo&logoColor=white" height="30" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/efolley">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="30" alt="LinkedIn">
  </a>
  <a href="https://www.twitter.com/_efolley">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" height="30" alt="X/Twitter">
  </a>
</p>

---

## Hello World

I'm Egor Folley, FDE AI at Capco in New York. I help enterprises solve real business problems with AI systems, from C-suite discovery to production deployment. Currently, this girhubis under reconstruction.

### 🛠️ Now building

An open, production-grade reference stack for enterprise agents: 1 shared platform, 3 verticals. Design docs and ADRs land first, code follows. Progress updates weekly.

| Project | What it is | Status | Target |
|---|---|---|---|
| [AgentGate](https://github.com/efolley/agentgate) | Control plane that authenticates, routes, rate-limits and audits every agent and MCP tool call, backed by a permissions knowledge graph | 🟡 Design | Oct 2026 |
| [EvalForge](https://github.com/efolley/evalforge) | Agents mine an enterprise KG to generate golden sets and red-team cases, then run regression evals over MCP | ⚪ Planned | Nov 2026 |
| [OpenDiligence](https://github.com/efolley/opendiligence) | Multi-agent diligence over SEC EDGAR filings in a company KG. Public rebuild of my PE deal-evaluation pattern, no client IP | ⚪ Planned | Nov 2026 |
| [RegGraph](https://github.com/efolley/reggraph) | Maps SEC, FINRA and EU AI Act changes onto a firm's policy and controls graph | ⚪ Planned | Dec 2026 |
| [WarRoom](https://github.com/efolley/warroom) | Multi-agent incident commander: triage and RCA over a service-dependency graph, human-approved rollbacks | ⚪ Planned | Dec 2026 |

**Every repo ships with:** LangGraph multi-agent orchestration · Neo4j GraphRAG · MCP servers · OTel/LangSmith tracing · evals and guardrails · API gateway with retries, circuit breakers and DLQ · Postgres + Redis · architecture diagram, eval scorecard, cost and latency numbers.

### Production track record
- 7+ years shipping GenAI, multi-agent RAG and vision AI systems to production
- 12+ production AI systems across 2 enterprises, 6 SMBs and 4 startups, owning the loop from scoping through deployment and handoff
- Led a $2M AI transformation for a $90B AUM PE firm: ontology-first deal evaluation that cut diligence from 4 months to ~1 hour. 6-agent ingestion pipeline over 20,000+ pages/month, production RAG-KAG on Azure, 93% Recall@10 on a 100+ question golden set
- 2x AI founder: ARTIAL (Techstars, autonomous drone navigation) and Modalina AI (NVIDIA Inception, multimodal vision AI)
- BSc in Mechatronics & Robotics; left a PhD to build ARTIAL

### Selected work
- **Autonomous Drone Navigation**: Fully autonomous visual navigation on NVIDIA Jetson Nano (4GB) in C++/ROS with ORB-SLAM3 and PX4. Live flights: [indoor](https://www.youtube.com/watch?v=koDdYc0uOd0), [outdoor](https://www.youtube.com/watch?v=Xw3yJWd3-2w)
- **Construction Vision AI Agent**: 5 VLM agents with hybrid RAG for real-time safety analysis on GCP; saved supervisors ~15 h/week. Presented at [BuiltWorlds AI Conference](https://builtworlds.com/news/aiml-demos/).
- **Multi-agent RAG Platform**: 5-agent platform that cut technology adoption for field managers from 6 weeks to 3. LangGraph, LangSmith, Milvus, Google App Engine.
- **Agentic GraphRAG Copilot**: Embedded copilot over a ~3,000-entity knowledge graph that cut cross-team data retrieval from hours to minutes, with a DeepEval regression suite.
- **Enterprise MCP Server**: Exposed 18 internal APIs to agents via FastMCP/FastAPI, cutting integration effort by 60%.

> Client systems above were delivered under NDA, so that code stays private. The **Now building** repos are open rebuilds of the same patterns on public data.

### Stack I ship with
`Python` `TypeScript` `LangGraph` `LangChain` `LangSmith` `LlamaIndex` `MCP` `GraphRAG` `Ontology / Knowledge Graphs` `Neo4j` `Milvus` `Palantir AIP` `PyTorch` `FastAPI` `Docker` `AWS` `GCP` `Azure` `ROS` `C++`

---

**Contact**: egor@efolley.com