<div align="center">

# Umut Şanlı

**AI Engineer · Enterprise AI · Retrieval · Document AI · Multi-Agent Systems**

I build AI systems for real business problems.

[Website](https://umutsanli.com) · [LinkedIn](https://www.linkedin.com/in/umutsanli/) · [Elpis Technology](https://elpis.technology)

</div>

---

## About

I'm an **AI Engineer at ING Hubs** and the founder of **Elpis Technology**.

My work is mostly around AI systems that have to work with real company data and existing software. I build retrieval systems, document processing pipelines, AI agents and integrations with enterprise applications.

I started my career as an **SAP ABAP consultant** and spent eight years working on enterprise software across finance, procurement, sales, supply chain and ERP systems. During my MSc in Software Engineering at Boğaziçi University, I moved further into AI and started building production-oriented systems.

That background has a strong influence on how I build AI:

- **Keep sensitive data private** when the environment requires it
- **Respect existing permissions** instead of creating a second access model
- **Measure retrieval and model output** before relying on it
- **Keep business rules in code** when they need deterministic behavior
- **Use AI where it adds value** and keep people in the loop for important decisions
- **Connect AI to existing systems** instead of building isolated demos

## What I work on

### Retrieval and RAG

I build retrieval systems that combine semantic search, Turkish lexical search and exact identifier matching.

My work includes pgvector, embeddings, reranking, retrieval evaluation and permission-aware search across sources such as NTFS, Active Directory and SharePoint.

### Document AI

I work on invoice and business document pipelines covering OCR, vision-language models, structured extraction, validation and ERP integration.

Recent work includes local inference with **Qwen3-VL and MLX-LM**, with sensitive documents processed locally before data is sent to SAP.

### AI agents

I build multi-agent systems where different agents have specific responsibilities and pass structured information between each other.

Tools I have worked with include **LangGraph, LangChain and CrewAI**.

### Enterprise integration

A large part of my work is connecting AI to the software companies already use.

My SAP background includes **ABAP, S/4HANA, FI, MM, SD, TRM, CDS, OData, BAPI, IDoc and SAP BTP**, alongside Python and TypeScript services.

---

## Selected work

### [Pithos](https://elpis.technology/products/pithos/) · Enterprise Retrieval

An on-premises retrieval layer for enterprise AI applications, with a focus on Turkish documents and existing access permissions.

- Semantic, Turkish lexical and exact-identifier search
- NTFS, Active Directory and SharePoint permissions checked before results are combined
- Docker-based deployment for restricted environments
- Turkish OCR with low-confidence review
- `0.8929 NDCG@10` · `1.00 Recall@20`
- Evaluation set: `530 documents` · `60 Turkish queries`

**Role:** Founder and developer, Elpis Technology

---

### Hermes · Local Document AI

A local vision-language pipeline for Turkish e-invoice and e-archive documents.

`Document → Qwen3-VL-8B → Structured JSON → Validation → SAP BAPI / IDoc`

- Runs locally on Apple Silicon with MLX-LM
- Extracts structured invoice data
- Validates the result before ERP submission
- Keeps sensitive financial documents inside the enterprise environment

**Role:** Architect and developer

---

### [WebWeaver](https://github.com/usanli/WebWeaver) · Multi-Agent Systems

A five-agent LLM pipeline that generates websites and applications from a user brief.

`Brief → Planning → Content → Layout → Code → QA`

The project uses separate agents for planning, content, layout, implementation and quality checks.

**Recognition:** Best Capstone Project, Boğaziçi University  
**MSc Software Engineering:** 3.91 GPA · First in cohort

---

### Petrol Ofisi AI Partnership · Enterprise AI

AI work covering business transformation, AI opportunity discovery and process automation.

One of the projects was a local-LLM Business Transformation Cockpit that:

1. Reads enterprise process inventories
2. Calculates workload and process metrics in code
3. Uses a local LLM to suggest potential AI use cases
4. Takes the suggestions into process-owner workshops
5. Produces a structured list of AI opportunities

The work covered **12 directorates and 50 group directorates**.

---

### Harmonia · Financial Reconciliation

An AI-powered e-reconciliation platform for matching outgoing and incoming financial records.

- Designed and built end-to-end
- ML-based email parsing
- Matching engine for both directions
- Python and FastAPI backend on SAP BTP
- Deployed to enterprise clients

---

### Vencopo · SAP Integration

A B2B vendor collaboration platform built around SAP procurement processes.

`Supplier → Portal → RBAC → OData / RFC / BAPI → SAP`

Supports RFQ, purchase orders, advance shipping notices and document sharing without requiring suppliers to work directly in SAP GUI.

[Repository](https://github.com/usanli/Vencopo)

---

### Enterprise RAG Knowledge Assistant

A LangGraph and pgvector based retrieval assistant for enterprise knowledge.

The system is containerized and deployed on GCP. Retrieval and generation are kept separate so they can be evaluated independently.

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

**Elpis Technology** · Founder  
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

I'm interested in **applied AI, enterprise retrieval, document intelligence, local LLMs, AI agents and AI engineering in regulated environments**.

**[umutsanli.com](https://umutsanli.com)** · **[LinkedIn](https://www.linkedin.com/in/umutsanli/)** · **[Elpis Technology](https://elpis.technology)** · **[Email](mailto:umut.sanli@umutsanli.com)**

<div align="center">

<sub>AI systems for real business problems.</sub>

</div>
