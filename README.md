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

Each is a small, complete, tested system — clone any of them and it runs offline in
one command, no API keys, CI green.

**AI / LLM Serving**
- [llm-gateway](https://github.com/harshadkhetpal/llm-gateway) — one API over many LLM providers: cheapest-first routing, caching, failover with circuit breaking, cost ledger
- [llm-batch-sim](https://github.com/harshadkhetpal/llm-batch-sim) — discrete-event simulation quantifying why continuous batching beats naive serving (6x throughput, 9x lower p95 on the demo workload)

**RAG & Retrieval**
- [rag-chunk-lab](https://github.com/harshadkhetpal/rag-chunk-lab) — chunking strategy vs retrieval quality, measured: BM25 from scratch, golden-set eval, the boundary-loss effect pinned as a test
- [vector-index-lab](https://github.com/harshadkhetpal/vector-index-lab) — exact and IVF vector search from first principles, with the recall-vs-probes trade-off every vector DB sells, measured

**Agents & MCP**
- [mini-mcp](https://github.com/harshadkhetpal/mini-mcp) — the Model Context Protocol tools subset from first principles: server, client and the JSON-RPC mechanics between them, in ~200 readable lines

**AI Quality & Machine Learning**
- [lora-lab](https://github.com/harshadkhetpal/lora-lab) — LoRA fine-tuning mechanics from first principles in NumPy: exact merging, frozen-base guarantees and rank trade-offs, all pinned as tests
- [rag-eval-gate](https://github.com/harshadkhetpal/rag-eval-gate) — golden-set RAG evaluation as a deterministic CI gate; a change that degrades answers fails the build and names the case
- [ml-train-gate](https://github.com/harshadkhetpal/ml-train-gate) — reproducible training (logistic regression from first principles), metric-regression gates on AUC/recall, generated model cards

**MLOps**
- [drift-watch](https://github.com/harshadkhetpal/drift-watch) — input drift detection as a pipeline gate: PSI with baseline-quantile bins + KS distance, unseen categories treated as maximum signal

**DevOps / IaC**
- [tf-plan-guard](https://github.com/harshadkhetpal/tf-plan-guard) — policy gate over `terraform plan`: blocks destroys *and replaces* of protected resources before the apply

**SRE / Observability**
- [slo-burn](https://github.com/harshadkhetpal/slo-burn) — error-budget arithmetic + generated multiwindow burn-rate Prometheus alerts (Google SRE Workbook policy, auto-scaled to your window)
- [gpu-cost-exporter](https://github.com/harshadkhetpal/gpu-cost-exporter) — NVIDIA DCGM metrics re-exported as money: burn, waste (the idle share, in dollars), cost per 1k inferences

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
