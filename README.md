<!-- Futuristic Wave Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:6A5ACD,100:2EDAFF&text=%20Welcome%20to%20My%20Universe!%20&fontAlign=50&fontAlignY=35&fontSize=28&fontColor=ffffff&animation=fadeIn" />
</p>

<!-- Typing Introduction -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=2000&pause=800&color=2EDAFF&center=true&vCenter=true&width=1100&lines=Hi,+I'm+Tran+Dinh+Khuong;NLP+%26+Generative+AI+Engineer;Building+Agentic+RAG,+GraphRAG+%26+Multi-Agent+Systems;LangGraph+%7C+LlamaIndex+%7C+LangChain+%7C+Neo4j" alt="Typing SVG" />
</p>

<!-- Terminal Intro -->
<p align="center">
  <img src="https://img.shields.io/badge/Welcome_to_My_Terminal-0D1117?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=2EDAFF" alt="Terminal Badge" />
</p>

<!-- Profile Views -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=khuonglaptri3&label=Profile%20views&color=2EDAFF&style=for-the-badge" alt="Profile Views"/>
</p>

---

### About Me

- **3rd-year IT Student** at Ho Chi Minh City University of Technology and Education (HCMUTE)
- **Specialization:** Natural Language Processing (NLP), Generative AI, and Agentic RAG Systems
- **Core Focus:** Aspect-Based Sentiment Analysis (ABSA), GraphRAG, Stateful Multi-Agent Workflows, and Production AI Engineering
- **GPA:** 3.28 / 4.0
- **Engineering Philosophy:** Designing resilient, closed-loop AI systems that follow the operational lifecycle: `Observe -> Understand -> Explain -> Resolve -> Learn`.
- **Primary Tooling:** Python, PyTorch, Hugging Face Transformers, LangGraph, LlamaIndex, LangChain, Neo4j, Qdrant, FastAPI, Docker, and AWS

> "Transforming unstructured text into structured intelligence, causal explanations, and verifiable decisions."

---

### Core Focus & Skill Highlights

<p align="center">
  <img src="https://img.shields.io/badge/LangGraph-Stateful_Agents-000000?style=for-the-badge&logo=diagram-project&logoColor=2EDAFF"/>
  <img src="https://img.shields.io/badge/LlamaIndex-RAG_Framework-8A2BE2?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-Orchestration-1C3C3C?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Neo4j-GraphRAG_&_Ontology-008CC1?style=for-the-badge&logo=neo4j&logoColor=white"/>
  <img src="https://img.shields.io/badge/Qdrant-Hybrid_Vector_Search-DC2626?style=for-the-badge&logo=qdrant&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging_Face-Transformers_&_ABSA-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</p>

---

### Technical Stack & Frameworks

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,fastapi,postgres,docker,aws,git,github,vscode&perline=9" alt="Tech Stack Icons"/>
</p>

---

### Core Competencies Matrix

| Domain | Methodologies & Frameworks |
|---|---|
| **Natural Language Processing (NLP)** | Aspect-Based Sentiment Analysis (ABSA: ATE, APC, ASTE), PhoBERT, DeBERTa, Transformers, Tokenization, Text Classification, Named Entity Recognition (NER), Model Calibration |
| **Generative AI & Agentic Systems** | LangGraph (Stateful Cyclic Graphs, Multi-Agent Orchestration, Human-in-the-Loop Triage), LangChain (Tools, Structured Outputs, Chains), LlamaIndex (Index Construction, Router Engines, Advanced Retrieval) |
| **Retrieval & Knowledge Graphs** | GraphRAG, Neo4j (Ontology Modeling, Cypher Traversal, Text2Cypher), Qdrant (Dense Semantic + Sparse BM25 Lexical Hybrid Search, Reciprocal Rank Fusion - RRF), Cross-Encoder Reranking |
| **Backend & MLOps** | FastAPI (RESTful API, Streaming), PostgreSQL, Redis (Caching, State), Docker, OpenTelemetry, Argilla (Collaborative Annotation & Active Learning), Git/GitHub CI/CD |
| **AI Governance & Compliance** | PII Masking & Data Minimization, Guardrails against Hallucinations, Groundedness & Citation Verification, Vietnam Personal Data Protection Compliance (Law No. 91/2025/QH15) |

---

### Flagship Project: SenticRAG Platform

#### User-Story-Driven Customer Intelligence, Root-Cause Investigation & Actionable Customer Care

SenticRAG is an enterprise-grade AI platform addressing the gap between macro-level sentiment quantification and micro-level root-cause resolution. It transforms raw, high-volume customer feedback into actionable customer care recommendations through a closed-loop architectural model.

```
Customer Feedback
       |
       v
[ Observe ]   --> Macro ABSA (PhoBERT/DeBERTa) scans 100% corpus for quantification
       |
       v
[ Understand] --> Hybrid Retrieval (Qdrant Dense + Sparse BM25) isolates representative cases
       |
       v
[ Explain ]   --> GraphRAG (Neo4j) maps Issue -> Product/Version -> Symptom -> Root Cause
       |
       v
[ Resolve ]   --> LangGraph Multi-Agent Copilot enforces Policy & drafts verified solutions
       |
       v
[  Learn  ]   --> Human-in-the-loop feedback updates Knowledge Graph & Active Learning queues
```

#### Key Architecture & Engineering Highlights

- **Dual-Pipeline Architecture:**
  - *Pipeline A (Quantitative Truth Layer):* Batch/micro-batch ABSA pipeline (ATE, Category, APC) processing entire feedback streams without sampling bias, delivering verified metrics to BI dashboards.
  - *Pipeline B (Investigation & Resolution):* Latency-optimized retrieval and reasoning engine triggered by customer tickets or analyst cohorts.
- **Hybrid Retrieval & RRF Fusion:** Integrates semantic vector search with lexical BM25 in Qdrant, filtered strictly by version, product, and aspect metadata, fused via Reciprocal Rank Fusion.
- **Neo4j GraphRAG Ontology:** Connects operational nodes (`Product`, `ProductVersion`, `Firmware`, `Issue`, `Symptom`, `RootCause`, `Policy`, `Resolution`, `Evidence`) to prevent hallucinations and trace explanations directly to verified source evidence.
- **Agentic Workflow with LangGraph:** Coordinates ticket triage, customer context resolution, policy eligibility checks, and draft response generation with strict confidence thresholds and human escalation fallbacks.
- **Closed-Loop Feedback System:** Integrates analyst and support agent corrections via Argilla, ensuring knowledge mutations pass formal review gates before updating the production knowledge base.
- **Privacy & Compliance by Design:** Incorporates pseudonymization and PII masking strictly following the Vietnam Personal Data Protection Law (Law No. 91/2025/QH15).

---

### Additional Highlighted Projects

#### [Adult Income Prediction & Fairness-Oriented Feature Engineering](https://github.com/khuonglaptri3/Fair_Machine_Learning_Analyzing)
Production-style data science workflow for binary income classification on the UCI Adult dataset. Implemented modular feature engineering pipelines, robust preprocessing, fairness-conditioned interaction features, model evaluation, and interpretability analysis with reproducible experimentation.

#### Customer Churn Prediction Pipeline
Machine learning pipeline predicting customer churn using domain-specific feature engineering combined with SMOTE balancing. Achieved high predictive accuracy and automated operational insights.

#### Data Visualization & Analytics Dashboard
Interactive PostgreSQL and Plotly visualization dashboard engineered for live data exploration, cohort drill-down, and operational metric storytelling.

---

### Featured Repositories

<p align="center">
  <a href="https://github.com/khuonglaptri3/SmartTrafficDetection">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=khuonglaptri3&repo=SmartTrafficDetection&theme=radical" />
  </a>
  <a href="https://github.com/khuonglaptri3/Fair_Machine_Learning_Analyzing">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=khuonglaptri3&repo=Fair_Machine_Learning_Analyzing&theme=radical" />
  </a>
</p>

---

### Professional Certifications

<p align="center">
  <a href="https://www.credly.com/badges/5ba920fd-4169-4340-99a8-2cd775034f59" target="_blank">
    <img src="https://images.credly.com/size/220x220/images/7b3f119b-ada8-4ff6-817a-f2a8bbb7fe97/blob" width="130" alt="AWS AI Practitioner Badge"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://www.credly.com/badges/5ba920fd-4169-4340-99a8-2cd775034f59" target="_blank">
    <img src="https://images.credly.com/size/220x220/images/e3541a0c-dd4a-4820-8052-5001006efc85/blob" width="130" alt="AWS ML Essentials Badge"/>
  </a>
  &nbsp;&nbsp;
  <a href="#">
    <img src="https://images.credly.com/size/220x220/images/8a28a66c-151d-4f2d-b021-ca7d3e146437/blob" width="130" alt="AWS Data Analytics Badge"/>
  </a>
  &nbsp;&nbsp;
  <a href="#">
    <img src="https://images.credly.com/size/220x220/images/683b2e3c-0d28-42a2-ab84-7203a209f9d0/blob" width="130" alt="AWS Cloud Practitioner Badge"/>
  </a>
</p>

---

### GitHub Analytics & Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=khuonglaptri3&show_icons=true&theme=radical&hide_border=true" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=khuonglaptri3&theme=radical&hide_border=true" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=khuonglaptri3&bg_color=0d1117&color=2EDAFF&line=8A2BE2&point=ffffff&area=true&hide_border=true" width="90%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=khuonglaptri3&layout=compact&theme=radical&hide_border=true&langs_count=8" width="45%" />
  <img src="https://github-profile-trophy.vercel.app/?username=khuonglaptri3&theme=matrix&no-frame=true&row=1&margin-w=15" width="45%" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=khuonglaptri3&theme=radical" width="90%" />
</p>

---

### 3D Contribution Graph

<p align="center">
  <img src="https://raw.githubusercontent.com/khuonglaptri3/khuonglaptri3/main/profile-3d-contrib/profile-night-green.svg" width="90%" alt="3D Contributions"/>
</p>

---

### Contribution Activity

<p align="center">
  <img src="https://raw.githubusercontent.com/khuonglaptri3/khuonglaptri3/output/snake.svg" alt="Snake Animation" width="90%"/>
</p>

---

### Visitor Counter

<p align="center">
  <img src="https://count.getloli.com/get/@khuonglaptri3?theme=rule34" alt="Visitor Count" />
</p>

---

### Connect With Me

<p align="center">
  <a href="mailto:23110035@student.hcmute.edu.vn">
    <img src="https://img.shields.io/badge/Email-23110035@student.hcmute.edu.vn-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white">
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/kh%C6%B0%C6%A1ng-tr%E1%BA%A7n-%C4%91%C3%ACnh-685531320">
    <img src="https://img.shields.io/badge/LinkedIn-Tran_Dinh_Khuong-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  &nbsp;
  <a href="https://www.facebook.com/khueo">
    <img src="https://img.shields.io/badge/Facebook-khuongdev-1877F2?style=for-the-badge&logo=facebook&logoColor=white">
  </a>
  &nbsp;
  <a href="https://github.com/khuonglaptri3">
    <img src="https://img.shields.io/badge/GitHub-khuonglaptri3-181717?style=for-the-badge&logo=github&logoColor=white">
  </a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6A5ACD,100:2EDAFF&height=160&section=footer&text=%20Thanks%20for%20visiting!%20&fontSize=22&fontColor=ffffff&animation=twinkling" />
</p>
