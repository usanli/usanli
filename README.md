<div align="center">

# Umut Şanlı

**AI Engineer · Enterprise AI · Retrieval · Document AI · Multi-Agent Systems**

I build AI systems that hold up in production.

[Website](https://umutsanli.com) · [LinkedIn](https://www.linkedin.com/in/umutsanli/) · [Elpis Technology](https://elpis.technology)

</div>

---

## About

I'm an **AI Engineer at ING Hubs** and the founder of **Elpis Technology**.

I build AI systems for real enterprise workflows: retrieval, document intelligence, multi-agent orchestration and automation connected to the systems businesses already depend on.

I started my career in **SAP ABAP**, spending eight years inside enterprise software across finance, procurement, sales, supply chain and core ERP systems. During my MSc in Software Engineering at Boğaziçi University, I moved deeper into AI and began building systems rather than only studying models.

That background shapes how I approach AI:

- **Private by default** — on-premises when the data requires it
- **Permission-aware** — access rights are enforced before retrieval results reach the model
- **Measured, not guessed** — golden sets and retrieval metrics before deployment
- **Deterministic where it matters** — business logic and calculations stay in code
- **Human where it matters** — AI drafts, people make consequential decisions
- **Integrated, not isolated** — AI output reaches the ERP and operational systems where work actually happens

## What I build

### Retrieval & RAG

Hybrid retrieval systems combining **semantic, Turkish lexical and exact-identifier search**, with authorization enforced before results merge.

I work with pgvector, embeddings, reranking, evaluation sets, **NDCG / Recall**, and permission-aware retrieval across sources such as NTFS, Active Directory and SharePoint.

### Document AI

Vision-language pipelines for invoices and business documents: OCR, structured extraction, validation and enterprise integration.

Recent work includes local inference with **Qwen3-VL + MLX-LM** and automated posting into SAP through **BAPI / IDoc**.

### Agents & orchestration

Multi-agent systems where specialized agents have explicit responsibilities, structured handoffs, shared context and recovery paths.

Primary tools include **LangGraph, LangChain and CrewAI**.

### Enterprise integration

AI connected to the systems that run the business rather than living in a demo.

My SAP background includes **ABAP, S/4HANA, FI, MM, SD, TRM, CDS, OData, BAPI, IDoc and SAP BTP**, alongside modern Python and TypeScript services.

---

## Selected work

### [Pithos](https://elpis.technology/products/pithos/) · Enterprise Retrieval

An on-premises, Turkish-first retrieval layer for enterprise AI applications.

- Semantic, Turkish lexical and exact-identifier retrieval
- NTFS, Active Directory and SharePoint permissions enforced before result merging
- Docker-deployed and designed for air-gapped environments
- Turkish OCR with low-confidence review quarantine
- `0.8929 NDCG@10` · `1.00 Recall@20`
- Evaluation set: `530 documents` · `60 Turkish queries`

**Role:** Founder & sole developer, Elpis Technology

---

### Hermes · Local Document AI

A local vision-language pipeline for Turkish e-invoice and e-archive processing.

**Pipeline:**  
`Document → Qwen3-VL-8B → Structured JSON → Validation → SAP BAPI / IDoc`

- Runs locally on Apple Silicon through MLX-LM
- Extracts structured invoice data
- Validates output before ERP submission
- Designed to keep sensitive financial documents inside the enterprise environment

**Role:** Architect & Lead Developer

---

### [WebWeaver](https://github.com/usanli/WebWeaver) · Multi-Agent Systems

A five-agent LLM pipeline that generates websites and applications from a user brief.

`Brief → Planning → Content → Layout → Code → QA → Deployable site`

The system coordinates specialized agents, passes structured context between them and includes recovery when an agent fails.

**Recognition:** Best Capstone Project at Boğaziçi University  
**MSc Software Engineering:** 3.91 GPA · First in cohort

---

### Petrol Ofisi AI Partnership · Enterprise AI

AI work spanning executive education, business transformation and process automation.

Built a **local-LLM Business Transformation Cockpit** that:

1. Reads enterprise process inventories
2. Computes workload analytically in code
3. Uses a local LLM to draft AI opportunities
4. Routes opportunities through process-owner workshops
5. Produces a structured and auditable AI opportunity portfolio

`Code calculates → AI drafts → People decide`

Coverage included **12 directorates and 50 group directorates**.

---

### Harmonia · Financial Reconciliation

AI-powered e-reconciliation platform for outgoing and incoming enterprise financial matching.

- Designed and built end-to-end
- ML-based email parsing
- Matching engine for both flow directions
- Python / FastAPI backend on SAP BTP
- Deployed to enterprise clients

---

### Vencopo · SAP Integration

B2B vendor collaboration platform exposing SAP procurement workflows through a modern web interface.

`Supplier → Portal → RBAC → OData / RFC / BAPI → SAP`

Supports RFQ, purchase orders, advance shipping notices and document sharing without requiring suppliers to work directly in SAP GUI.

[Repository](https://github.com/usanli/Vencopo)

---

### Enterprise RAG Knowledge Assistant

A LangGraph + pgvector retrieval assistant designed for enterprise knowledge access.

Containerized and deployed on GCP, with retrieval and generation separated so the system can be evaluated and controlled independently.

---

## Engineering background

| Area | Technologies |
|---|---|
| **AI / ML** | Python · LLM Engineering · RAG · Hybrid Retrieval · Multi-Agent Systems · VLMs · OCR · MLX · Ollama · OpenAI API · Qwen · Gemma |
| **AI Frameworks** | LangGraph · LangChain · CrewAI · pgvector |
| **Backend** | Python · FastAPI · PostgreSQL · Redis · REST · BFF |
| **Web** | TypeScript · React · Next.js |
| **SAP** | ABAP · S/4HANA · FI · MM · SD · TRM · CDS · OData · BAPI · IDoc · Fiori · SAP BTP |
| **Infrastructure** | Docker · Kubernetes · Terraform · GCP · CI/CD |
| **Evaluation** | Golden sets · NDCG · Recall · Retrieval benchmarking · Human review |

---

## Career

**ING Hubs** · AI Engineer  
`2026 – Present`

**Elpis Technology** · Founder & Principal Consultant  
`2026 – Present`

**Aya Bilişim** · ABAP Consultant → SAP Support Manager → Customer Solution Manager → Customer Solution Manager & AI Lead  
`2019 – 2026`

**Boğaziçi University** · MSc Software Engineering  
`2025` · 3.91 GPA · First in cohort · Best Capstone Project

**Boğaziçi University** · BSc Physics  
`2022`

My enterprise SAP work covered organizations in food production, furniture, chemicals, food retail, restaurant chains, mining, energy, automotive, textiles, paper and packaging, agriculture, cosmetics, steel, diversified holdings and public transportation.

---

## Selected credentials

- **Generative AI Developer** · SAP Certified Associate
- **AI Product Manager Professional Certificate** · Microsoft
- **Machine Learning with Python** · IBM
- **Python for Data Science** · IBM

---

## By the numbers

| | |
|---|---:|
| Enterprise software experience | **8 years** |
| Products shipped | **6** |
| AI systems in production | **3** |
| Enterprise stakeholders | **10+** |
| Pithos evaluation documents | **530** |
| Pithos Turkish test queries | **60** |

---

## Connect

If you're working on **applied AI, enterprise retrieval, document intelligence, local LLMs, AI agents or AI engineering in regulated environments**, I'd be happy to connect.

**[umutsanli.com](https://umutsanli.com)** · **[LinkedIn](https://www.linkedin.com/in/umutsanli/)** · **[Elpis Technology](https://elpis.technology)** · **[Email](mailto:umut.sanli@umutsanli.com)**

<div align="center">

<sub>Building AI systems that enterprises can trust.</sub>

</div>
