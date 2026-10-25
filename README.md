<div align="center">

  <!-- HERO BANNER (DEVOPS INFINITY LOOP LOGO) -->
  <a href="https://github.com/cpandey1993-ux">
    <img src="./assets/devops-hero-banner.png" alt="Chandan Pandey - DevOps, DevSecOps, Cloud Architect" width="100%" />
  </a>

  <br/><br/>

  <h1>Hi, I'm Chandan Pandey 👋</h1>
  <h3>⚡ Senior Cloud, DevSecOps &amp; Infrastructure Architect</h3>

  <p align="center">
    <!-- Quick Contact Badges -->
    <a href="https://github.com/cpandey1993-ux"><img src="https://img.shields.io/badge/GitHub-cpandey1993--ux-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
    <a href="https://www.linkedin.com/in/chandan-pandey-6b1601277"><img src="https://img.shields.io/badge/LinkedIn-chandan--pandey-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <img src="https://img.shields.io/badge/Location-Delhi%2C%20India%20🇮🇳-00F0FF?style=flat-square&logo=googlemaps&logoColor=black" alt="Location" />
    <img src="https://komarev.com/ghpvc/?username=cpandey1993-ux&color=00F0FF&style=flat-square&label=PROFILE+VIEWS" alt="Profile Views" />
  </p>

  <!-- DYNAMIC TYPING SVG -->
  <a href="https://github.com/cpandey1993-ux">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&pause=1200&color=00F0FF&center=true&vCenter=true&random=false&width=750&lines=Senior+Cloud%2C+DevSecOps+%26+Infrastructure+Architect;Azure+Enterprise+Landing+Zones+%7C+Zero-Trust+GitOps;Terraform+Modular+IaC+%7C+Continuous+Drift+Detection;Multi-Stage+YAML+CI%2FCD+Automation+%7C+Self-Hosted+Runners;100%2B+Workload+Migration+Strategy+%7C+FinOps+Optimization" alt="Typing SVG" />
  </a>

</div>

---

## 🚀 About Me

I'm a **DevSecOps Consultant & Cloud Architect** designing, securing, and automating enterprise cloud infrastructure on **Microsoft Azure**. I specialize in **Infrastructure as Code (Terraform)**, secure **CI/CD automation (Azure DevOps multi-stage YAML pipelines)**, and embedding security across the SDLC — turning manual, error-prone deployments into repeatable, auditable, self-service platforms.

- 🔭 **Specialization:** Enterprise Azure Landing Zones, DevSecOps automation, and zero-drift cloud environments
- 🛡️ **Security Focus:** Shift-left security, policy-as-code, and GitOps-driven delivery
- ☁️ **Cloud Depth:** Architecting secure Virtual Networks, Subnets, Bastion hosts, Storage Accounts, and Key Vault
- ⚙️ **IaC Mastery:** Reusable parent/child Terraform modules with remote state lease locking in Azure Blob storage
- 💬 **Ask me about:** Terraform, Azure DevOps YAML, Kubernetes, CI/CD security, and FinOps
- 📍 **Location:** Delhi, India

---

## 🏆 Key Enterprise Highlights (Architecture & Governance)

```
+--------------------------------------------------------------------------------------------------+
|                                    10 Scalability & Quality Pillars                               |
|                                                                                                  |
|  1. Scalable      2. Robust        3. Secure        4. Reliable       5. Portable                |
|  6. Governed      7. High Avail    8. Cost-Optim    9. Backed Up      10. Compliant & Monitored  |
+--------------------------------------------------------------------------------------------------+
```

- 🏛️ **Enterprise Governance & CAF:** Structured Tenant Root hierarchy separating Platform Management Groups (*Identity, Management, Connectivity*) from Workload Landing Zones (*Corp, Online, Dev, UAT, Prod Subscriptions*).
- ⚙️ **Terraform Modular Engineering:** Engineered decoupled, reusable child modules (`azurerm_resource_group`, `azurerm_vnet`, `azurerm_subnet`, `azurerm_storage_account`, `azurerm_keyvault`, `azurerm_vm`, `azurerm_bastion`) backed by Azure Blob remote state lease locking.
- 🔒 **Zero-Trust & Shift-Left DevSecOps:** Integrated automated security gates (**GitLeaks, Checkov, Trivy, TFLint, Infracost**) before deployment; enforced manual approval gates (`ManualValidation@1`) before production mutation.
- 🌐 **Enterprise Hub-and-Spoke Networking:** Centralized traffic inspection via Azure Firewall/NVAs with UDRs (`0.0.0.0/0`), Private Endpoints for PaaS, and private DNS resolution.
- 🔄 **100+ Workload Cloud Migration Strategy:** 5-phase migration framework (*Discovery, Assessment, Readiness, Cutover, Hypercare*) with minimal downtime windows.
- 💰 **FinOps & Cloud Economics:** Eliminating zombie resources (unattached disks, idle public IPs), 30-day rightsizing, and automated scheduling.

---

## 🏗️ End-to-End Enterprise DevSecOps Pipeline Architecture

```mermaid
flowchart TD
    subgraph S1 ["1. Shift-Left Security & Code Validation"]
        A["👨‍💻 Git Push / PR (Trunk-Based)"] --> B["🔍 GitLeaks (Secret & Credential Scan)"]
        B --> C["🛡️ Checkov & Trivy (SAST & CVE Scanning)"]
        C --> D["📐 TFLint & Terraform Validation"]
        D --> E["💰 Infracost (Cloud Spend Estimation)"]
    end

    subgraph S2 ["2. Infrastructure Orchestration & Governance"]
        E --> F["📋 Terraform Plan & Drift Detection"]
        F --> G{"🛡️ Multi-Party Approval Gate (UAT/Prod)"}
        G -->|Approved on Main| H["⚡ Terraform Apply (Self-Hosted Runner)"]
        H --> I["🔒 Remote State Locked in Azure Blob"]
    end

    subgraph S3 ["3. Enterprise Azure Landing Zone"]
        H --> J["🏢 Central Hub VNet (Azure Firewall / VPN / Private DNS)"]
        J --> K["🌐 Spoke VNets (App, DB, Bastion, Private Endpoints)"]
        K --> L["📊 Azure Monitor AMA & Central Log Analytics"]
        L --> M["🔔 Automated Alerts (Slack & Email Notifications)"]
    end
```

---

## 🛠️ Tech Stack

### ☁️ Cloud Platforms & Networking
<p>
  <img src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/Azure_Networking-0078D4?style=for-the-badge&logo=azure-virtual-machines&logoColor=white" alt="Networking" />
  <img src="https://img.shields.io/badge/Azure_Firewall-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Firewall" />
  <img src="https://img.shields.io/badge/Azure_Bastion-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Bastion" />
</p>

### 🏗️ Infrastructure as Code
<p>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/HCL-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="HCL" />
  <img src="https://img.shields.io/badge/TFLint-2088FF?style=for-the-badge&logo=terraform&logoColor=white" alt="TFLint" />
  <img src="https://img.shields.io/badge/Infracost-00C58A?style=for-the-badge&logo=infracost&logoColor=white" alt="Infracost" />
</p>

### 🔄 CI/CD & DevSecOps Automation
<p>
  <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white" alt="Azure DevOps" />
  <img src="https://img.shields.io/badge/Azure_Pipelines-2560E0?style=for-the-badge&logo=azure-pipelines&logoColor=white" alt="Pipelines" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Self--Hosted_Agents-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white" alt="Runners" />
</p>

### 🛡️ Cloud Security & Governance
<p>
  <img src="https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Entra ID" />
  <img src="https://img.shields.io/badge/Azure_Key_Vault-0089D6?style=for-the-badge&logo=azure-key-vault&logoColor=white" alt="Key Vault" />
  <img src="https://img.shields.io/badge/Checkov-2C3454?style=for-the-badge&logo=bridgecrew&logoColor=white" alt="Checkov" />
  <img src="https://img.shields.io/badge/Trivy-1B3A57?style=for-the-badge&logo=aqua&logoColor=white" alt="Trivy" />
  <img src="https://img.shields.io/badge/Azure_Policy-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Policy" />
</p>

### 🐳 Containers & Orchestration
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Azure_Kubernetes_Service_(AKS)-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="AKS" />
</p>

### 📊 Monitoring, Cost & Observability
<p>
  <img src="https://img.shields.io/badge/Azure_Monitor-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure Monitor" />
  <img src="https://img.shields.io/badge/Log_Analytics-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Log Analytics" />
  <img src="https://img.shields.io/badge/Slack_Alerts-4A154B?style=for-the-badge&logo=slack&logoColor=white" alt="Slack" />
</p>

### 💻 Scripting & Systems
<p>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>

---

## 📂 Featured Repositories

| Repository | Focus Domain | Architecture & Technologies | Implementation Highlights |
| :--- | :--- | :--- | :--- |
| **[Chandan_terraform_module](https://github.com/cpandey1993-ux/Chandan_terraform_module)** | Infrastructure as Code | `Terraform` `HCL` `Azure RM` | Production-grade modular Azure architecture implementing reusable child modules (Resource Groups, Storage Accounts, Networking) with strict parameter hygiene and state isolation. |
| **[Birthday-notification](https://github.com/cpandey1993-ux/Birthday-notification)** | Event Automation & Scripting | `PowerShell` `Slack API` `SMTP` | Automated event monitoring and notification utility integrating secure secrets management, Slack Webhook payloads, and SMTP delivery. |
| **[Chandan-devOps-learning-journey](https://github.com/cpandey1993-ux/Chandan-devOps-learning-journey)** | DevSecOps Knowledge Base | `Linux` `Azure` `DevOps` `Git` | Deep technical repository documenting architectural blueprints, Linux administration, Azure resources, and CI/CD pipelines. |
| **[classic_pipeline_rg](https://github.com/cpandey1993-ux/classic_pipeline_rg)** | Release Engineering | `Azure DevOps` `Pipelines` `ARM` | Infrastructure provisioning and pipeline execution practices leveraging Azure DevOps automation workflows. |

---

## 📊 Live GitHub Engineering Metrics

<div align="center">

  <table border="0">
    <tr>
      <td width="50%" align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=cpandey1993-ux&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00F0FF&icon_color=00F0FF&text_color=C9D1D9" alt="Chandan's GitHub Stats" width="100%" />
      </td>
      <td width="50%" align="center">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=cpandey1993-ux&theme=tokyonight&hide_border=true&background=0D1117&stroke=00F0FF&ring=00F0FF&fire=00F0FF&currStreakLabel=00F0FF" alt="Chandan's GitHub Streak" width="100%" />
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=cpandey1993-ux&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00F0FF&text_color=C9D1D9" alt="Top Languages" width="60%" />
      </td>
    </tr>
  </table>

</div>

---

## 🤝 Let's Connect!

I'm always open to discussing **Cloud Architecture, DevSecOps transformations, Landing Zones, and enterprise consulting**:

<div align="center">

  <a href="https://www.linkedin.com/in/chandan-pandey-6b1601277">
    <img src="https://img.shields.io/badge/LinkedIn-Connect%20with%20Chandan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://github.com/cpandey1993-ux">
    <img src="https://img.shields.io/badge/GitHub-Follow%20%40cpandey1993--ux-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>

  <br/><br/>
  <sub>📍 Based in <strong>Delhi, India</strong> • Open to Senior / Lead DevSecOps &amp; Cloud Platform Engagements</sub>

</div>
