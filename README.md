<div align="center">

  <!-- Custom Enterprise Cloud Architect Banner -->
  <a href="https://linkedin.com/in/ranjan-bhardwaj" target="_blank">
    <img src="./assets/banner.svg" alt="Ranjan Bhardwaj - Cloud Solutions Architect Banner" width="100%" />
  </a>

  <!-- Animated Subtitle -->
  <a href="https://linkedin.com/in/ranjan-bhardwaj">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=0078D4&center=true&vCenter=true&width=750&lines=Enterprise+Cloud+Solutions+Architect+(Azure+%26+AWS);Azure+Landing+Zone+(CAF)+%26+Multi-Cloud+Governance;Production-Grade+Terraform+%26+Policy-as-Code;End-to-End+DevSecOps%2C+Kubernetes+(AKS)+%26+Observability;15%2B+Years+of+Resilient+Infrastructure+Leadership" alt="Dynamic Typing Subtitle" />
  </a>

  <br/><br/>

  <!-- Quick Badges -->
  <a href="https://linkedin.com/in/ranjan-bhardwaj" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <img src="https://img.shields.io/badge/Location-Delhi%2C%20India-blue?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <a href="#-enterprise-architecture-domains--playbooks">
    <img src="https://img.shields.io/badge/Focus-Cloud%20%26%20Enterprise%20Strategy-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Focus" />
  </a>
  <a href="https://linkedin.com/in/ranjan-bhardwaj" target="_blank">
    <img src="https://img.shields.io/badge/Status-Open%20to%20Architect%20Roles-success?style=for-the-badge&logo=target&logoColor=white" alt="Status" />
  </a>

</div>

---

### 🌟 Executive Summary

**Cloud Solutions Architect & Infrastructure Planning Leader** with **15+ years** of total IT & telecommunications backbone experience, including **6+ years** architecting, automating, and scaling mission-critical enterprise cloud ecosystems (Azure-primary, with hands-on AWS exposure).

* 🏛️ **Cloud SME & Enterprise Architecture**: Trusted technical authority formulating Cloud Adoption Framework (CAF)-aligned Landing Zones, Tenant & Management Group Hierarchies, Subscription Vending, and multi-region HA/DR blueprints.
* ⚙️ **Terraform Landing Zone Engineering**: Architect of reusable, modular Terraform frameworks with remote state hardening, linting, secret scanning, costing, and automated drift detection pipelines — cutting infrastructure provisioning lead times by **60%**.
* 🛡️ **Multi-Tier Zero Trust Security & DevSecOps**: Implemented end-to-end defense-in-depth across Identity, Network, Governance, and Compute levels, embedding **Tfsec**, **Checkov**, and **Trivy** into trunk-based CI/CD pipelines to accelerate release velocity by **40%**.
* 🌐 **Mission-Critical Hub & Spoke Networking**: 15-year telecom and networking foundation designing centralized inspection, UDRs, Azure Firewall, Private Endpoints, ExpressRoute, and IPAM/CIDR conflict resolution.
* 💰 **FinOps & Cloud Modernization**: Championed enterprise cost governance (unattached disk cleanup, VM rightsizing, Reserved Capacity, Log Analytics optimization) and end-to-end 6R migration cycles with zero-downtime cutovers.
* 🤝 **Client, Vendor & GTM Leadership**: Led client architecture workshops, RFP/RFI technical evaluation matrices, SOW drafting, commercial proposals, senior technical interviews, and engineering team upskilling.

---

### 📊 Impact & Value Delivered

<div align="center">

| 🏆 Total Experience | ☁️ Cloud Architecture | ⚡ Provisioning Speed | 🚀 Release Acceleration | 🛡️ Reliability / SLA |
| :---: | :---: | :---: | :---: | :---: |
| **15+ Years**<br>IT & Network Backbone | **6+ Years**<br>Azure & AWS Architecture | **60% Reduction**<br>Modular Terraform | **40% Faster**<br>Automated DevSecOps | **98%+ Sustained**<br>Zero-Downtime HA/DR |

</div>

---

<a id="enterprise-architecture-domains--playbooks"></a>
### 🏛️ Enterprise Architecture Playbooks & Capabilities

```mermaid
flowchart TB
    subgraph G1["1. Enterprise Governance & Identity (CAF)"]
        direction LR
        ID["Microsoft Entra ID (RBAC / PIM / Groups)"]
        MG["Tenant Root MG ➔ Platform MG | Application MG | Sandbox | Decom"]
        POL["Azure Policy & Initiatives + Justified Exemptions"]
    end

    subgraph N1["2. Hub & Spoke Connectivity & Perimeter"]
        direction LR
        IPAM["IPAM & On-Premises CIDR Assessment"]
        HUB["Hub VNet: Azure Firewall + UDR + ExpressRoute / VPN"]
        PRIV["Private Endpoints + Private DNS Zones + Zero Trust"]
    end

    subgraph I1["3. Infrastructure as Code & DevSecOps"]
        direction LR
        TF["Modular Terraform + Encrypted Remote State + Drift Detection"]
        PIPE["Azure Pipelines: Trunk-Based + Branch Policies + PR Gates"]
        SEC["Shift-Left Security: Tfsec + Checkov + Trivy + Infracost"]
    end

    subgraph O1["4. Resilience, Migration & FinOps"]
        direction LR
        MIG["6R Migration Strategy: Assessment ➔ Cutover ➔ Hypercare"]
        HADR["HA / DR: LRS / ZRS / GRS + VMSS + RTO / RPO SLA"]
        FIN["FinOps: Idle Resource Reaper + Reserved Instances + Log Tuning"]
    end

    G1 --> N1
    N1 --> I1
    I1 --> O1
```

---

#### 1. 🏢 Enterprise Governance, Identity & Tenant Hierarchy
* **Microsoft Entra ID (Azure AD)**: Comprehensive user and security group lifecycle management, role-based access control (**RBAC**), least privilege access principles, and Microsoft Defender for Cloud integration.
* **Management Group Hierarchy Architecture**:
  * Designed hierarchical structures beneath **Tenant Root Group**: *Platform MG* (Management, Connectivity, Identity), *Application/Landing Zones MG* (Corp, Online), *Sandbox MG*, and *Decommissioned MG*.
* **Subscription Governance & Boundaries**: Clear separation between platform and workload subscriptions; automated subscription vending, onboarding, and decommissioning workflows.
* **Policy-as-Code & Guardrails**: Enterprise Azure Policy and Policy Initiatives assignments enforcing tags, allowed SKUs, encryption standards, and geographic residency, paired with formal **policy exemption workflows** requiring documented business justifications.

#### 2. 🌐 Hub-and-Spoke Networking Architecture & Zero Trust Perimeter
* **Centralized Traffic Inspection & Egress**: Hub VNet architecture hosting centralized Next-Gen Firewalls (Azure Firewall / NVA) with User Defined Routes (**UDR** / `0.0.0.0/0`) forcing all spoke-to-spoke and spoke-to-internet traffic through inspection.
* **IPAM & CIDR Planning**: Enterprise IP address space design and on-premises CIDR assessment to eliminate IP overlap across hybrid and multi-cloud environments.
* **Private Connectivity**: Comprehensive implementation of **Azure Private Endpoints** and **Private DNS Zones**, disabling public exposure for PaaS data stores (Azure SQL, Storage, Key Vault).
* **Hybrid Backbone**: Enterprise-grade interconnectivity leveraging **Azure ExpressRoute** (with redundant circuits) and high-availability site-to-site **VPN Gateways**.

#### 3. 🛡️ 4-Tier Defense-in-Depth Security Model
* 🔑 **Identity Level**: Microsoft Entra ID Conditional Access, MFA, Privileged Identity Management (PIM), Just-In-Time (JIT) access.
* 🌐 **Networking Level**: Micro-segmentation via NSGs/ASGs, centralized Azure Firewall with threat intelligence, WAF on Application Gateway & Front Door.
* 📋 **Governance Level**: Continuous compliance auditing with Microsoft Defender for Cloud, regulatory compliance dashboards (CIS, ISO 27001), and Azure Policy deny effects.
* 💻 **Compute Level**: Hardened OS baseline images, VM disk encryption at rest with customer-managed keys (CMK), container vulnerability scanning with Trivy.

#### 4. ⚙️ Production Terraform Landing Zone Automation
* **Hardened Remote State**: State stored in dedicated Azure Blob Storage with encryption at rest, TLS 1.2+ enforcement, strict least-privilege RBAC, and lease-based state locking.
* **Modular Enterprise Framework**: Reusable, parameterized Terraform modules versioned in private registries for networking, compute, identity, and PaaS.
* **Automated Quality & Security Gates**: CI/CD integration of `tflint`, `terraform fmt`, `checkov`, `tfsec`, and secret scanning.
* **Cost & Drift Automation**: Pre-deployment cost estimation via **Infracost** with manual approval gates, plus scheduled unattended pipelines for **Terraform Drift Detection**.

#### 5. 🚀 Azure DevSecOps & Enterprise Pipeline Governance
* **Trunk-Based Branching Strategy**: Short-lived feature branches, mandatory Pull Requests (PRs), minimum reviewer enforcement, and **Code Owners** routing.
* **Branch Protection Policies**: `main` branch deletion locks, linear history enforcement, and mandatory build/security check pass criteria.
* **Multi-Stage YAML Pipeline Templates**:
  * `Stage 1: Validate & Test` (Linting, Unit Tests, Static Code Analysis)
  * `Stage 2: Plan & Security Scan` (Tfsec, Checkov, Trivy, Infracost)
  * `Stage 3: Manual Approval Gate` (CAB / Lead Architect sign-off)
  * `Stage 4: Automated Apply` (Isolated service principal deployment)
  * `Stage 5: Rollback & Notification` (Automated failback and telemetry alerting)
* **Middleware & Compute Bootstrapping**: Automated provisioning using VM Custom Data and cloud-init scripts for rapid VM configuration.

#### 6. 🔄 Cloud Migration Lifecycle & Cutover Methodology
* **6R Migration Strategies**: Systematic assessment applying *Rehost, Replatform, Refactor, Repurchase, Retain, or Retire* based on workload complexity and business ROI.
* **Phased Migration Journey**:
  * **Phase 1: Discovery & Assessment**: Dependency mapping, network latency profiling, sizing, and TCO/ROI analysis.
  * **Phase 2: Readiness & Landing Zone**: Substrate preparation, connectivity verification, and governance setup.
  * **Phase 3: Migration Execution**: Pre-migration checklists, pilot testing, and data replication.
  * **Phase 4: Cutover & Go-Live**: Strict cutover window execution, DNS repointing, and rollback readiness.
  * **Phase 5: Post-Migration & Hypercare**: 24/7 hypercare support, telemetry validation, and operational handover.

#### 7. 💰 FinOps & Cloud Cost Optimization
* **Waste Elimination**: Automated discovery and decommission scripts for unattached managed disks, idle load balancers, and orphaned public IPs.
* **Compute Optimization**: Rightsizing oversized compute instances and implementing automated schedule-based VM start/stop routines for non-production environments.
* **Log Ingestion Tuning**: Log Analytics workspace optimization, filtering high-volume verbose tables, and configuring retention policies to curb unnecessary ingestion costs.
* **Capacity Planning**: Formulating strategy for Azure Reserved Virtual Machine Instances (1-yr / 3-yr) and Azure Savings Plans to maximize discount realization.

#### 8. 🔄 High Availability, Backup & Disaster Recovery (HA/DR)
* **Storage Resiliency Tiers**: Strategic selection across **LRS**, **ZRS**, and **GRS / RA-GRS** based on data criticality and compliance requirements.
* **Compute High Availability**: Virtual Machine Scale Sets (**VMSS**) with autoscaling, Availability Zones, and cross-region active-passive / active-active topologies.
* **Business Continuity SLAs**: Explicit **RTO** (Recovery Time Objective) and **RPO** (Recovery Point Objective) architecture design, paired with Azure Site Recovery (ASR) failover drills.

#### 9. 📈 Unified Observability & SRE
* **Full-Stack Monitoring**: Centralized monitoring architecture with **Azure Monitor**, Application Insights, and multi-workspace Log Analytics.
* **Actionable Telemetry**: Custom **Grafana** executive dashboards, Prometheus alerting rules, and automated incident escalation workflows to sustain **98%+ production SLA**.

#### 10. 🤝 Vendor, Presales & Technical Delivery Governance
* **RFP / RFI & Presales Engagement**: Authoring comprehensive technical proposal responses, architecture evaluation matrices, and commercial sizing for enterprise bids.
* **Contractual & SOW Governance**: Defining project scope, deliverables, acceptance criteria, milestone payment sign-offs, sprint backlog dependencies, and risk mitigation registers.
* **Vendor & Third-Party Management**: Environment access provisioning governed by least-privilege principles, vendor escalation matrix design, weekly review cadences, and sprint retrospectives.
* **Transitions & Knowledge Transfer**: Structured documentation handovers, operational runbooks, architecture decision records (ADRs), and formal **RACI matrix** accountability.

#### 11. 👥 Technical Leadership, Mentorship & Hiring
* **Senior Technical Interviewing**: Lead panelist for hiring Senior/Principal Cloud Architects, DevOps Engineers, and SREs.
* **Knowledge Transfer & Upskilling**: Conducted organization-wide KT sessions on Terraform modularization, Azure CAF, and Kubernetes best practices.

---

### 🛠️ Technical Ecosystem & Core Stack

<table>
  <tr>
    <td width="25%"><strong>Cloud Platforms</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white" alt="Azure" />
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS" />
      <img src="https://img.shields.io/badge/Azure_Landing_Zones_(CAF)-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white" alt="CAF" />
      <img src="https://img.shields.io/badge/Multi--Cloud_Strategy-0A85EA?style=flat-square&logo=cloud&logoColor=white" alt="Multi-Cloud" />
      <img src="https://img.shields.io/badge/FinOps_%26_Cost_Optimization-00C781?style=flat-square&logo=cashapp&logoColor=white" alt="FinOps" />
    </td>
  </tr>
  <tr>
    <td><strong>Infrastructure as Code</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Terraform_(Modular)-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
      <img src="https://img.shields.io/badge/Azure_Bicep-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Bicep" />
      <img src="https://img.shields.io/badge/ARM_Templates-0078D4?style=flat-square&logo=azure-devops&logoColor=white" alt="ARM" />
      <img src="https://img.shields.io/badge/Policy--as--Code-24292E?style=flat-square&logo=git&logoColor=white" alt="Policy as Code" />
      <img src="https://img.shields.io/badge/GitOps-F05032?style=flat-square&logo=git&logoColor=white" alt="GitOps" />
      <img src="https://img.shields.io/badge/Infracost-00B4D8?style=flat-square&logo=terraform&logoColor=white" alt="Infracost" />
    </td>
  </tr>
  <tr>
    <td><strong>DevSecOps & CI/CD</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azure-devops&logoColor=white" alt="Azure DevOps" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions" />
      <img src="https://img.shields.io/badge/Checkov-FF6F00?style=flat-square&logo=securityscorecard&logoColor=white" alt="Checkov" />
      <img src="https://img.shields.io/badge/Tfsec-4B5563?style=flat-square&logo=terraform&logoColor=white" alt="Tfsec" />
      <img src="https://img.shields.io/badge/Trivy-0052CC?style=flat-square&logo=aqua&logoColor=white" alt="Trivy" />
      <img src="https://img.shields.io/badge/Shift--Left_Security-D9381E?style=flat-square&logo=shield&logoColor=white" alt="Shift Left" />
    </td>
  </tr>
  <tr>
    <td><strong>Containers & Platforms</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Azure_Kubernetes_Service_(AKS)-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="AKS" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm" />
      <img src="https://img.shields.io/badge/Ingress_Controllers-009639?style=flat-square&logo=nginx&logoColor=white" alt="Ingress" />
      <img src="https://img.shields.io/badge/Azure_PaaS-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure PaaS" />
    </td>
  </tr>
  <tr>
    <td><strong>Networking & Security</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Hub--Spoke_VNet-0078D4?style=flat-square&logo=network&logoColor=white" alt="Hub Spoke" />
      <img src="https://img.shields.io/badge/Azure_ExpressRoute-0089D6?style=flat-square&logo=microsoft&logoColor=white" alt="ExpressRoute" />
      <img src="https://img.shields.io/badge/Azure_Firewall-D83B01?style=flat-square&logo=fortinet&logoColor=white" alt="Azure Firewall" />
      <img src="https://img.shields.io/badge/App_Gateway_%2F_Front_Door-0078D4?style=flat-square&logo=azure&logoColor=white" alt="App Gateway" />
      <img src="https://img.shields.io/badge/Private_Endpoints-0078D4?style=flat-square&logo=azure&logoColor=white" alt="Private Endpoints" />
      <img src="https://img.shields.io/badge/Zero_Trust_Architecture-107C41?style=flat-square&logo=symantec&logoColor=white" alt="Zero Trust" />
      <img src="https://img.shields.io/badge/SD--WAN_%26_DWDM-6B7280?style=flat-square&logo=cisco&logoColor=white" alt="Networking" />
    </td>
  </tr>
  <tr>
    <td><strong>Observability & Governance</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Azure_Monitor-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure Monitor" />
      <img src="https://img.shields.io/badge/Log_Analytics-005A9E?style=flat-square&logo=splunk&logoColor=white" alt="Log Analytics" />
      <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
      <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
      <img src="https://img.shields.io/badge/HLD_%2F_LLD_Design-2C3E50?style=flat-square&logo=diagramsdotnet&logoColor=white" alt="HLD LLD" />
      <img src="https://img.shields.io/badge/CAB_Leadership-1F2937?style=flat-square&logo=jira&logoColor=white" alt="CAB" />
      <img src="https://img.shields.io/badge/RFP_%2F_SOW_Governance-004B87?style=flat-square&logo=readme&logoColor=white" alt="Governance" />
    </td>
  </tr>
</table>

---

### 💼 Career History & Core Architectural Milestones

#### **Senior Technical Lead — DevOps & Cloud Architect** | *Colt Technology Services* &nbsp;&nbsp; `Apr 2023 – Present`
* **Enterprise Cloud Strategy & CAF Modernization**: Cloud SME driving multi-cloud strategy, CAF-aligned Landing Zones, and enterprise data modernization roadmaps across Indian and global stakeholders.
* **Tenant & Subscription Hierarchy**: Designed and implemented multi-tier management group architectures (Tenant Root, Platform, Workloads, Sandboxes) with automated subscription vending.
* **Modular Terraform Standardization**: Formulated enterprise-wide reusable Terraform frameworks, establishing remote state hardening, linting, and drift detection pipelines that reduced provisioning times by **60%**.
* **DevSecOps & Shift-Left Implementation**: Embedded security scanners (**Tfsec**, **Checkov**, **Trivy**) into trunk-based Azure DevOps pipelines, accelerating release velocity by **40%**.
* **Client & Presales Engagement**: Partnered with Sales and GTM teams for customer-facing solution architecture in the Indian market, authoring RFP responses, HLD/LLD technical specifications, and driving C-level workshops.
* **AKS & Cloud Native Platforms**: Standardized containerized workloads on AKS using Helm charts, ingress controllers, and secure Key Vault integration.
* **Sustained High Availability & SRE**: Unified telemetry across Azure Monitor, Log Analytics, and Grafana, sustaining **98%+ production uptime**.

#### **Technical Lead — Cloud Architect** | *Colt Technology Services* &nbsp;&nbsp; `Jan 2020 – Apr 2023`
* Led complex cloud migration initiatives, authoring pre/post checklists, cutover procedures, and hypercare plans.
* Engineered hybrid cloud network solutions with ExpressRoute, VPN Gateways, and Azure App Gateway to ensure business continuity.
* Chaired Change Advisory Board (CAB) reviews and release governance meetings, coordinating multi-disciplinary teams.
* Mentored engineers in Terraform IaC, Azure networking, and Kubernetes platform engineering.

#### **Enterprise Telecom & Network Engineering Foundation** &nbsp;&nbsp; `2011 – 2020`
* *SI Infratel | Airtel UNOC | Spectranet*
* 9+ years managing carrier-grade transmission networks, DWDM, SDH, OSPF/EIGRP/VLAN routing, delivering **99.9% network SLA** compliance and 40% faster fault restoration.

---

### 📈 GitHub Activity & Engineering Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ranjan0404&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=0078D4&icon_color=00B4D8&text_color=E6EDF3" alt="Ranjan's GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ranjan0404&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=0078D4&text_color=E6EDF3" alt="Top Languages" height="165" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ranjan0404&theme=tokyonight&hide_border=true&background=0D1117&ring=0078D4&fire=FF9900&currStreakLabel=00B4D8" alt="GitHub Streak" />
</div>

---

### 🤝 Strategic Value Proposition

```
┌────────────────────────────────────────────────────────────────────────┐
│  ✔ Enterprise Governance, Entra ID & CAF Landing Zone Architecture     │
│  ✔ Scalable Modular Terraform (IaC) with Automated Drift Detection     │
│  ✔ Robust DevSecOps Automation with Shift-Left Security Scanners       │
│  ✔ Zero Trust Hub-and-Spoke Networking & Private Endpoint Topologies   │
│  ✔ 6R Cloud Migration Execution: Discovery, Cutover & Hypercare        │
│  ✔ FinOps Cloud Cost Governance & Capacity Optimization (RI / Savings) │
│  ✔ High-Availability & Disaster Recovery Architectures (98%+ SLA)     │
│  ✔ Client-Facing Presales, RFP/RFI Blueprints & GTM Enablement         │
│  ✔ Vendor SOW Governance, Deliverable Sign-Offs & RACI Accountability  │
│  ✔ Senior Technical Interviews, Team Mentorship & Architectural KT     │
└────────────────────────────────────────────────────────────────────────┘
```

---

### 📬 Connect With Me

Looking for an **Enterprise Cloud Solutions Architect**, a **Principal Cloud Strategist**, or a leader to spearhead your cloud modernization and DevSecOps journey?

<div align="center">

<a href="https://linkedin.com/in/ranjan-bhardwaj" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Connect%20with%20Ranjan-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/ranjan0404" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-ranjan0404-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

<br/><br/>

📍 **Location:** Delhi, India &nbsp;|&nbsp; 🌐 **Open to:** Enterprise Cloud Architecture • Remote & Hybrid Engagements • Leadership Opportunities

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_color_list=0:FF9900,50:1E3A8A,100:0078D4&height=100&section=footer" width="100%" alt="Footer" />
</div>
