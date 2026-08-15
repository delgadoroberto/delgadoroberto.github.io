<div align="center">

# 👋 Hi there, I'm Roberto Delgado

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Inter&size=24&duration=3000&pause=1000&color=16C7C7&center=true&vCenter=true&width=900&lines=Cybersecurity+Engineer;Cloud+%26+Infrastructure+Security;DevSecOps+%26+CI%2FCD+Security;Vulnerability+Management+%26+Hardening" />
</p>

</div>

---

## 👨‍💻 About Me

Cybersecurity professional with 12+ years of experience in cloud security engineering, infrastructure hardening, and technical vulnerability management across enterprise environments.

Currently dedicated to building secure architectures, hardening infrastructure baselines, and scaling secure cloud environments. Active hands-on practitioner leveraging personal labs to design automated DevSecOps pipelines and cloud security solutions.

---

## 🌐 Website & Contact

<p align="center">
<a href="https://delgadoroberto.github.io/">
  <img src="https://img.shields.io/badge/Cybersecurity_CV-1F2937?style=for-the-badge&logo=githubpages&logoColor=white">
</a>
<a href="https://github.com/delgadoroberto">
  <img src="https://img.shields.io/badge/GitHub_Profile-374151?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/delgado-roberto/">
  <img src="https://img.shields.io/badge/LinkedIn-2563EB?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
</p>

---

# 💻 Tech Stack

## ☁️ Cloud & Infrastructure
<p align="left">
<img src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-5835CC?style=for-the-badge&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/LocalStack-121212?style=for-the-badge" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
</p>

## ⚙️ DevSecOps & Automation
<p align="left">
<img src="https://img.shields.io/badge/Git-181717?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
<img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
</p>

## 🔐 Security & Hardening
<p align="left">
<img src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aquasecurity&logoColor=white" />
<img src="https://img.shields.io/badge/Checkov-000000?style=for-the-badge" />
<img src="https://img.shields.io/badge/OWASP_ZAP-000000?style=for-the-badge&logo=owasp&logoColor=white" />
<img src="https://img.shields.io/badge/Tenable_Nessus-00C176?style=for-the-badge" />
<img src="https://img.shields.io/badge/OpenVAS-4CAF50?style=for-the-badge" />
<img src="https://img.shields.io/badge/CIS_Benchmarks-005A9C?style=for-the-badge" />
<img src="https://img.shields.io/badge/Defender_for_Cloud-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
</p>

---

## 🚀 Featured Projects & Labs

### ☁️ [Terraform AWS Security Labs](https://github.com/delgadoroberto/terraform-aws-security-labs)
Security-focused Terraform labs implementing secure AWS configurations, IAM security controls, encryption policies, and automated infrastructure hardening practices.

### 🔐 [DevSecOps Security Pipelines](https://github.com/delgadoroberto/devsecops-pipeline-lab)
Hands-on projects integrating CI/CD security validation, dependency scanning, container security, infrastructure-as-code security testing, and automated security checks.

### 🛡️ [Cybersecurity Hardening Guide](https://github.com/delgadoroberto/linux-security-audit)
Practical security hardening references and automated shell scripts covering system configurations, cloud security posture validation, and infrastructure baselines.

---

## 📌 About This Repository

This repository hosts the source code and automation assets for my personal cybersecurity portfolio website. 

### 📂 Repository Structure
```text
.
├── .github/
│   ├── workflows/
│   │   └── security.yml      # CI/CD automated security pipeline
│   ├── CODEOWNERS            # Repository access and review policies
│   └── dependabot.yml        # Supply chain dependency tracking
├── index.html                # Main web CV structure
├── styles.css                # Interface styling
├── script.js                 # Dynamic frontend logic
├── README.md                 # Technical documentation
├── SECURITY.md               # Repository security policy
└── .gitignore                # Environment and state file hardening
```

---

## ⚙️ Automated CI/CD Security & GitOps

This repository operates under strict GitOps and DevSecOps principles, integrating native security controls directly into the codebase lifecycle:

* **Automated Security Pipeline (`security.yml`):** Every code push triggers a CI/CD workflow that maps source files (`find`), validates the integration of defensive Application Security controls (verifying **Content-Security-Policy** headers within `index.html`), and triggers a custom regex scanning process (`grep`) to prevent credential or API key leakage.
* **Supply Chain Security (`dependabot.yml`):** Configured for automated weekly checking of GitHub Actions dependencies to remediate third-party risks and out-of-date workflow components.
* **Access Control Policy (`CODEOWNERS`):** Enforces explicit branch protection and code review accountability.
* **Environment Hardening (`.gitignore`):** Programmed to explicitly prevent the accidental exposure of localized infrastructure assets, restricting local private environment files (`.env`) and Infrastructure-as-Code state files (`.tfstate`).

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
