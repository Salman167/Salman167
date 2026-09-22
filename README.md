<div align="center">

<img src="banner.png" alt="Zaid Salman — Idea. Design. Implement. Deploy. Rebuild." width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=500&size=20&pause=1100&color=E8B15A&center=true&vCenter=true&width=720&lines=Agentic+RAG+%C2%B7+ACRFP+%C2%B7+DevOps;Bengaluru+%C2%B7+Open+to+India%2C+UAE%2C+KSA%2C+Europe;LangGraph+%C2%B7+FastAPI+%C2%B7+Kubernetes" alt="Agentic RAG, ACRFP, and DevOps" />

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

# Vision and mission

**Vision.** Agentic systems that run in production and stay inside policy, approval, and observability.

**Mission.** Take each idea through design, implementation, deploy, and rebuild, then ship Agentic RAG and ACRFP on Azure and AWS.

---

# Tech stack

### Agentic RAG & LLM engineering

![Python](https://img.shields.io/badge/Python-0c0a09?style=flat-square&logo=python&logoColor=3776AB)
![FastAPI](https://img.shields.io/badge/FastAPI-0c0a09?style=flat-square&logo=fastapi&logoColor=009688)
![LangChain](https://img.shields.io/badge/LangChain-0c0a09?style=flat-square&logo=langchain&logoColor=E7E5E4)
![LangGraph](https://img.shields.io/badge/LangGraph-0c0a09?style=flat-square&logoColor=E8B15A)
![RAG](https://img.shields.io/badge/Agentic_RAG-0c0a09?style=flat-square&logoColor=E8B15A)
![Qdrant](https://img.shields.io/badge/Qdrant-0c0a09?style=flat-square&logoColor=DC244C)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0c0a09?style=flat-square&logo=microsoft-azure&logoColor=0078D4)
![RAGAS](https://img.shields.io/badge/RAGAS-0c0a09?style=flat-square&logoColor=A78BFA)
![Langfuse](https://img.shields.io/badge/Langfuse-0c0a09?style=flat-square&logoColor=FB7185)

### Data & services

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0c0a09?style=flat-square&logo=postgresql&logoColor=4169E1)
![Redis](https://img.shields.io/badge/Redis-0c0a09?style=flat-square&logo=redis&logoColor=FF4438)
![MinIO](https://img.shields.io/badge/MinIO-0c0a09?style=flat-square&logoColor=C72E49)
![Pydantic](https://img.shields.io/badge/Pydantic-0c0a09?style=flat-square&logo=pydantic&logoColor=E92063)

### DevOps & cloud

![Azure](https://img.shields.io/badge/Azure-0c0a09?style=flat-square&logo=microsoft-azure&logoColor=0078D4)
![AWS](https://img.shields.io/badge/AWS-0c0a09?style=flat-square&logo=amazon-aws&logoColor=FF9900)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0c0a09?style=flat-square&logo=kubernetes&logoColor=326CE5)
![Docker](https://img.shields.io/badge/Docker-0c0a09?style=flat-square&logo=docker&logoColor=2496ED)
![Helm](https://img.shields.io/badge/Helm-0c0a09?style=flat-square&logo=helm&logoColor=A5B4FC)
![Terraform](https://img.shields.io/badge/Terraform-0c0a09?style=flat-square&logo=terraform&logoColor=844FBA)
![Ansible](https://img.shields.io/badge/Ansible-0c0a09?style=flat-square&logo=ansible&logoColor=EE0000)
![Argo CD](https://img.shields.io/badge/Argo_CD-0c0a09?style=flat-square&logo=argo&logoColor=EF7B4D)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0c0a09?style=flat-square&logo=github-actions&logoColor=2088FF)
![Jenkins](https://img.shields.io/badge/Jenkins-0c0a09?style=flat-square&logo=jenkins&logoColor=D24939)
![Prometheus](https://img.shields.io/badge/Prometheus-0c0a09?style=flat-square&logo=prometheus&logoColor=E6522C)
![Grafana](https://img.shields.io/badge/Grafana-0c0a09?style=flat-square&logo=grafana&logoColor=F46800)
![Linux](https://img.shields.io/badge/Linux-0c0a09?style=flat-square&logo=linux&logoColor=FCC624)

### Certifications

<a href="https://www.linkedin.com/in/zaidsalman/details/certifications/">
  <img src="https://img.shields.io/badge/AWS_Solutions_Architect_Associate-0c0a09?style=flat-square&logo=amazon-aws&logoColor=E8B15A" alt="AWS Solutions Architect Associate" />
</a>
<a href="https://www.linkedin.com/in/zaidsalman/details/certifications/">
  <img src="https://img.shields.io/badge/AZ--104_Azure_Administrator-0c0a09?style=flat-square&logo=microsoft-azure&logoColor=E8B15A" alt="AZ-104 Azure Administrator" />
</a>
<a href="https://www.linkedin.com/in/zaidsalman/details/certifications/">
  <img src="https://img.shields.io/badge/AZ--400_DevOps_Engineer_Expert-0c0a09?style=flat-square&logo=microsoft-azure&logoColor=E8B15A" alt="AZ-400 DevOps Engineer Expert" />
</a>

[View certificates on LinkedIn](https://www.linkedin.com/in/zaidsalman/details/certifications/)

---

# GitHub analytics

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Salman167&theme=github_dark" alt="GitHub stats" height="180" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Salman167&theme=github_dark" alt="Top languages" height="180" />

<br>

<img src="https://streak-stats.demolab.com?user=Salman167&hide_border=true&background=0C0A09&stroke=3F3428&ring=E8B15A&fire=E8B15A&currStreakNum=FAF7F2&sideNums=FAF7F2&currStreakLabel=E8B15A&sideLabels=E7E5E4&dates=A8A29E" alt="GitHub contribution streak" />

<br>

<img src="https://ghchart.rshah.org/E8B15A/Salman167" alt="GitHub contribution graph" width="100%" />

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

# Fun facts

- 🎤 I sing once I know the song.
- 💃 Dancing is how I leave the day behind.
- 🍳 I cook on weeknights. It is how I switch off.
- 🤝 I like making new friends and spending real time with them.
- 🥾 Trekking is where my head gets quiet.
- 💪 Calisthenics keeps the week steady.

---

<div align="center">

**ACRFP · Agentic RAG · DevOps**

</div>
