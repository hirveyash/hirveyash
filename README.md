<h1 align="center">Yash Hirve</h1>
<p align="center"><b>Cloud Security · AWS · IAM · Infrastructure as Code · Detection</b><br>
M.S. Cybersecurity @ Yeshiva University (May 2027) · Ex-Amazon · New York / New Jersey</p>

<p align="center">
  <a href="https://hirveyash.github.io/"><img src="https://img.shields.io/badge/Portfolio-hirveyash.github.io-0B1220?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/yashhirve"><img src="https://img.shields.io/badge/LinkedIn-yashhirve-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:yhirve@proton.me"><img src="https://img.shields.io/badge/Email-yhirve%40proton.me-6D4AFF?style=flat-square&logo=protonmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open%20to-Cloud%20Security%20roles-2EA44F?style=flat-square" alt="Open to Cloud Security roles">
</p>

I build security into cloud infrastructure before it ships. My work focuses on catching misconfigurations in Terraform before they deploy, and on detecting and correlating threats across AWS, Azure and GCP.

## Featured projects

### [TerraGuard](https://github.com/hirveyash/TerraGuard) · Terraform IaC security scanner
A deterministic static-analysis scanner that catches Terraform misconfigurations in pull requests.
- **29 rules** across IAM, S3, RDS, EC2, security groups, KMS, logging and secrets, mapped to **CIS AWS Foundations** and **NIST 800-53**
- CLI with text, JSON and **SARIF** output and severity-based fail thresholds, built to run in **GitHub Actions**
- Secure-code fix for every finding · **230 tests** · ~270 ms per 100 KB of HCL

`TypeScript` `Next.js` `GitHub Actions` `SARIF`

### [CloudSentinel](https://github.com/hirveyash/CloudSentinel) · Multi-cloud threat detection and response
Turns scattered cloud alerts into one incident.
- Normalizes **AWS GuardDuty**, **Azure Defender for Cloud** and **GCP Security Command Center** findings into one schema
- Correlates events by source IP and identity into **cross-cloud incidents**, with explainable 0–100 risk scores
- Analyst-approved response actions (quarantine, revoke credentials) recorded in an authenticated audit log

`TypeScript` `Next.js` `AWS SDK` `Vitest`

## What I work with

| Area | Tools |
| --- | --- |
| Cloud | AWS (IAM, VPC, KMS, GuardDuty, CloudTrail, CloudWatch), Azure Defender for Cloud, GCP SCC |
| Infrastructure & DevSecOps | Terraform, Docker, Kubernetes, GitHub Actions, Trivy, Checkov |
| Security | IAM & least privilege, IaC security, threat detection, incident response, CIS Benchmarks, NIST 800-53, MITRE ATT&CK |
| Languages | Python, TypeScript, Go, Bash, SQL |

## Certifications

- AWS Certified Cloud Practitioner
- ISC2 Certified in Cybersecurity (CC)
- Google Cybersecurity Professional Certificate
- *In progress:* AWS Solutions Architect – Associate (Dec 2026) → AWS Security – Specialty (Mar 2027)

## Building next

- [ ] Secure multi-account AWS landing zone in Terraform (Organizations, SCPs, IAM Identity Center, org CloudTrail)
- [ ] Cloud detection engineering lab: simulated attacks, CloudTrail detections mapped to MITRE ATT&CK
- [ ] Auto-remediation with EventBridge and Lambda
- [ ] EKS security: pod security, RBAC, IRSA, Falco

## Recognition

8th place, ISC2 NJ Chapter CTF · Google Arcade Global Top 25 · ISACA member

---
<sub>Interested in cloud security, IAM or detection engineering? I'm happy to talk: <a href="mailto:yhirve@proton.me">yhirve@proton.me</a></sub>
