<div align="center">

# ⚡ ZAID SALMAN

### 🤖 Generative AI Engineer × 🧠 Agentic RAG × ☁️ DevOps

### Production RAG • ACRFP • Cloud platforms on Azure & AWS

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=4F8BFF&center=true&vCenter=true&width=780&lines=Generative+AI+Engineer;Agentic+RAG+Systems;ACRFP+on+Azure+AKS;DevOps+%7C+Kubernetes+%7C+Terraform;FastAPI+%C2%B7+LangGraph+%C2%B7+Qdrant" alt="Typing animation" />

<br>

```
╔═══════════════════════════════════════════════════════════════╗
║  Generative AI, taken from prototype to production            ║
║  Agentic RAG • ACRFP • Kubernetes • Terraform • CI/CD         ║
║  Bengaluru  |  Open to India, UAE, KSA, and Europe            ║
╚═══════════════════════════════════════════════════════════════╝
```

<br>

<a href="https://www.linkedin.com/in/zaidsalman">
  <img src="https://img.shields.io/badge/LinkedIn-Zaid_Salman-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://salman167.github.io">
  <img src="https://img.shields.io/badge/Portfolio-salman167.github.io-6E40C9?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio" />
</a>
<a href="mailto:zaid.cloudsre@gmail.com">
  <img src="https://img.shields.io/badge/Email-zaid.cloudsre@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<br><br>

![Profile views](https://komarev.com/ghpvc/?username=Salman167&color=blueviolet&style=flat-square)
[![GitHub followers](https://img.shields.io/github/followers/Salman167?label=Follow&style=social)](https://github.com/Salman167)

</div>

---

# 🧠 About Me

I am a **Generative AI and AI Platform Engineer** with a DevOps foundation. I build production **Agentic RAG** systems and the **Agentic Cloud Reliability & FinOps Platform (ACRFP)** — multi-agent workflows that stay inside policy, approval, and observability gates.

Day to day that means LangGraph agents, FastAPI services, hybrid retrieval, and the Kubernetes, Terraform, and CI/CD path that gets those systems onto Azure and AWS.

<details open>
<summary><b>📋 Technical snapshot</b></summary>

```bash
$ whoami
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Name      : Zaid Salman
Role      : Generative AI Engineer | AI Platform | DevOps
Focus     : Agentic RAG, ACRFP, production LLM systems
Stack     : Python, FastAPI, LangGraph, Qdrant, AKS
Cloud     : Azure, AWS, Kubernetes, Terraform, GitHub Actions
Certs     : AWS SAA  |  AZ-104  |  AZ-400
Location  : Bengaluru, India
Status    : Building production GenAI platforms
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</details>

---

# 🚀 What I'm Building

### ☁️ ACRFP — Agentic Cloud Reliability & FinOps Platform

**[Salman167/acrfp](https://github.com/Salman167/acrfp)**

Multi-agent system on Azure AKS that watches Kubernetes and cloud signals, diagnoses reliability and cost issues, and proposes typed fixes. A guardrail proxy decides allow, require-approval, or deny. Agents do not call kubectl or ARM directly.

```
Event → API Gateway → LangGraph Orchestrator
                          │
            Diagnosis   FinOps   Remediation
                          │
                   Guardrail Proxy
                          │
              ALLOW · REQUIRE_APPROVAL · DENY
```

| Piece | What it does |
|---------|-------------|
| Diagnosis agent | Reads signals and runbooks |
| FinOps agent | Cost and waste findings |
| Remediation agent | Typed fix proposals |
| Guardrail proxy | Risk from action type + parameters |
| Approval queue | Human gate before destructive changes |

---

### 🔍 Enterprise Agentic RAG Platform

**[Salman167/Enterprise-rag-platform](https://github.com/Salman167/Enterprise-rag-platform)**

Multilingual enterprise RAG for English, Arabic, French, and German. Twelve microservices cover upload, OCR, locale-aware chunking, embeddings, hybrid retrieval, citations, and feedback.

```
Users → API Gateway → Auth → RAG services → Qdrant / PostgreSQL / MinIO / Redis
                              ├── Ingest: OCR → Chunk → Embed
                              └── Query: LangGraph → Retrieve → Cite → Answer
```

| Piece | What it does |
|---------|-------------|
| Hybrid retrieval | Dense + keyword search |
| LangGraph query path | Grounded answers with citations |
| Evaluation | Langfuse tracing and RAGAS quality gates |
| Controls | JWT/RBAC, PII redaction, GDPR and PDPL region tags |
| Sources | SharePoint and Confluence style document sync |

---

### 🛠️ DevOps & Cloud Delivery

The same platforms are shipped with containers, GitOps, and infrastructure as code — not left as notebooks.

| Area | What I use it for |
|---------|-------------|
| Kubernetes | AKS / EKS, Helm, Argo CD, autoscaling |
| IaC | Terraform, Ansible |
| CI/CD | GitHub Actions, Jenkins, Azure DevOps |
| Observability | Prometheus, Grafana, Langfuse |
| FinOps | Rightsizing, lifecycle policies, stale-resource cleanup |

- **[Cloud-cost-optimization](https://github.com/Salman167/Cloud-cost-optimization)** — AWS Lambda that finds EBS snapshots no longer tied to an active instance and removes them.
- **[gh-actions](https://github.com/Salman167/gh-actions)** — GitHub Actions on a Vite app.
- **[Portfolio](https://salman167.github.io)** — short public snapshot of this work.

---

# 💻 Tech Stack

### 🤖 Agentic RAG & LLM engineering

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/Agentic_RAG-FF6B6B?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-4F46E5?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-E11D48?style=flat-square)

### 🗄️ Data & services

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

### ☁️ DevOps & cloud

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### 🎓 Certifications

![AWS SAA](https://img.shields.io/badge/AWS_Solutions_Architect_Associate-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AZ-104](https://img.shields.io/badge/AZ--104_Azure_Administrator-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![AZ-400](https://img.shields.io/badge/AZ--400_DevOps_Engineer_Expert-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)

---

# 📈 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Salman167&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Salman167&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" height="165" />

</div>

---

# 💭 Current Focus

```
Working on    : ACRFP guardrails and Agentic RAG quality gates
Shipping with : AKS, Helm, Argo CD, Terraform, GitHub Actions
Ask me about  : LangGraph agents, hybrid retrieval, FinOps agents, GitOps
Open to       : GenAI platform, Agentic RAG, and DevOps roles
```

---

# 📫 Let's Connect

<div align="center">

### [LinkedIn](https://www.linkedin.com/in/zaidsalman) · [Portfolio](https://salman167.github.io) · [Email](mailto:zaid.cloudsre@gmail.com)

**ACRFP · Agentic RAG · DevOps**

</div>
