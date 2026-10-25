<!-- 
  ╔══════════════════════════════════════════════════════════════════════════════╗
  ║                                                                            ║
  ║   🏗️  RAHUL GOYAL — Enterprise Cloud Architect & DevSecOps Strategist      ║
  ║   📐  14+ Years | Azure | Terraform | Landing Zones | Cloud Migrations     ║
  ║                                                                            ║
  ╚══════════════════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<!-- ═══════════════════════ HERO BANNER ═══════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a3a5c,100:0078d4&height=220&section=header&text=Rahul%20Goyal&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=Enterprise%20Cloud%20Architect%20%7C%20DevSecOps%20Strategist%20%7C%2014%2B%20Years&descSize=16&descAlignY=52&descAlign=50" width="100%" />

<!-- ═══════════════════════ TYPING ANIMATION ═══════════════════════ -->

<br/>

<a href="https://github.com/rahulgoyaldevops">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3500&pause=1200&color=0078D4&center=true&vCenter=true&multiline=true&repeat=true&width=750&height=80&lines=%F0%9F%8F%97%EF%B8%8F+I+don't+just+build+infrastructure+%E2%80%94+I+architect+enterprises;%E2%98%81%EF%B8%8F+From+Landing+Zones+to+100%2B+App+Migrations+at+Scale" alt="Typing SVG" />
</a>

<br/>

<!-- ═══════════════════════ QUICK IDENTITY ═══════════════════════ -->

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                                                                             │
│   Role        ►  Enterprise Cloud Architect & Technical Account Manager     │
│   Experience  ►  14+ Years  ·  Infrastructure + Application Architecture   │
│   Domains     ►  Cloud Migrations · Landing Zones · DevSecOps · FinOps     │
│   Scale       ►  100+ Application Migrations · Multi-Subscription Estates  │
│   Philosophy  ►  Scalable · Secure · Governed · Cost-Optimised · Portable  │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

<!-- ═══════════════════════ IMPACT BADGES ═══════════════════════ -->

![Azure](https://img.shields.io/badge/Azure-Enterprise_Architect-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-Landing_Zones-623CE4?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-AKS_Production-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![DevSecOps](https://img.shields.io/badge/DevSecOps-OIDC_Pipelines-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![FinOps](https://img.shields.io/badge/FinOps-Cost_Optimization-00C853?style=flat-square&logo=cashapp&logoColor=white)
![AI/ML](https://img.shields.io/badge/AI%2FDevOps-AIOps_&_RAG-FF6F00?style=flat-square&logo=openai&logoColor=white)

</div>

---

## 🧠 The Architect's Mindset

> *Most engineers deploy resources. I design **enterprises**.*
> 
> *When a CTO asks to "migrate 100+ applications across dev, UAT, and production into Azure with multi-subscription governance" — I don't just write Terraform. I engineer the tenant hierarchy, the management group structure, the hub-spoke networking, policy guardrails, the RBAC model, the FinOps framework, DR resilience, monitoring observability, trunk-based branching, vendor SOWs, and team upskilling. Then I build it. Then I govern it.*

<br/>

<div align="center">

```mermaid
graph LR
    A["🎯 Strategy<br/><i>CAF: Plan, Ready, Adopt</i>"] --> B["🏗️ Foundation<br/><i>Landing Zone + Governance</i>"]
    B --> C["🔄 Migration<br/><i>100+ Apps at Scale</i>"]
    C --> D["🛡️ Govern<br/><i>Policy · RBAC · Compliance</i>"]
    D --> E["📊 Optimize<br/><i>FinOps · Monitor · Iterate</i>"]
    E -->|"Continuous"| B

    style A fill:#1a3a5c,stroke:#0078d4,color:#fff
    style B fill:#1a3a5c,stroke:#0078d4,color:#fff
    style C fill:#1a3a5c,stroke:#0078d4,color:#fff
    style D fill:#1a3a5c,stroke:#0078d4,color:#fff
    style E fill:#1a3a5c,stroke:#0078d4,color:#fff
```

</div>

---

## 🏛️ What I Actually Architect (Not Just Buzzwords)

<table>
<tr>
<td width="50%" valign="top">

### ☁️ Cloud Foundation & Landing Zone
```
Microsoft Entra ID
  └── Tenant Root Group
       ├── Platform MG
       │    ├── Identity Subscription
       │    ├── Management Subscription
       │    └── Connectivity Subscription
       ├── Landing Zone MG
       │    ├── Corp (Online) MG
       │    └── SAP / Specialized MG
       ├── Sandbox MG
       └── Decommissioned MG
```
- CAF-driven strategy: **Plan → Ready → Adopt → Govern → Secure → Manage**
- Subscription boundaries, policy initiatives, RBAC group formation
- Subscription onboarding/offboarding automation
- Policy exemptions with justification workflows

</td>
<td width="50%" valign="top">

### 🌐 Hub-Spoke Network Architecture
```
   ┌────────────────────────────┐
   │        HUB VNET            │
   │  ┌──────┐  ┌───────────┐  │
   │  │Azure │  │ VPN GW /  │  │
   │  │ FW   │  │ExpressRte │  │
   │  └──┬───┘  └─────┬─────┘  │
   │     │            │         │
   │  ┌──┴────────────┴──┐     │
   │  │  Private DNS Zones│     │
   │  └──────────────────┘     │
   └────────┬───────┬──────────┘
            │       │
    ┌───────┴─┐ ┌───┴───────┐
    │ Spoke 1 │ │  Spoke N  │
    │ (Prod)  │ │  (UAT)    │
    │ UDR→FW  │ │  UDR→FW   │
    └─────────┘ └───────────┘
```
- IP address management & CIDR planning
- On-premises CIDR assessment & integration
- Centralized inspection & controlled egress
- Private endpoints & DNS resolution chain
- UDR firewall rules & NSG hardening

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔐 Security — Defense in Depth
| Layer | Controls |
|:--|:--|
| **Identity** | Entra ID, Conditional Access, PIM, MFA |
| **Network** | NSG, Azure Firewall, Private Link, WAF |
| **Governance** | Azure Policy, Initiatives, Defender for Cloud |
| **Compute** | Defender for Servers, JIT Access, Bastion |
| **Data** | Encryption at rest/transit, Key Vault, CMK |

</td>
<td width="50%" valign="top">

### 💰 FinOps & Cost Intelligence
```
 FinOps Lifecycle
 ┌──────────┐    ┌──────────┐    ┌──────────┐
 │ INFORM   │───▶│ OPTIMIZE │───▶│ OPERATE  │
 │          │    │          │    │          │
 │ Cost     │    │ Right-   │    │ Reserved │
 │ Visibility│   │ Sizing   │    │ Capacity │
 │ Tagging  │    │ Idle     │    │ Auto     │
 │ Budgets  │    │ Resources│    │ Start/   │
 │ Alerts   │    │ Disk     │    │ Stop     │
 └──────────┘    │ Cleanup  │    │ Retention│
                 └──────────┘    │ Tuning   │
                                 └──────────┘
```

</td>
</tr>
</table>

---

## ⚙️ Terraform & DevSecOps Pipeline Architecture

<div align="center">

```mermaid
graph TD
    DEV["👨‍💻 Developer Push<br/><i>Feature Branch</i>"] --> PR["📋 Pull Request<br/><i>Mandatory · Max Reviewers</i>"]
    PR --> VALIDATE["✅ Validate & Lint<br/><i>terraform validate<br/>tflint · checkov</i>"]
    VALIDATE --> PLAN["📐 Terraform Plan<br/><i>Cost Estimation<br/>Drift Detection</i>"]
    PLAN --> SEC["🔒 Security Scan<br/><i>Secret Scanning<br/>SAST · Policy Check</i>"]
    SEC --> APPROVE["👀 Manual Approval<br/><i>Code Owners Review</i>"]
    APPROVE --> APPLY["🚀 Terraform Apply<br/><i>State: Encrypted · Least Privilege</i>"]
    APPLY --> MONITOR["📊 Post-Deploy Verify<br/><i>Smoke Tests · Monitoring</i>"]
    MONITOR -->|"Rollback if needed"| ROLLBACK["⏪ Rollback Template"]

    style DEV fill:#1a3a5c,stroke:#0078d4,color:#fff
    style PR fill:#1a3a5c,stroke:#0078d4,color:#fff
    style VALIDATE fill:#234e6e,stroke:#0078d4,color:#fff
    style PLAN fill:#234e6e,stroke:#0078d4,color:#fff
    style SEC fill:#c62828,stroke:#ff5252,color:#fff
    style APPROVE fill:#f57f17,stroke:#ffc107,color:#fff
    style APPLY fill:#2e7d32,stroke:#66bb6a,color:#fff
    style MONITOR fill:#2e7d32,stroke:#66bb6a,color:#fff
    style ROLLBACK fill:#616161,stroke:#9e9e9e,color:#fff
```

</div>

<details>
<summary><b>🔍 My Terraform & Pipeline Best Practices (Click to Expand)</b></summary>
<br/>

| Area | Practice |
|:--|:--|
| **State Management** | Remote state (Azure Blob), least privilege access, encryption at rest, state locking |
| **Module Design** | DRY reusable modules, semantic versioning, input validation, output contracts |
| **Branching** | Trunk-based strategy, short-lived feature branches, no delete on main, CODEOWNERS |
| **Pipeline Templates** | Validate → Test → Build → Deploy → Apply → Rollback (reusable YAML templates) |
| **Quality Gates** | Linting (tflint), security scan (checkov/tfsec), cost estimation (infracost), policy (OPA/Sentinel) |
| **Drift Detection** | Scheduled `terraform plan` via pipelines, drift alerts to Slack/Teams |
| **Secrets** | Zero hardcoded credentials. Managed Identity & Azure Key Vault integrated natively |
| **Parallel Jobs** | Parallelized plan/apply across independent modules for execution velocity |

</details>

---

## 🔄 Cloud Migrations — Battle-Tested at Scale

<div align="center">

```
┌──────────────────────────── MIGRATION FACTORY ──────────────────────────────┐
│                                                                             │
│  ┌──────────┐   ┌──────────┐   ┌──────────┐   ┌──────────┐   ┌──────────┐ │
│  │DISCOVERY │──▶│ASSESSMENT│──▶│READINESS │──▶│ MIGRATE  │──▶│HYPERCARE │ │
│  │          │   │          │   │          │   │          │   │          │  │
│  │ App      │   │ 6R       │   │ Pre-     │   │ Cutover  │   │ Post-    │  │
│  │ Inventory│   │ Strategy │   │ Checklist│   │ Windows  │   │ Checklist│  │
│  │ Dependency│  │ TCO/ROI  │   │ Landing  │   │ Parallel │   │ Sign-off │  │
│  │ Mapping  │   │ Analysis │   │ Zone     │   │ Run      │   │ KT       │  │
│  │          │   │          │   │ Ready    │   │          │   │          │  │
│  └──────────┘   └──────────┘   └──────────┘   └──────────┘   └──────────┘ │
│                                                                             │
│  ► 100+ Applications · Dev/UAT/Prod · Multi-Subscription · On-Prem → Cloud │
│  ► Pre, During & Post migration checklists for zero-surprise cutovers      │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

</div>

---

## 🎯 Beyond Technology — Enterprise Leadership

> *A 14-year career isn't just about code. It's about leading teams, vendor governance, winning multimillion-dollar proposals, and owning delivery end-to-end.*

<table>
<tr>
<td width="33%" align="center">

### 📋 Vendor & Delivery
- Scope, Deliverables, Acceptance Criteria
- Sprint planning & dependency mapping
- SOW review & commercial negotiations
- RFP/RFI response & technical evaluation
- Escalation matrix design
- Payment milestone tracking
- Weekly reviews & retro governance

</td>
<td width="33%" align="center">

### 👥 Team & Transitions
- Team upskilling strategy & KT sessions
- Senior-level technical interview panels
- RACI matrix & documentation handover
- Cutover transition planning & execution
- Service ownership & operational excellence
- SOP creation & process governance
- Cross-functional stakeholder alignment

</td>
<td width="33%" align="center">

### 🏆 Service Ownership
- End-to-end cloud platform ownership
- Pre-sales & enterprise architecture proposals
- High-impact POC design & execution
- Estimation & capacity planning
- Architecture review boards (ARB)
- Audit & compliance defense
- Executive C-level stakeholder management

</td>
</tr>
</table>

---

## 🤖 AI-Augmented Engineering

> *Every senior architect must master AI: not just generic chat, but integrating GenAI and intelligent automation into production workflows.*

| AI Capability | How I Apply It |
|:--|:--|
| **AI-Assisted IaC** | GitHub Copilot & LLMs for Terraform module generation and static analysis |
| **AIOps & Observability** | Anomaly detection in Azure Monitor, log anomaly clustering, proactive capacity prediction |
| **GenAI Documentation** | Automated runbook updates, Architecture Decision Records (ADRs), post-mortem generation |
| **AI in Security** | Microsoft Copilot for Security, prompt-driven incident correlation, SIEM telemetry enrichment |
| **Enterprise Azure OpenAI** | Architecture of secure Azure OpenAI private endpoints, RAG pipelines, Vector Search |

---

## 📌 Featured Production Architectures & Repositories

| Repository | Focus Area | Tech Stack |
| :--- | :--- | :--- |
| **[tf-monolithic-landing-zone](https://github.com/rahulgoyaldevops/tf-monolithic-landing-zone)** | Enterprise Azure Landing Zone with parent/child modules, Key Vault integration & Infracost | `Terraform`, `AzureRM`, `Key Vault`, `Infracost` |
| **[terraform-github-actions](https://github.com/rahulgoyaldevops/terraform-github-actions)** | Production Terraform CI/CD pipeline using GitHub Actions with passwordless Azure OIDC | `GitHub Actions`, `Terraform`, `Azure OIDC`, `Security` |
| **[azure-devsecops-pipeline-templates](https://github.com/rahulgoyaldevops/azure-devsecops-pipeline-templates)** | Enterprise pipeline templates for Azure DevOps: Validate, Checkov, TFLint & Drift Detection | `Azure DevOps`, `Checkov`, `TFLint`, `Gitleaks` |
| **[cloud-migration-playbook](https://github.com/rahulgoyaldevops/cloud-migration-playbook)** | End-to-end 100+ app migration factory: 6R decision trees, pre/post checklists & cutovers | `Migration Factory`, `6R Strategy`, `Checklists`, `Governance` |
| **[azure-finops-governance-toolkit](https://github.com/rahulgoyaldevops/azure-finops-governance-toolkit)** | Cost governance toolkit: automated idle VM/disk detection & Terraform tagging policies | `FinOps`, `PowerShell`, `Azure Policy`, `Cost Management` |
| **[kubernetes-production-aks](https://github.com/rahulgoyaldevops/kubernetes-production-aks)** | Multi-zone production AKS cluster architecture: Calico CNI, Azure AD RBAC, Key Vault CSI | `Kubernetes`, `AKS`, `Calico`, `Terraform`, `ArgoCD` |

---

## 🛠️ Technology Arsenal

<div align="center">

**Cloud Platforms & Architecture**<br/>
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

**Infrastructure as Code & Automation**<br/>
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Bicep](https://img.shields.io/badge/Bicep-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Containers & Orchestration**<br/>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AKS](https://img.shields.io/badge/AKS-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)

**CI/CD & DevSecOps**<br/>
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Checkov](https://img.shields.io/badge/Checkov-Security-FF5722?style=for-the-badge)

**Observability & FinOps**<br/>
![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![FinOps](https://img.shields.io/badge/FinOps-00C853?style=for-the-badge)

</div>

---

## 📈 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rahulgoyaldevops&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=0078d4&icon_color=0078d4&text_color=c9d1d9" width="48%" />
<img src="https://nirzak-streak-stats.vercel.app/?user=rahulgoyaldevops&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=0078d4&ring=0078d4&fire=ff6f00&currStreakLabel=0078d4" width="48%" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rahulgoyaldevops&theme=github-compact&hide_border=true&bg_color=0d1117&color=0078d4&line=0078d4&point=ff6f00&area=true&area_color=0078d4" width="98%" />

</div>

---

## 🤝 Let's Connect

<div align="center">

<a href="https://rahulgoyal.co.in">
  <img src="https://img.shields.io/badge/Portfolio-rahulgoyal.co.in-0078D4?style=for-the-badge&logo=googlechrome&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/rahulgoyaldevops/">
  <img src="https://img.shields.io/badge/LinkedIn-Rahul_Goyal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://medium.com/@rahulgec04">
  <img src="https://img.shields.io/badge/Medium-@rahulgec04-12100E?style=for-the-badge&logo=medium&logoColor=white" />
</a>
<a href="mailto:rahulgoyal.devops@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</div>

<br/>

<div align="center">

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                                                                         ║
║   "I don't build servers. I architect enterprises that scale,           ║
║    self-heal, self-govern, and survive their architects leaving."        ║
║                                                                         ║
║                                          — Rahul Goyal                  ║
║                                                                         ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

</div>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=rahulgoyaldevops&style=flat-square&color=0078d4&label=Profile+Views)
![GitHub Followers](https://img.shields.io/github/followers/rahulgoyaldevops?style=flat-square&color=0078d4&label=Followers)
![GitHub Stars](https://img.shields.io/github/stars/rahulgoyaldevops?style=flat-square&color=0078d4&label=Total+Stars)

</div>

<!-- ═══════════════════════ FOOTER WAVE ═══════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0078d4,50:1a3a5c,100:0d1117&height=120&section=footer" width="100%" />