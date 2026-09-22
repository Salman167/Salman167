<div align="center">

<img src="banner.png" alt="Zaid Salman — Generative AI Engineer" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=500&size=20&pause=1100&color=E8B15A&center=true&vCenter=true&width=760&lines=Generative+AI+Engineer;Agentic+RAG+Systems;ACRFP+on+Azure+AKS;Kubernetes+%C2%B7+Terraform+%C2%B7+GitOps" alt="Focus" />

<br>

<a href="https://www.linkedin.com/in/zaidsalman">
  <img src="https://img.shields.io/badge/LinkedIn-Zaid_Salman-0c0a09?style=for-the-badge&logo=linkedin&logoColor=E8B15A&labelColor=0c0a09" alt="LinkedIn" />
</a>
<a href="https://salman167.github.io">
  <img src="https://img.shields.io/badge/Portfolio-salman167.github.io-0c0a09?style=for-the-badge&logo=github&logoColor=E8B15A&labelColor=0c0a09" alt="Portfolio" />
</a>
<a href="mailto:zaid.cloudsre@gmail.com">
  <img src="https://img.shields.io/badge/Email-zaid.cloudsre@gmail.com-0c0a09?style=for-the-badge&logo=gmail&logoColor=E8B15A&labelColor=0c0a09" alt="Email" />
</a>

<br>

![Profile views](https://komarev.com/ghpvc/?username=Salman167&color=E8B15A&style=flat-square&label=profile+views)

</div>

---

# About

I am a **Generative AI and AI Platform Engineer** with a DevOps foundation. I build production **Agentic RAG** systems and the **Agentic Cloud Reliability & FinOps Platform (ACRFP)** — multi-agent workflows that stay inside policy, approval, and observability gates.

Day to day that means LangGraph agents, FastAPI services, hybrid retrieval, and the Kubernetes, Terraform, and CI/CD path that gets those systems onto Azure and AWS.

<details open>
<summary><b>Technical snapshot</b></summary>

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

# What I'm building

### ACRFP — Agentic Cloud Reliability & FinOps Platform

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

### Enterprise Agentic RAG Platform

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

### DevOps & cloud delivery

The same platforms are shipped with containers, GitOps, and infrastructure as code.

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

# Tech stack

### Agentic RAG & LLM engineering

![Python](https://img.shields.io/badge/Python-0c0a09?style=flat-square&logo=python&logoColor=E8B15A)
![FastAPI](https://img.shields.io/badge/FastAPI-0c0a09?style=flat-square&logo=fastapi&logoColor=E8B15A)
![LangChain](https://img.shields.io/badge/LangChain-0c0a09?style=flat-square&logo=langchain&logoColor=E8B15A)
![LangGraph](https://img.shields.io/badge/LangGraph-0c0a09?style=flat-square&logoColor=E8B15A)
![RAG](https://img.shields.io/badge/Agentic_RAG-0c0a09?style=flat-square&logoColor=E8B15A)
![Qdrant](https://img.shields.io/badge/Qdrant-0c0a09?style=flat-square&logoColor=E8B15A)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0c0a09?style=flat-square&logo=microsoft-azure&logoColor=E8B15A)
![RAGAS](https://img.shields.io/badge/RAGAS-0c0a09?style=flat-square&logoColor=E8B15A)
![Langfuse](https://img.shields.io/badge/Langfuse-0c0a09?style=flat-square&logoColor=E8B15A)

### Data & services

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0c0a09?style=flat-square&logo=postgresql&logoColor=E8B15A)
![Redis](https://img.shields.io/badge/Redis-0c0a09?style=flat-square&logo=redis&logoColor=E8B15A)
![MinIO](https://img.shields.io/badge/MinIO-0c0a09?style=flat-square&logoColor=E8B15A)
![Pydantic](https://img.shields.io/badge/Pydantic-0c0a09?style=flat-square&logo=pydantic&logoColor=E8B15A)

### DevOps & cloud

![Azure](https://img.shields.io/badge/Azure-0c0a09?style=flat-square&logo=microsoft-azure&logoColor=E8B15A)
![AWS](https://img.shields.io/badge/AWS-0c0a09?style=flat-square&logo=amazon-aws&logoColor=E8B15A)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0c0a09?style=flat-square&logo=kubernetes&logoColor=E8B15A)
![Docker](https://img.shields.io/badge/Docker-0c0a09?style=flat-square&logo=docker&logoColor=E8B15A)
![Helm](https://img.shields.io/badge/Helm-0c0a09?style=flat-square&logo=helm&logoColor=E8B15A)
![Terraform](https://img.shields.io/badge/Terraform-0c0a09?style=flat-square&logo=terraform&logoColor=E8B15A)
![Ansible](https://img.shields.io/badge/Ansible-0c0a09?style=flat-square&logo=ansible&logoColor=E8B15A)
![Argo CD](https://img.shields.io/badge/Argo_CD-0c0a09?style=flat-square&logo=argo&logoColor=E8B15A)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0c0a09?style=flat-square&logo=github-actions&logoColor=E8B15A)
![Jenkins](https://img.shields.io/badge/Jenkins-0c0a09?style=flat-square&logo=jenkins&logoColor=E8B15A)
![Prometheus](https://img.shields.io/badge/Prometheus-0c0a09?style=flat-square&logo=prometheus&logoColor=E8B15A)
![Grafana](https://img.shields.io/badge/Grafana-0c0a09?style=flat-square&logo=grafana&logoColor=E8B15A)
![Linux](https://img.shields.io/badge/Linux-0c0a09?style=flat-square&logo=linux&logoColor=E8B15A)

### Certifications

![AWS SAA](https://img.shields.io/badge/AWS_Solutions_Architect_Associate-0c0a09?style=flat-square&logo=amazon-aws&logoColor=E8B15A)
![AZ-104](https://img.shields.io/badge/AZ--104_Azure_Administrator-0c0a09?style=flat-square&logo=microsoft-azure&logoColor=E8B15A)
![AZ-400](https://img.shields.io/badge/AZ--400_DevOps_Engineer_Expert-0c0a09?style=flat-square&logo=microsoft-azure&logoColor=E8B15A)

---

# GitHub analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Salman167&show_icons=true&hide_border=true&rank_icon=github&bg_color=0c0a09&title_color=E8B15A&text_color=E7E5E4&icon_color=E8B15A" alt="GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Salman167&layout=compact&hide_border=true&langs_count=8&bg_color=0c0a09&title_color=E8B15A&text_color=E7E5E4" alt="Top languages" height="165" />

</div>

---

# Current focus

```
Working on    : ACRFP guardrails and Agentic RAG quality gates
Shipping with : AKS, Helm, Argo CD, Terraform, GitHub Actions
Ask me about  : LangGraph agents, hybrid retrieval, FinOps agents, GitOps
Open to       : GenAI platform, Agentic RAG, and DevOps roles
```

---

<div align="center">

### [LinkedIn](https://www.linkedin.com/in/zaidsalman) · [Portfolio](https://salman167.github.io) · [Email](mailto:zaid.cloudsre@gmail.com)

**ACRFP · Agentic RAG · DevOps**

</div>
