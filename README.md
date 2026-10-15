# Awesome-Wealth-Management

## Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Wealth-Management

# Top Wealth Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Portfolio Tracking, Net-Worth Dashboards, Advisor Platforms, Investment Aggregation & Personal Wealth Software*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Wealth Management**. These systems aggregate accounts, track portfolios and net worth, support advisors, and help individuals or firms monitor investments over time.

**Examples** include Personal Capital (Empower), Quicken Premier, Kubera, Vyzer, Wealthfront, Betterment, Morningstar Investor, Addepar, Orion Enterprise, Envestnet, and **Ghostfolio** (`ghostfolio/ghostfolio`)—open-source wealth management software for tracking portfolios.

**Open-source emphasis**: Consumer and advisor wealth platforms are mostly commercial. Open options focus on **portfolio tracking** and privacy-first net-worth tools—**Ghostfolio**, **Wealthfolio**, **Portfolio Performance**, and related projects. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Empower (Personal Capital), Quicken, Kubera, Vyzer](https://www.empower.com/)**  
  Consumer wealth dashboards—account aggregation, net worth, retirement planning, and investment tracking.

- **[Wealthfront, Betterment](https://www.wealthfront.com/)**  
  Automated investment (robo-advisor) platforms with portfolio management and tax-aware features.

- **[Addepar, Orion, Envestnet, Morningstar](https://addepar.com/)**  
  Advisor and institutional wealth platforms—portfolio accounting, reporting, and multi-asset analytics for RIAs and enterprises.

- **[Other commercial wealth platforms](https://www.morningstar.com/)**  
  Additional brokerage-linked and advisor-technology suites.

## Open-Source GitHub Projects

- **[Ghostfolio](https://github.com/ghostfolio/ghostfolio)**  
  Open-source wealth management software—track stocks, ETFs, and other assets, measure performance, and keep portfolio data under your control.

- **[Wealthfolio](https://github.com/afadil/wealthfolio)**  
  Open privacy-first portfolio and wealth tracker—desktop and self-hosted options, local-first design, multi-asset support.

- **[Portfolio Performance](https://github.com/portfolio-performance/portfolio)**  
  Popular open-source portfolio management application (desktop)—detailed performance analysis, tax reports, and multi-currency support.

- **[Maybe Finance](https://github.com/maybe-finance/maybe)**  
  Open-source personal finance and net-worth style application (community/self-host oriented).

- **[Firefly III](https://github.com/firefly-iii/firefly-iii)**  
  Open personal finance manager—budgets and accounts; often paired with investment tracking rather than a full wealth suite.

- **[Ledger / hledger / Beancount](https://github.com/ledger/ledger)**  
  Open plain-text accounting tools—power users track investments and net worth with scripts and reports.

- **[Rotki](https://github.com/rotki/rotki)**  
  Open portfolio tracking focused on crypto and multi-asset holdings with privacy emphasis.

- **[Ghostfolio / Wealthfolio mobile & API extensions](https://github.com/ghostfolio/ghostfolio)**  
  Community and official extensions around open portfolio backends.

### Additional Strong Open-Source Options

- **Self-hosted portfolio web app**: Ghostfolio.
- **Local-first desktop**: Wealthfolio or Portfolio Performance.
- **Crypto-heavy portfolios**: Rotki.
- **Plain-text power users**: Beancount / Ledger + custom reports.
- **Composable stacks**: Broker CSVs → open tracker → optional spreadsheet or BI.
- Commercial platforms still lead for bank/broker aggregation (OFX/API), robo-advisory execution, and RIA compliance reporting.

**Frameworks for building custom systems**:  
**Ghostfolio** or **Wealthfolio** for self-hosted tracking; **Portfolio Performance** for deep desktop analysis; plain-text accounting when you want full auditability.  
Fully open wealth *tracking* is practical; automated aggregation, advice, and trade execution remain largely commercial and regulated.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- This is not financial advice. Portfolio software can misprice assets or miss corporate actions. Verify figures against broker statements. Advisor platforms may be regulated—use licensed providers where required.
- Open-source tools offer privacy and ownership but no investment advice or custody. Commercial platforms shift aggregation and support to the vendor. Neither replaces professional advice for complex tax or estate situations.

---

**Made for individual investors, family offices exploring DIY tooling, and builders of portfolio software.**  
Let's expand open wealth tracking while recognizing the aggregation depth and regulatory packaging that leading commercial wealth platforms deliver.
