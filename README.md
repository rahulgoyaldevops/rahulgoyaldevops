<div align="center">

<!-- HEADER WAVE BANNER (NO UNESCAPED AMPERSAND IN DESC TO PREVENT XML PARSE ERROR) -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,35:102a45,70:005a9e,100:0078d4&height=220&section=header&text=Rahul%20Goyal&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=Senior%20DevOps%20and%20Cloud%20Engineer%20%7C%2014%2B%20Years%20Experience&descSize=16&descAlignY=52&descAlign=50" width="100%" />

<br/>

<!-- DYNAMIC TYPING HEADLINE (SINGLE-LINE SEQUENTIAL CYCLING - PROPERLY SIZED) -->
<p align="center">
  <a href="https://github.com/rahulgoyaldevops">
    <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&duration=3000&pause=1400&color=0078D4&center=true&vCenter=true&repeat=true&width=720&height=42&lines=Senior+DevOps+and+Cloud+Engineer+%7C+14%2B+Years;Infrastructure+and+Platform+Lead;Automating+Enterprise+Landing+Zones+%7C+DevSecOps;Leading+100%2B+App+Migrations+%7C+FinOps+Governance;Kubernetes+(AKS)+%7C+Policy+as+Code+%7C+Zero-Trust" alt="Typing Headline" />
  </a>
</p>

<!-- ACTIONABLE CONNECT BUTTONS -->
<p align="center">
  <a href="https://www.linkedin.com/in/rahulgoyaldevops/">
    <img src="https://img.shields.io/badge/LinkedIn-Rahul_Goyal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;&nbsp;
  <a href="https://rahulgoyal.co.in">
    <img src="https://img.shields.io/badge/Portfolio-rahulgoyal.co.in-0078D4?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
  &nbsp;&nbsp;
  <a href="https://medium.com/@rahulgec04">
    <img src="https://img.shields.io/badge/Medium-Articles-12100E?style=for-the-badge&logo=medium&logoColor=white" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:rahulgoyal.devops@gmail.com">
    <img src="https://img.shields.io/badge/Email-Get_In_Touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<br/>

<!-- EXECUTIVE IMPACT METRICS -->
<table>
  <tr>
    <td align="center" width="25%">
      <h3>⏱️ 14+ Years</h3>
      <sub><b>Enterprise Experience</b><br/>Cloud & Platform Engineering</sub>
    </td>
    <td align="center" width="25%">
      <h3>🚀 100+ Workloads</h3>
      <sub><b>Production Migrations</b><br/>Multi-Subscription Scale</sub>
    </td>
    <td align="center" width="25%">
      <h3>💰 30%+ FinOps</h3>
      <sub><b>Cloud Cost Reduction</b><br/>Resource Optimization</sub>
    </td>
    <td align="center" width="25%">
      <h3>🔐 Zero-Trust</h3>
      <sub><b>DevSecOps Pipelines</b><br/>OIDC & Policy as Code</sub>
    </td>
  </tr>
</table>

</div>

---

## 💼 Executive Profile

Senior DevOps & Cloud Engineer with **14+ years of cross-functional experience** leading cloud infrastructure automation, platform reliability, large-scale migrations, and enterprise DevSecOps. 

- **Enterprise Cloud Delivery:** Proven track record leading **100+ application migrations** across Dev, UAT, and Production from on-premises datacenters into governed, multi-subscription Azure and hybrid cloud environments.
- **Infrastructure as Code (IaC) & Platform Foundations:** Hands-on specialist in modular **Terraform Landing Zones**, Azure Cloud Adoption Framework (CAF), Hub-and-Spoke networking, and policy-driven compliance.
- **Technical Leadership & Ownership:** Extensive experience driving vendor SOW evaluations, technical RFP proposals, RACI transition frameworks, architecture review boards, and upskilling engineering teams.

---

## 🏛️ Core Engineering Domains & Responsibilities

<details open>
<summary><b>1. ☁️ Cloud Architecture & Enterprise Landing Zones</b></summary>
<br/>

- **Cloud Adoption Framework (CAF):** Implementing end-to-end strategy across **Plan, Ready, Adopt, Govern, Secure, and Manage**.
- **Tenant & Management Group Hierarchy:**
  - Multi-tier structure: *Root Group ➔ Platform MG (Identity, Connectivity, Management) ➔ Landing Zone MG (Corp/Online, Specialized/SAP) ➔ Sandbox & Decommissioned MGs*.
  - Subscription boundaries, automated onboarding/offboarding, and enterprise RBAC assignments.
- **Hub-and-Spoke Networking:**
  - Centralized ingress/egress inspection via Azure Firewall and Network Virtual Appliances (NVAs).
  - Transit routing with User Defined Routes (UDR), Network Security Groups (NSGs), and Private DNS Zone resolution chains.
  - Hybrid connectivity via ExpressRoute and Site-to-Site VPN Gateways with on-premises CIDR alignment.

</details>

<details open>
<summary><b>2. ⚡ DevSecOps, CI/CD & Infrastructure as Code (IaC)</b></summary>
<br/>

- **Terraform Enterprise Standards:**
  - Modular, DRY design using parent-child module architecture and semantic versioning.
  - Remote encrypted state with blob storage locking and least-privilege RBAC.
  - Automated drift detection pipelines with proactive Slack/Teams alert notifications.
- **Pipeline Engineering (Azure DevOps & GitHub Actions):**
  - **Passwordless Authentication:** Azure OIDC Workload Identity Federation (eliminating static client secrets).
  - **Quality & Security Gates:** Multi-stage validation (`terraform fmt`, `tflint`, `checkov`, `tfsec`, `gitleaks`, `infracost`).
  - **Release Strategy:** Trunk-based branching, mandatory PR reviews (min 2 reviewers), CODEOWNERS enforcement, and automated rollback workflows.

</details>

<details open>
<summary><b>3. 🔄 Large-Scale Cloud Migrations (100+ Applications)</b></summary>
<br/>

- **Migration Factory Methodology:**
  - **Discovery & Assessment:** CMDB analysis, automated dependency mapping, workload profiling, and 6R strategy rationalization (*Rehost, Replatform, Refactor, Repurchase, Retire, Retain*).
  - **Readiness Checklists:** Pre-migration validation covering subnet CIDRs, ExpressRoute latency, firewall rules, and backup verification.
  - **Execution & Cutover:** Parallel runs, continuous data replication, DNS TTL tuning, cutover runbooks, and rollback SLAs.
  - **Hypercare & Transition:** Performance baseline audits, monitoring alerts, stakeholder sign-offs, and operations handover.

</details>

<details open>
<summary><b>4. 🛡️ Security, Governance, FinOps & Resilience</b></summary>
<br/>

- **Defense-in-Depth Security:**
  - Identity & Access: Microsoft Entra ID, Conditional Access, PIM (Privileged Identity Management), and Azure RBAC.
  - Data & Compute: Azure Key Vault secrets/keys, customer-managed keys (CMK), Defender for Cloud, and JIT VM access.
- **FinOps & Cost Governance:**
  - Automated detection and remediation of idle VMs, unattached managed disks, and orphaned public IPs.
  - Tagging compliance enforcement via Azure Policy initiatives to enable granular department showback/chargeback.
  - Reserved capacity planning, VM auto start/stop scheduling, and Azure Monitor log ingestion tuning.
- **High Availability & Disaster Recovery (DR):**
  - Storage redundancy strategies (LRS, ZRS, GRS) aligned with business RTO/RPO targets.
  - Virtual Machine Scale Sets (VMSS) with multi-zone distribution and automated health-probe self-healing.

</details>

<details open>
<summary><b>5. 👥 Technical Leadership, Vendor & Transition Governance</b></summary>
<br/>

- **Vendor & Commercial Management:** Authoring Statement of Work (SOW), defining deliverables and acceptance criteria, evaluating RFP/RFI technical matrices, and tracking payment milestones.
- **Delivery Ownership:** Leading sprint retrospectives, escalation matrix design, cross-functional issue resolution, and executive reporting.
- **Transitions & Knowledge Transfer:** Building comprehensive SOP documentation, RACI handover matrices, and leading team upskilling sessions.

</details>

<details open>
<summary><b>6. 🤖 Modern AI-Augmented Engineering</b></summary>
<br/>

- **AIOps & Predictive Monitoring:** Intelligent anomaly detection in telemetry pipelines and AI-assisted root-cause analysis.
- **Enterprise Azure OpenAI:** Architecting private endpoints, managed identity access, and scalable foundation model deployments.
- **Developer Productivity:** AI-assisted IaC generation, automated incident runbook drafting, and pipeline optimization.

</details>

---

## 📌 Featured Production Architectures & Code Repositories

<div align="center">

| Repository | Focus Area | Technologies |
| :--- | :--- | :--- |
| 🏗️ **[tf-monolithic-landing-zone](https://github.com/rahulgoyaldevops/tf-monolithic-landing-zone)** | Modular Enterprise Azure Landing Zone | `Terraform`, `AzureRM`, `Key Vault`, `Infracost` |
| 🔄 **[terraform-github-actions](https://github.com/rahulgoyaldevops/terraform-github-actions)** | Passwordless Terraform CI/CD with Azure OIDC | `GitHub Actions`, `Azure OIDC`, `DevSecOps` |
| 🔒 **[azure-devsecops-pipeline-templates](https://github.com/rahulgoyaldevops/azure-devsecops-pipeline-templates)** | Enterprise Azure DevOps Pipeline Library | `Azure DevOps`, `Checkov`, `TFLint`, `Gitleaks` |
| 📋 **[cloud-migration-playbook](https://github.com/rahulgoyaldevops/cloud-migration-playbook)** | 100+ App Migration Factory & 6R Framework | `Migration Checklists`, `Cutover`, `Hypercare` |
| 💰 **[azure-finops-governance-toolkit](https://github.com/rahulgoyaldevops/azure-finops-governance-toolkit)** | Cost Optimization Scripts & Policy as Code | `PowerShell`, `Azure Policy`, `FinOps Toolkit` |
| ☸️ **[kubernetes-production-aks](https://github.com/rahulgoyaldevops/kubernetes-production-aks)** | Multi-Zone Production AKS Architecture | `Kubernetes`, `AKS`, `Calico CNI`, `ArgoCD` |

</div>

---

## 🛠️ Technical Competencies

<div align="center">

**Cloud Platforms**<br/>
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Infrastructure as Code & Automation**<br/>
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Bicep](https://img.shields.io/badge/Bicep-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Containers & Orchestration**<br/>
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AKS](https://img.shields.io/badge/Azure_AKS-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**CI/CD & Security**<br/>
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Checkov](https://img.shields.io/badge/Checkov-Security-FF5722?style=flat-square)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)

**Observability & FinOps**<br/>
![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![FinOps](https://img.shields.io/badge/FinOps-Certified_Practices-00C853?style=flat-square)

</div>

---

## 📈 Engineering Activity & Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rahulgoyaldevops&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=0078d4&icon_color=0078d4&text_color=c9d1d9" width="48%" />
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=rahulgoyaldevops&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=0078d4&ring=0078d4&fire=ff6f00&currStreakLabel=0078d4" width="48%" />

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rahulgoyaldevops&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=0078d4&text_color=c9d1d9" width="55%" />

</div>

---

<div align="center">

### 🤝 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahulgoyaldevops/)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Website-rahulgoyal.co.in-0078D4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rahulgoyal.co.in)
&nbsp;
[![Medium](https://img.shields.io/badge/Medium-Articles-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@rahulgec04)
&nbsp;
[![Email](https://img.shields.io/badge/Email-Direct_Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahulgoyal.devops@gmail.com)

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0078d4,35:005a9e,70:102a45,100:090d16&height=120&section=footer" width="100%" />

</div>