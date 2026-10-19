# Hi, I'm Gargi 👋

<p align="left">
  <a href="https://gargi-vipat.framer.website/"><img src="https://img.shields.io/badge/Portfolio-gargi--vipat.framer.website-2563EB?style=flat-square&logo=framer&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/gargi-vipat/"><img src="https://img.shields.io/badge/LinkedIn-gargi--vipat-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/GargiVipat"><img src="https://img.shields.io/badge/X-%40GargiVipat-000000?style=flat-square&logo=x&logoColor=white" alt="X" /></a>
  <a href="mailto:gargivipat@gmail.com"><img src="https://img.shields.io/badge/Email-gargivipat%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

**AI/ML Engineer specializing in Agentic Systems, Neurosymbolic Architectures, Knowledge Graphs & Provenance Guardrails**  
*MS in Artificial Intelligence, Northeastern University (GPA: 4.00) · AI Engineer @ One Community Global · Ex-MLE Co-op @ GrantX (QWNTL Labs)*

---

### 🚀 What I Build

I design and deploy the systems between raw data, multi-modal perception, and autonomous action: **agentic orchestration pipelines, hybrid retrieval systems, and deterministic neurosymbolic guardrails**. 

My core focus is making AI reliable when **"just prompt an LLM" fails** - enforcing physical, structural, and factual safety boundaries through knowledge graphs (Neo4j, Kùzu), the Model Context Protocol (MCP), and failure-mode auditing.

* **Production Agent & RAG Systems**: Built and deployed containerized RAG systems serving hundreds of enterprise users and organizations, reducing hallucination, latency (from 1min+ to 2s), and token costs by 60%.
* **Deterministic Guardrails & Safe Autonomy**: Architecting neurosymbolic "safety cages" that mathematically enforce hard physical constraints and source provenance before agents can take real-world action.

---

### 🏆 Hackathon Spotlight

#### **[FoGuard](https://x.com/GargiVipat/status/2112239242420334667) - Safe Autonomous Navigation & Incident Recovery for Physical AI Agents**
*Built at Wajo AI's GSD Hackathon (October 2026)*

* **The Problem:** Enterprise warehouse logistics and physical autonomous agents cannot afford routing hallucinations that cause collisions or gridlock when corridors are obstructed.
* **Architecture:** 
  * Built a deterministic **RouteVerifier** guardrail backed by a local **Kùzu** property graph database modeling facility topology.
  * Engineered a custom **Model Context Protocol (MCP)** server providing read-only map state (`get_workspace_topology` and `propose_recovery_route`) to Claude, connected with Wajo's Fo agent MCP to dispatch automated real-world SMS/email incident recovery notices.
  * Designed an interactive diagnostic dashboard with vision anomaly toggles (SegFormer-B0 + Depth Anything V2) to simulate corridor blockages.
* **Results:** Enforced 100% mathematical route validity across 5/5 live end-to-end recovery runs with zero uncorroborated route approvals.

---

### 💼 Work Experience

* **AI Engineer** @ **One Community Global** *(Aug 2026 – Present | Portland, ME)*  
  * Designing AI-driven automated prompt workflows for bio and announcement generation across weekly publications for a 150+ person volunteer organization.
  * Structuring the *Highest Good Network* manual into clean, chunked, RAG-ready knowledge graphs and vector corpora for the organization's upcoming conversational AI assistant.
  * Contributing to technical interviewing and evaluation of prospective software engineering and AI contributors.

* **Machine Learning Engineer** @ **GrantX / QWNTL Labs** *(Jun 2025 – Dec 2025 | Remote)*  
  * **AI Fusion Search:** Built a hybrid search engine combining BM25, ELSER, and dense vector search with LLM reranking and NAICS/FIPS scoring in Elasticsearch, cutting false negatives by 35% and manual review time by 70% across 10,000+ grants for 200+ organizations.
  * **Production RAG Engine (Talk_To_NOFO):** Owned end-to-end design and deployment of a containerized (Docker) production RAG pipeline (LangChain, Supabase, Vertex AI Gemini on Google Cloud Run) enabling 100+ active users to query 500+ dense federal funding notices.
  * **Latency & Cost Optimization:** Diagnosed degraded long-turn responses; engineered sliding-window chat memory with batch summarization, slashing latency from 1min+ to 2s, token usage by 60%, and API spend by $450/month.

* **Graduate Teaching Assistant (Algorithms)** @ **Khoury College, Northeastern University** *(Jan 2025 – Apr 2025)*  
  * Led weekly recitations and office hours for 20+ graduate students on dynamic programming, graph algorithms, and computational complexity (Python, C++), resulting in 90% student improvement.

---

### 🔭 Featured Projects

| Project | Description | Tech Stack | Link |
| :--- | :--- | :--- | :---: |
| **[FoGuard](https://x.com/GargiVipat/status/2112239242420334667)** | Safe autonomous robot navigation & incident rerouting via a deterministic Kùzu property graph guardrail and custom Model Context Protocol (MCP) server. | Kùzu Graph, MCP, Claude Opus, Python, FastHTML | [Demo](https://x.com/GargiVipat/status/2112239242420334667) |
| **[Cat-is-Judging](https://github.com/gargi-09/cat-is-judging)** | Neurosymbolic faithfulness auditor for LLM agents. Features a 52K-record AIS maritime ETL pipeline in SQLite, offset sweeps correcting spoofing alerts (~70% drop), and an automated CI/CD evaluation gate (≥95% faithfulness). | Pydantic v2, Python, SQLite, CI/CD Evaluation | [Repo](https://github.com/gargi-09/cat-is-judging) |
| **[NextNode](https://github.com/gargi-09/NextNode)** | Neurosymbolic career intelligence platform pairing Gemini 2.5 Flash resume parsing with Neo4j knowledge graphs. Walks multi-hop `PREREQUISITE_OF` chains to compute implicit skill gaps with interactive React 19 3D force graphs and MCP multi-agent tool reviews. | Neo4j, Cypher, FastAPI, React 19, @xyflow/react, MCP | [Repo](https://github.com/gargi-09/NextNode) |
| **[Museum Records QA Agent](https://github.com/gargi-09/museum-qa-agent)** | Verified QA agent with provenance tracking. Diagnosed silent prompt drops on production endpoints, integrated 4 deterministic verification passes to catch zero-source false passes, and built hybrid BM25 + bge-small retrieval with RRF. | Python, BM25, bge-small-en, RRF, Prompt Engineering | [Repo](https://github.com/gargi-09/museum-qa-agent) |
| **[DepthAR](https://github.com/gargi-09/depthar)** | Real-time semantics-aware AR occlusion on a single webcam (8–12 FPS). Runs Depth Anything V2 + SegFormer-B0 in parallel with a symbolic rule-based boundary correction layer and 8-frame EMA stabilization (91% accuracy). | PyTorch, Depth Anything V2, SegFormer-B0, OpenCV | [Repo](https://github.com/gargi-09/depthar) |
| **[Construction RAG QA](https://github.com/akashd-98/RAG--an-ablation-study)** | Ablation study and domain-specific Q&A pipeline over dense, unstructured technical construction documents using local embedding models and vector indexing. | Ollama, ChromaDB, LangChain, Python | [Repo](https://github.com/akashd-98/RAG--an-ablation-study) |

📌 *Each repository contains detailed problem statements, architectural diagrams, benchmark evaluations, and reproducible setups.*

---

### 🛠️ Technical Arsenal

* **Languages:** Python, SQL, Cypher, C++, JavaScript/TypeScript
* **Agentic & Neurosymbolic AI:** Model Context Protocol (MCP), Multi-Agent Orchestration, Knowledge Graphs (Neo4j, Kùzu), Trajectory-Level Failure Auditing, Provenance Tracking, Prompt Engineering, Guardrails
* **Machine Learning & RAG:** Hybrid Search (BM25 + ELSER + Dense Vectors), Reciprocal Rank Fusion (RRF), LLM Reranking, LangChain, PyTorch, TensorFlow 2.0, Scikit-learn, OpenCV, Computer Vision (Depth Anything, SegFormer)
* **Databases & Vector Stores:** Neo4j, Kùzu Graph, Supabase (pgvector), Elasticsearch, ChromaDB, SQLite, MySQL
* **Cloud & DevOps:** Google Cloud Run, Vertex AI, Docker, AWS, Databricks, FastAPI, Git, CI/CD Actions, React 19

---

### 💡 What I'm Focused On Right Now

* **Architecting MCP-Native Agents:** Standardizing tool execution, permission boundaries, and stateful verification between foundational models and enterprise knowledge graphs.
* **Deterministic Evaluation & Grounding:** Eliminating silent failure modes in high-stakes agentic pipelines through symbolic assertions, self-consistency scoring, and provenance verification.
* **Seeking Roles:** Actively interviewing for **full-time AI/ML Engineer**, **Forward Deployed Engineer (FDE)** and **Agentic Infrastructure** roles where reliability, latency, and verifiable grounding matter.

---

### 📫 Let's Connect

* 🌐 **Portfolio:** [gargi-vipat.framer.website](https://gargi-vipat.framer.website/)
* 💼 **LinkedIn:** [linkedin.com/in/gargi-vipat](https://www.linkedin.com/in/gargi-vipat/)
* 🐙 **GitHub:** [github.com/gargi-09](https://github.com/gargi-09)
* 🐦 **X (Twitter):** [@GargiVipat](https://x.com/GargiVipat)
* 📬 **Email:** [gargivipat@gmail.com](mailto:gargivipat@gmail.com)
