<div align="center">

# Harshad Khetpal

### AI Engineer — production LLM systems, MLOps, multi-cloud platform engineering

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Harshad%20Khetpal-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/harshad-khetpal-38098499/)
[![Portfolio](https://img.shields.io/badge/Portfolio-harshadkhetpal.github.io-000?style=flat-square&logo=github)](https://harshadkhetpal.github.io)
[![Email](https://img.shields.io/badge/Email-khetpalharsh%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:khetpalharsh@gmail.com)

</div>

Close to 8 years building AI and platform systems that businesses run on — currently
delivering production LLM, RAG and agent systems for enterprise clients including
Boeing, T-Mobile and BCG. Open to relocation (UK, Europe, UAE).

---

## Projects

Each of these is a small, complete, tested system — clone any of them and it runs
offline in one command, no API keys.

### [llm-gateway](https://github.com/harshadkhetpal/llm-gateway)
One API in front of many LLM providers: cheapest-first routing, response caching,
automatic failover with circuit breaking, and a cost ledger that separates spend from
spend avoided. *Why: most LLM spend is repeat prompts paid twice and easy prompts sent
to expensive models.*

### [rag-eval-gate](https://github.com/harshadkhetpal/rag-eval-gate)
Golden-set evaluation for RAG systems as a deterministic CI gate — a change that
degrades answer quality fails the build the way a failing unit test does, and names
the case that broke. *Why: the dangerous RAG failure is a fluent answer with the
load-bearing fact missing.*

### [gpu-cost-exporter](https://github.com/harshadkhetpal/gpu-cost-exporter)
Reads NVIDIA DCGM metrics and re-exports what utilisation graphs don't show: burn,
**waste** (the idle share, in money) and cost per 1k inferences, as Prometheus
metrics. *Why: a GPU at 4% utilisation is a calm green line on a dashboard and $0.97
of every $1.01 on the bill.*

Each README has a **"Design decisions worth arguing with"** section — the trade-offs
I'd defend in a review, written down.

---

## Day to day

**AI / LLM** — Python, FastAPI, LangChain, LangGraph, RAG, prompt engineering, golden-set
evaluation; Amazon Bedrock, Anthropic Claude, OpenAI; vLLM-style serving concerns:
continuous batching, KV-cache, quantization

**MLOps & Data** — MLflow, Databricks, Airflow, PySpark, Kafka, dbt, BigQuery

**Platform** — Kubernetes (AKS/EKS/GKE), Docker, Helm, Terraform, Ansible, GitOps
(ArgoCD/Flux), Azure DevOps, GitHub Actions

**Observability & Reliability** — Prometheus, Grafana, OpenTelemetry, SLOs, on-call,
incident response; GDPR / ISO 27001 audit experience

---

<div align="center">

📫 **khetpalharsh@gmail.com** · Open to AI Engineer / MLOps / Platform roles with visa sponsorship (UK · Europe · UAE)

</div>
