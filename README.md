# William Free Hall (Free)
### *Principal Cloud & AI Architect • DevSecOps Lead • Databricks SME*
**Niceville, FL** • [LinkedIn](https://linkedin.com/in/william-free-hall) • [GitHub Enterprise](https://github.com/For-Your-Service) • Email: [whall4.wh@gmail.com](mailto:whall4.wh@gmail.com)

[![Profile Views](https://komarev.com/ghpvc/?username=FreeFades2Black&color=blueviolet&style=for-the-badge)](https://github.com/FreeFades2Black)
[![GitHub Repos](https://img.shields.io/badge/Flagship%20Portfolio-Production%20Verified-brightgreen?style=for-the-badge&logo=github&logoColor=white)](https://github.com/FreeFades2Black)
[![Databricks SME](https://img.shields.io/badge/Specialization-Databricks%20%7C%20PySpark%20%7C%20Delta%20Lake-FF3621?style=for-the-badge&logo=databricks&logoColor=white)](https://github.com/FreeFades2Black)
[![Zero-Trust DevSecOps](https://img.shields.io/badge/Security-CIS%20v1.8%20%7C%20NIST%20800--53-blue?style=for-the-badge&logo=shield&logoColor=white)](https://github.com/FreeFades2Black)

---

## 🎯 Executive Summary

Principal Cloud & AI Architect, DevSecOps Lead, and Technical Leader with over 20 years of experience transitioning high-stakes operational leadership into architecting resilient, multi-cloud enterprise lakehouse environments and zero-trust microservice meshes across **AWS, GCP, Databricks, and Kubernetes**.

Veteran U.S. Army Special Forces Intelligence Sergeant (18F) and Team Sergeant (18Z) combining elite operational discipline with deep technical execution in **high-throughput PySpark data pipelines, Delta Lake Medallion architectures, modular Terraform IaC, Istio strict mTLS zero-trust meshes, and automated CI/CD governance**.

---

## 🏛️ Flagship Enterprise Architecture Showcase

```mermaid
flowchart TD
    subgraph MultiCloudIaC ["1. Multi-Cloud IaC & GitOps (Terraform + Helm 3)"]
        TF["Terraform Modular IaC<br/>(AWS S3/KMS/IAM + Databricks + GCP)"]
        Helm["Helm 3 Chart Suite<br/>values-dev | values-staging | values-prod"]
        Istio["Istio Service Mesh<br/>Strict mTLS + Ingress Gateway + Canary 90/10"]
        TF --> Helm --> Istio
    end

    subgraph LakehouseEngine ["2. Distributed Lakehouse & Telemetry (PySpark + Delta Lake)"]
        Bronze["Bronze Layer<br/>High-Throughput Raw Ingestion (3,200+ Reqs/Sensors)"]
        Silver["Silver Layer<br/>SCD-2 Normalization & Quality Gate (0-100%)"]
        Gold["Gold Layer<br/>Longitudinal Trends & Anomaly Registers"]
        Bronze --> Silver --> Gold
    end

    subgraph RemediationEngine ["3. Defense Zero-Trust & FinOps Operator"]
        OPA["OPA / Rego Zero-Trust Gate<br/>Non-Root UID 10001 / ReadOnlyRootFS"]
        Operator["Cloud Asset Lifecycle Operator<br/>TLS Renewal & FinOps Orphan Scanner"]
        Audit["Structured Security Dossiers & Infracost PR Diff"]
        OPA --> Operator --> Audit
    end

    subgraph ControlPlanes ["4. Serverless Control Planes & Interactive Dashboards"]
        Pages["Live GitHub Pages Analytics<br/>Ghost Job Engine & UAP Radar"]
        DBX["Databricks Apps (fys-matching-app)<br/>Serverless Compute ($0 Idle Run-Rate)"]
        Streamlit["Streamlit Live Operations Gateway"]
        Gold --> Pages & DBX & Streamlit
    end
```

---

## 🚀 Pinned Flagship Projects

### 1. [⚡ Multi-Cloud Edge Telemetry & Analytical Lakehouse](https://github.com/FreeFades2Black/edge-telemetry-lakehouse)
[![CI/CD Matrix Gate](https://github.com/FreeFades2Black/edge-telemetry-lakehouse/actions/workflows/ci.yml/badge.svg)](https://github.com/FreeFades2Black/edge-telemetry-lakehouse/actions/workflows/ci.yml)
[![Nightly Synthetic Ingestion](https://github.com/FreeFades2Black/edge-telemetry-lakehouse/actions/workflows/synthetic_injector_cron.yml/badge.svg)](https://github.com/FreeFades2Black/edge-telemetry-lakehouse/actions/workflows/synthetic_injector_cron.yml)
* **Target Audience:** BMW Manufacturing, Michelin, GE Vernova, industrial IoT platform teams.
* **Core Problem:** Ingest high-throughput sensor telemetry, process micro-batches, and automate industrial anomaly detection.
* **Key Innovations:**
  * **Automated Data Quality Gate:** Evaluates schema conformance, range validity, and temporal clock drift, scoring records 0–100% and routing malformed records to a quarantine DLQ before Silver promotion.
  * **ISO 10816 Vibration Anomaly Engine:** Real-time statistical detector identifying bearing cavitation and thermal runaway across AMR robotics, curing presses, and HA gas turbines.
  * **Nightly Automated Ingestion:** Scheduled GitHub Actions workflow injecting synthetic telemetry batches nightly at 02:00 UTC.
  * **2-Minute LocalStack Sandbox:** Reproducible local execution via `make init`, `make test`, and `make run-local`.

---

### 2. [🛡️ Defense-Grade GitOps Landing Zone & DevSecOps Pipeline](https://github.com/FreeFades2Black/defense-gitops-landing-zone)
[![Gunslinger Precision CI Gate](https://github.com/FreeFades2Black/defense-gitops-landing-zone/actions/workflows/revolver-pipeline.yml/badge.svg)](https://github.com/FreeFades2Black/defense-gitops-landing-zone/actions/workflows/revolver-pipeline.yml)
[![Compliance Standards](https://img.shields.io/badge/Compliance-NIST%20800--53%20%7C%20CIS%20v1.8-blue?style=flat-square&logo=shield&logoColor=white)](https://github.com/FreeFades2Black/defense-gitops-landing-zone)
* **Target Audience:** HII Mission Technologies, Nightwing, defense industrial base contractors, enterprise FinTech.
* **Core Problem:** Provision hardened Kubernetes / ECS clusters conforming to CIS Benchmarks and DoD DevSecOps zero-trust gates.
* **Key Innovations:**
  * **Hardened Terraform Landing Zone:** KMS envelope encryption for Kubernetes secrets, private-only control plane, IMDSv2 enforced, and encrypted VPC Flow Logs.
  * **Open Policy Agent (OPA / Rego):** Zero-trust admission constraints enforcing unprivileged non-root execution (UID 10001), read-only root filesystems, and strict CPU/memory limits.
  * **The 4-Chamber Gunslinger Pipeline:** Multi-gate CI/CD workflow executing SAST, Trivy container scans, Checkov IaC audits, Infracost PR cost diffs, and automated SBOM generation.

---

### 3. [⚡ Automated Certificate & Cloud Asset Lifecycle Operator](https://github.com/FreeFades2Black/cloud-asset-lifecycle-operator)
[![Fleet Health Audit](https://github.com/FreeFades2Black/cloud-asset-lifecycle-operator/actions/workflows/scheduled_health_check.yml/badge.svg)](https://github.com/FreeFades2Black/cloud-asset-lifecycle-operator/actions/workflows/scheduled_health_check.yml)
[![Binaries](https://img.shields.io/badge/Binaries-PyInstaller%20Linux%20%2F%20Windows-amber?style=flat-square&logo=python&logoColor=white)](https://github.com/FreeFades2Black/cloud-asset-lifecycle-operator)
* **Target Audience:** Infrastructure & Platform Engineering teams (World Acceptance, TD SYNNEX).
* **Core Problem:** Continuous proactive auditing of expiring TLS certificates, orphaned cloud resources, and dormant IAM secrets.
* **Key Innovations:**
  * **Proactive TLS/SSL Discovery:** Scans ACM certificates and external endpoints, grading expiration urgency (`CRITICAL <14d`, `EXPIRING_SOON <30d`, `EXPIRED`).
  * **Orphaned Cloud Asset FinOps Scanner:** Detects unattached EBS volumes, idle Elastic IPs, and stale NAT gateways with automated monthly/annual financial waste calculation.
  * **IAM Secret Hygiene Analyzer:** Identifies access keys older than 90 days and missing MFA credentials.
  * **Cross-Platform CLI (`cert-guard`):** Single-binary distribution with Rich terminal tables and JSON/CSV dossier exports.

---

### 4. [👻 Ghost Job Intelligence & Medallion Analytics Engine](https://github.com/FreeFades2Black/ghost-job-intel-geospatial-pipeline) • [Live Dashboard](https://freefades2black.github.io/ghost-job-intel-geospatial-pipeline/)
[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-GitHub%20Pages-blue?style=flat-square&logo=githubpages&logoColor=white)](https://freefades2black.github.io/ghost-job-intel-geospatial-pipeline/)
* **Core Problem:** Uncover phantom job postings, algorithmic repost loops, and hiring velocity across 3,200+ active enterprise requisitions with a special focus on the **Greenville, SC Top 10 Tech Hub**.
* **Key Innovations:**
  * **Databricks Multi-Year Longitudinal Trends (2022–2026):** Tracks quarterly hiring velocity recovery across aerospace defense, automotive EV manufacturing, and clinical health tech.
  * **Statistical Validity Threshold ($N \ge 30$):** Enforces rigorous sample size checks before assigning risk tiers (`HEALTHY <25%`, `ELEVATED 25-44%`, `CRITICAL ≥45%`).
  * **Interactive Web Visualizer:** Requisition drilldown modals, department stale progress bars, Leaflet geospatial hub radar map, and one-click executive audit CSV exports.

---

### 5. [🛸 UAP Sightings Multi-Era Lakehouse & Geospatial Radar](https://github.com/FreeFades2Black/uap-scraper-pipeline) • [Live Dashboard](https://freefades2black.github.io/uap-scraper-pipeline/)
[![Live Intelligence Radar](https://img.shields.io/badge/Live%20Radar-GitHub%20Pages-purple?style=flat-square&logo=radar&logoColor=white)](https://freefades2black.github.io/uap-scraper-pipeline/)
* **Core Problem:** Unify fragmented aerial sensor feeds and historical sighting archives from 1480 BC to Present.
* **Key Innovations:**
  * **Chronological Timeline & Historical Context:** Compares ancient sightings with major historical milestones (Battle of Megiddo, Colosseum construction, Rosetta Stone, Roswell 1947).
  * **Lakehouse Medallion Pipeline:** Ingests 1,026+ global records with full coordinate geocoding, hover tooltips, and shape taxonomy analytics.

---

## 🛠️ Technical Competency & Tooling Matrix

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Cloud Platforms** | Amazon Web Services (AWS), Google Cloud Platform (GCP), Microsoft Azure |
| **Data & AI Lakehouse** | Databricks, Apache Spark / PySpark, Delta Lake, Unity Catalog, HuggingFace, Pandas, Parquet |
| **Infrastructure as Code** | Terraform, OpenTofu, Terragrunt, AWS CloudFormation, LocalStack |
| **Containers & Orchestration** | Kubernetes (EKS/GKE), Docker, Helm 3, ArgoCD, containerd |
| **Zero-Trust & DevSecOps** | Open Policy Agent (OPA/Rego), Checkov, Trivy, Infracost, HashiCorp Vault, AWS KMS, IAM |
| **Languages & Scripting** | Python (PySpark, FastAPI, Pydantic, Typer), SQL, Bash / Shell, PowerShell |
| **CI/CD & Observability** | GitHub Actions, Prometheus, Grafana, CloudWatch, Datadog |

---

## 📬 Connect & Collaborate

* **Email:** [whall4.wh@gmail.com](mailto:whall4.wh@gmail.com)
* **LinkedIn:** [linkedin.com/in/william-free-hall](https://linkedin.com/in/william-free-hall)
* **GitHub Enterprise:** [github.com/For-Your-Service](https://github.com/For-Your-Service)
