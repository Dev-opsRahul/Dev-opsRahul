<!-- =========================================================================
     RAHUL MAURYA | PRINCIPAL DEVSECOPS & CLOUD SECURITY ARCHITECT
     13+ YEARS ENTERPRISE IT • ZERO TRUST • HARDENED K8S • LLMOPS SECURITY
========================================================================= -->

<div align="center">

<!-- DYNAMIC ANIMATED HERO HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,18,24&height=230&section=header&text=Rahul%20Maurya&fontSize=52&fontAlignY=36&fontColor=ffffff&desc=Principal%20DevSecOps%20Engineer%20%7C%20Distinguished%20Cloud%20Security%20Architect&descAlignY=58&descAlign=50&descSize=20" width="100%" alt="Rahul Maurya - Principal DevSecOps Engineer" />

<!-- DYNAMIC TYPING SVG ANIMATION -->
<a href="https://github.com/Dev-opsRahul">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=3000&pause=1200&color=00E5FF&center=true&vCenter=true&multiline=true&width=860&height=85&lines=13%2B+Years+of+Enterprise+IT+Experience+%E2%80%A2+Global+Scale+Infrastructure;Cloud+Security+Architect+%E2%80%A2+Zero-Trust+Landing+Zones+(Azure+%26+AWS);Hardened+Kubernetes+(AKS%2FEKS)+with+Cilium+eBPF+%26+ArgoCD+GitOps;AI+DevSecOps+%E2%80%A2+Securing+Enterprise+LLMs%2C+vLLM+%26+GenAI+Pipelines;SLSA-3+Software+Supply+Chain+Security+%E2%80%A2+Keyless+OIDC+%26+Cosign" alt="Typing SVG" />
</a>

<br/>

<!-- STRATEGIC BADGES -->
[![Experience](https://img.shields.io/badge/Enterprise_Experience-13%2B_Years-00D26A?style=for-the-badge&logo=codewars&logoColor=white)](#-13-year-enterprise-systems-journey)
[![Primary Cloud](https://img.shields.io/badge/Azure-Cloud_Architect_%26_Landing_Zones-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com/)
[![Secondary Cloud](https://img.shields.io/badge/AWS-Enterprise_DevSecOps-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)](https://aws.amazon.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-Cilium_eBPF_Hardened-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![AI Security](https://img.shields.io/badge/GenAI_Security-LLMOps_%26_Private_vLLM-FF007F?style=for-the-badge&logo=openai&logoColor=white)](#-ai-devsecops--enterprise-llmops-security)
[![Supply Chain](https://img.shields.io/badge/Supply_Chain-SLSA_Level_3-8A2BE2?style=for-the-badge&logo=sigstore&logoColor=white)](#-flagship-project-3-end-to-end-slsa-3-supply-chain-defense)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)

</div>

---

### 🛡️ Executive Technical Summary

With over **13 years of battle-tested enterprise IT experience**, I specialize in designing and delivering **zero-trust multi-cloud platforms, military-grade DevSecOps automation, and hardened Kubernetes ecosystems** for Fortune-scale environments.

My architectural approach shifts security from a reactive post-deployment gatekeeper to an **automated, mathematical guardrail embedded at every phase of the software and AI lifecycle**:
- **Enterprise Infrastructure as Code:** Architecting Azure CAF Landing Zones & AWS Control Tower architectures using Terraform Enterprise, Terragrunt, and OpenTofu with automated state locking and blast-radius minimization.
- **Zero-Trust Identity & Access (IAM):** Eradicating static credentials across CI/CD by standardizing on **Keyless OpenID Connect (OIDC)** Workload Identity Federation and HashiCorp Vault dynamic secret engines.
- **Next-Gen AI Security (LLMSecOps):** Hardening high-throughput private LLM inference clusters (vLLM / Triton) on GPU-enabled Kubernetes with eBPF network segmentation, prompt injection guardrails, and cryptographic model provenance.
- **Policy as Code (PaC) & Supply Chain Security:** Enforcing real-time admission controls using **Kyverno and OPA/Rego**, while generating CycloneDX SBOMs and keyless artifact attestations via **Sigstore (Cosign / Rekor)** for SLSA-3 compliance.

---

## 🧭 13-Year Enterprise Systems Journey

An architectural progression from bare-metal enterprise infrastructure to cutting-edge cloud platforms and AI security:

```mermaid
timeline
    title 13-Year Engineering & Architecture Evolution
    section Foundations (2011 - 2016)
        Linux Kernel & Bare-Metal : Enterprise SysAdmin : High-Availability Clusters : SAN/NAS Storage : Core Network Topologies (BGP/OSPF)
    section Cloud Transformation (2016 - 2020)
        Enterprise Azure & AWS Migration : Large-scale Virtualization : Configuration Management (Ansible) : CI/CD Automation (Jenkins/GitLab)
    section DevSecOps & Platforms (2020 - 2024)
        Terraform Landing Zones : Kubernetes (AKS/EKS) : GitOps (ArgoCD) : Policy-as-Code (OPA) : Shift-Left SAST/DAST Automation
    section Principal Architect & AI (2024 - Present)
        Zero-Trust Multi-Cloud Architecture : Cilium eBPF Kernel Observability : SLSA-3 Supply Chain Defense : LLMOps & GenAI Security
```

---

## 🤖 AI DevSecOps & Enterprise LLMOps Security

As enterprise workloads integrate generative AI and large language models, I architect the security platforms protecting model weights, inference infrastructure, and training data pipelines against the **OWASP Top 10 for LLMs**:

```mermaid
flowchart LR
    %% STYLING DEFINITIONS
    classDef client fill:#1e1e2e,stroke:#00E5FF,stroke-width:2px,color:#ffffff;
    classDef security fill:#2d0a3d,stroke:#FF007F,stroke-width:2px,color:#ffffff;
    classDef compute fill:#0b2b26,stroke:#00D26A,stroke-width:2px,color:#ffffff;
    classDef storage fill:#3a2002,stroke:#FF9900,stroke-width:2px,color:#ffffff;

    User([👤 User / App Client]):::client -->|HTTPS / TLS 1.3| WAF[🛡️ OWASP AI Gateway / WAF]:::security
    
    subgraph S1 ["AI Perimeter & Prompt Guard"]
        WAF --> Guard[NeMo Guardrails / Prompt Shield<br/>- Prompt Injection Defense<br/>- PII / Secret Masking<br/>- Rate Limiting & Token Budget]:::security
    end

    subgraph S2 ["Zero-Trust Private Compute (Isolated GPU Pool)"]
        Guard -->|Mutual TLS| vLLM[⚡ Private vLLM / Triton Cluster<br/>- Hardened AKS GPU NodePool<br/>- Cilium eBPF L7 Network Policy<br/>- Non-Root Read-Only Container]:::compute
    end

    subgraph S3 ["Cryptographic Model Security"]
        Registry[(📦 Private OCI Model Registry)]:::storage -->|ModelScan / ProtectAI| Scan[🔍 Tensor Scanner]:::security
        Scan -->|Cosign Sign & Rekor| vLLM
        vLLM -->|Audit Spans| Langfuse[📊 Langfuse & Grafana Telemetry<br/>Latency, Hallucinations, Token Cost]:::client
    end
```

### Key AI Security Capabilities:
* **Private Isolated Model Serving:** Zero public internet exposure for model weights; private endpoints and Cilium eBPF network policies isolate GPU worker nodes.
* **Model Supply Chain Attestation:** Scanning PyTorch/Safetensors weights with `modelscan` and cryptographically signing models with Cosign before loading onto cluster memory.
* **Runtime Threat Mitigation:** In-line inspection of prompt vectors preventing indirect prompt injection, jailbreaking, and unauthorized data leakage.

---

## 🏛️ Flagship Enterprise Architectures

---

### 🌟 Flagship Project 1: Multi-Cloud Zero-Trust Hub-Spoke Landing Zone
**Target Repository:** [`azure-enterprise-secure-landing-zone`](https://github.com/Dev-opsRahul/azure-enterprise-secure-landing-zone)  
*Enterprise-ready Terraform architecture establishing a multi-subscription cloud perimeter with automated compliance guardrails.*

```mermaid
flowchart TD
    classDef hub fill:#111936,stroke:#3b82f6,stroke-width:2px,color:#ffffff;
    classDef spoke fill:#0c2d27,stroke:#10b981,stroke-width:2px,color:#ffffff;
    classDef sec fill:#381324,stroke:#f43f5e,stroke-width:2px,color:#ffffff;
    classDef pipe fill:#2e1065,stroke:#a855f7,stroke-width:2px,color:#ffffff;

    subgraph CI ["🔒 CI/CD Keyless Pipeline (GitHub Actions)"]
        OIDC[🔑 GitHub OIDC Token]:::pipe -->|Workload Identity| Auth[Azure Entra ID Auth]:::pipe
        Auth --> Checkov[🛡️ Checkov & TFLint Guardrails]:::pipe
        Checkov --> TFPlan[📄 Terraform Spec Execution]:::pipe
    end

    TFPlan --> HubVNet

    subgraph Hub ["🌐 Connectivity Hub VNet (10.100.0.0/16)"]
        HubVNet[Azure Virtual WAN / Hub Router]:::hub
        HubVNet --> AzFW[🔥 Azure Firewall Premium IDS/IPS]:::sec
        HubVNet --> Bastion[🛡️ Azure Bastion PaaS]:::sec
        HubVNet --> AppGW[⚖️ Application Gateway WAF v2]:::sec
    end

    HubVNet -->|Encrypted VNet Peering| SpokeVNet

    subgraph Spoke ["🏢 Production Workload Spoke VNet (10.200.0.0/16)"]
        SpokeVNet[Spoke Routing Table]:::spoke
        SpokeVNet --> Compute[🔒 Private Compute Subnet<br/>Zero Public IPs • NSG Default Deny]:::spoke
        SpokeVNet --> PrivLink[🔗 Private Endpoints Subnet<br/>Azure Key Vault HSM • Storage Blob]:::sec
    end
```

* **Core Highlights:**
  * **100% Secretless Deployments:** Eliminates long-lived Service Principal client secrets; authenticates runners via OpenID Connect (OIDC).
  * **Zero Public Attack Surface:** Compute instances deploy without public IPs, accessible only via Azure Bastion and TLS-terminated private ingress.
  * **Policy-as-Code Enforcement:** Pre-merge Checkov scans enforce 100% compliance with CIS Azure Benchmark v2.0.

---

### 🌟 Flagship Project 2: Hardened Zero-Trust Kubernetes Engine (AKS / Cilium eBPF / ArgoCD)
**Target Repository:** [`k8s-zero-trust-gitops-platform`](https://github.com/Dev-opsRahul/k8s-zero-trust-gitops-platform)  
*Production Kubernetes platform leveraging eBPF kernel-level networking, declarative GitOps, and dynamic secret injection.*

```mermaid
flowchart TB
    classDef git fill:#18181b,stroke:#a1a1aa,stroke-width:2px,color:#ffffff;
    classDef gitops fill:#064e3b,stroke:#34d399,stroke-width:2px,color:#ffffff;
    classDef k8s fill:#1e3a5f,stroke:#60a5fa,stroke-width:2px,color:#ffffff;
    classDef kernel fill:#4c0519,stroke:#fb7185,stroke-width:2px,color:#ffffff;
    classDef secret fill:#451a03,stroke:#fbbf24,stroke-width:2px,color:#ffffff;

    Git[(📦 Git Main Repo<br/>Kustomize & Helm)]:::git -->|mTLS Webhook| Argo[🔄 ArgoCD Engine]:::gitops

    subgraph Cluster ["☸️ Hardened Private Kubernetes Cluster (AKS)"]
        Argo -->|Declarative Sync| Admission[🛡️ Kyverno Admission Controller<br/>Enforce Pod Security Standards: Restricted]:::k8s
        
        subgraph DataPlane ["⚡ Kernel-Level eBPF Data Plane (Cilium)"]
            Admission --> Pod1[Workload Pod: Service A<br/>UID: 10001 • Read-Only FS]:::k8s
            Pod1 <-->|eBPF L7 Network Policy<br/>Mutual TLS Encryption| Pod2[Workload Pod: Service B<br/>Capabilities Dropped: ALL]:::k8s
            CiliumMon[👁️ Hubble Observability DaemonSet]:::kernel -.->|Flow Telemetry| Pod1
        end

        subgraph Secrets ["🔐 Dynamic Identity & Secret Engine"]
            Vault[🏦 HashiCorp Vault Cluster]:::secret -->|Sidecar Injection| Pod1
        end
    end
```

* **Core Highlights:**
  * **Cilium eBPF CNI:** Replaces legacy iptables with kernel-level eBPF filtering, delivering line-rate performance and L3-L7 microsegmentation.
  * **Automated GitOps Reconciliation:** ArgoCD controller manages infrastructure states with continuous drift detection and auto-healing.
  * **Kyverno Guardrails:** Rejects any workload attempting root execution, privilege escalation, or mounting writable root filesystems.

---

### 🌟 Flagship Project 3: End-to-End SLSA-3 Supply Chain Defense
**Target Repository:** [`slsa3-supply-chain-pipeline`](https://github.com/Dev-opsRahul/slsa3-supply-chain-pipeline)  
*Complete software supply chain hardening pipeline enforcing cryptographic signing, SBOM generation, and admission verification.*

```mermaid
flowchart LR
    classDef step fill:#1e1e2e,stroke:#38bdf8,stroke-width:2px,color:#ffffff;
    classDef scan fill:#3b0764,stroke:#c084fc,stroke-width:2px,color:#ffffff;
    classDef sign fill:#14532d,stroke:#4ade80,stroke-width:2px,color:#ffffff;
    classDef k8s fill:#1e3a8a,stroke:#93c5fd,stroke-width:2px,color:#ffffff;

    Commit[📥 Git Push Verified Commit]:::step --> SAST[🔍 Semgrep & Gitleaks]:::scan
    SAST --> Build[📦 Hermetic Container Build]:::step
    Build --> SBOM[📋 Syft SBOM Generation<br/>CycloneDX Format]:::scan
    SBOM --> Vuln[🛡️ Grype Vulnerability Scan<br/>Zero High/Critical Cutoff]:::scan
    Vuln --> Sign[✍️ Cosign Keyless Signing<br/>OIDC & Sigstore Rekor Log]:::sign
    Sign --> Attest[📜 Cosign SBOM Attestation]:::sign
    Attest --> Admission[☸️ Kyverno Admission Gate<br/>Verify Signature & Rekor Log Entry]:::k8s
    Admission --> Deploy([🚀 Production Pod Runtime]):::k8s
```

* **Core Highlights:**
  * **SLSA Level 3 Compliance:** Builds run hermetically with immutable provenance tracking every build dependency back to source commit.
  * **Keyless Cosign Signing:** Utilizes ephemeral certificates backed by Sigstore's Rekor transparency log, removing key management headaches.
  * **In-Cluster Admission Verification:** Pod deployments are rejected if container images lack valid cryptographic signatures and vulnerability attestations.

---

## 🛠️ Complete Technology Arsenal

<div align="center">

### Cloud Platforms & Enterprise Perimeter
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA1A?style=for-the-badge&logo=opentofu&logoColor=black)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

### Containers, Orchestration & Kernel Observability
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm_3-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Cilium](https://img.shields.io/badge/Cilium_eBPF-1F8CEB?style=for-the-badge&logo=cilium&logoColor=white)
![Istio](https://img.shields.io/badge/Istio_mTLS-466BB0?style=for-the-badge&logo=istio&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)

### Zero-Trust IAM & Secrets Management
![HashiCorp Vault](https://img.shields.io/badge/Vault-FFC812?style=for-the-badge&logo=vault&logoColor=black)
![Azure Key Vault](https://img.shields.io/badge/Azure_Key_Vault-0078D4?style=for-the-badge&logo=azurekeyvault&logoColor=white)
![AWS Secrets Manager](https://img.shields.io/badge/AWS_Secrets-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![CyberArk](https://img.shields.io/badge/CyberArk-002B49?style=for-the-badge&logo=cyberark&logoColor=white)
![Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

### DevSecOps, Policy-as-Code & Supply Chain
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Checkov](https://img.shields.io/badge/Checkov-24292E?style=for-the-badge&logo=bridgecrew&logoColor=white)
![OPA](https://img.shields.io/badge/OPA_Rego-4B3B8B?style=for-the-badge&logo=openpolicyagent&logoColor=white)
![Kyverno](https://img.shields.io/badge/Kyverno-009688?style=for-the-badge&logo=kubernetes&logoColor=white)
![Sigstore Cosign](https://img.shields.io/badge/Cosign_Rekor-4B0082?style=for-the-badge&logo=sigstore&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-0052CC?style=for-the-badge&logo=aqua&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-2B2D42?style=for-the-badge&logo=semgrep&logoColor=white)

### AI DevSecOps & LLMOps Ecosystem
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM_Inference-00D26A?style=for-the-badge&logo=fastapi&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA_CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Triton](https://img.shields.io/badge/Triton_Server-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse_LLMOps-1F2937?style=for-the-badge&logo=opentelemetry&logoColor=white)

</div>

---

## 📈 Engineering Analytics & Continuous Contribution

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Dev-opsRahul&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true" width="48%" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Dev-opsRahul&theme=radical&hide_border=true" width="48%" alt="GitHub Streak" />

<br/>

<!-- ANIMATED CONTRIBUTION ACTIVITY GRAPH -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Dev-opsRahul&theme=react-dark&hide_border=true&area=true" width="97%" alt="Activity Graph" />

</div>

---

## 📑 Production Architecture Decision Records (ADR Highlights)

To ensure long-term architectural integrity, every technical decision across my repositories is governed by formal Architecture Decision Records (ADRs):

* [**ADR-001: Mandating Keyless OpenID Connect (OIDC) over Static Service Principal Secrets**](https://github.com/Dev-opsRahul)  
  *Context:* Static credentials stored in CI/CD secrets present rotation overhead and exfiltration exposure.  
  *Decision:* Standardized on Microsoft Entra ID Workload Identity Federation across all workflows. Zero permanent secrets in GitHub.
* [**ADR-002: Transitioning Kubernetes Networking from iptables to Cilium eBPF**](https://github.com/Dev-opsRahul)  
  *Context:* Complex microservice topologies suffer latency degradation and lack deep L7 traffic auditing with standard kube-proxy.  
  *Decision:* Enforced Cilium eBPF as cluster CNI for line-rate kernel packet routing, Hubble flow metrics, and L7 API security policies.
* [**ADR-003: Implementing SLSA Level 3 Supply Chain Ingestion Controls**](https://github.com/Dev-opsRahul)  
  *Context:* Third-party container dependencies introduce unknown vulnerabilities and image tampering risks.  
  *Decision:* Cryptographic signing via Cosign, Syft SBOM generation, and Kyverno admission policy validation prior to cluster scheduling.

---

## 🤝 Enterprise Leadership & Strategic Engagement

* **Target Roles:** Principal DevSecOps Engineer, Distinguished Cloud Security Architect, Staff Platform Engineer, Head of Infrastructure Security.
* **Advisory & Consulting:** Zero-Trust Cloud Transformations, Multi-Subscription Landing Zones, Enterprise GitOps Migrations, AI/LLMOps Security.
* **Let's Connect:** Reach out on [LinkedIn](https://linkedin.com) or contact me directly via **[GitHub Discussions](https://github.com/Dev-opsRahul)**.

<div align="center">

<!-- ANIMATED FOOTER WAVE -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,18,12,6&height=120&section=footer" width="100%" alt="Footer Wave" />

</div>