![SkynetAI-Labs Banner](skynet-master.png)

# Adam Baig | SkynetAI-Labs

**Business Development & B2B Sales Leader | Enterprise Client Acquisition | SaaS, AI & Fintech**

I bring a commercial perspective to technology through business development, enterprise client acquisition and revenue growth. At **SkynetAI-Labs**, I build practical cybersecurity, cloud and fintech projects to develop my technical understanding of the products and systems behind those conversations.

This portfolio combines hands-on implementation with security assessment, evidence-led reporting and commercial research. The projects are educational; they do not represent production banking systems or verified customer outcomes.

## Start Here

| Project | What it demonstrates | Evidence |
|---|---|---|
| [Revolut Business fintech case study — Labs 08–12](https://github.com/SkynetAI-Labs/Revolut-fintech-api-security-case-study) | A fictional banking API, JWT/RBAC and customer isolation, Docker/CI, explainable transaction monitoring and UK SME GTM research | [231-test main-branch verification](https://github.com/SkynetAI-Labs/Revolut-fintech-api-security-case-study/actions/runs/40136670923) · [Phase-by-phase audit](https://github.com/SkynetAI-Labs/Revolut-fintech-api-security-case-study/blob/main/AUDIT_LABS_08_12.md) |
| [Secure CI/CD pipeline — Lab 03](https://github.com/SkynetAI-Labs/lab-03-secure-cicd-pipeline) | Tests and security gates, publishing the scanned image, digest/action pins, SBOM and signed provenance | [Verified main workflow](https://github.com/SkynetAI-Labs/lab-03-secure-cicd-pipeline/actions/runs/40134729959) · [Audit](https://github.com/SkynetAI-Labs/lab-03-secure-cicd-pipeline/blob/main/SECURITY_AUDIT.md) |
| [Security monitoring and incident response — Lab 07](https://github.com/SkynetAI-Labs/lab-07-security-monitoring-response) | Historical regional AWS detection, request correlation and SNS-to-SQS alert delivery, followed by teardown | [Incident report](https://github.com/SkynetAI-Labs/lab-07-security-monitoring-response/blob/main/docs/incident-report.md) · [Open findings](https://github.com/SkynetAI-Labs/lab-07-security-monitoring-response/blob/main/SECURITY_AUDIT.md) |

## Verification Snapshot — 24 October 2026

- **Fintech case study:** 231 tests passed, with 10 dependency deprecation warnings. Bandit, pip-audit, Gitleaks, Docker build and the configured Trivy HIGH/CRITICAL gate passed. Two payment-input/balance-integrity defects were fixed with 31 added regression cases.
- **Labs 02 and 03:** the reviewed automated workflows passed.
- **Lab 04:** retained historical Checkov evidence records 41 passed and 4 failed. The repository audit also identified missing explicit HTTPS-only bucket enforcement; no fresh deployment or scan is claimed.
- **Lab 05:** Terraform formatting, initialization and validation passed; Checkov reported **113 passed, 12 failed**. Newly added delivery paths still require live verification.
- **Lab 06:** YAML parsing passed; Checkov reported **279 passed, 4 failed**. Network-policy and authenticated-RBAC evidence limitations are documented.
- **Lab 07:** Terraform validation passed; Checkov reported **54 passed, 10 failed**. Regional coverage and short retention are documented lab limitations.

Security findings remain visible. Passing checks describe the configured tests at their run date; they do not establish production readiness. Each repository links its dated audit and recommendations.

## All 12 Portfolio Labs

| Lab | Focus |
|---|---|
| [01 — Linux security](https://github.com/SkynetAI-Labs/lab-01-linux-security-hardening) | Historical Lynis assessment, package updates, password policy and firewall evidence |
| [02 — Automated security scanning](https://github.com/SkynetAI-Labs/lab-02-automated-security-scanning) | pytest, Semgrep, Gitleaks, pip-audit and Trivy |
| [03 — Secure CI/CD](https://github.com/SkynetAI-Labs/lab-03-secure-cicd-pipeline) | Security gates, container delivery and supply-chain evidence |
| [04 — Terraform and S3 security](https://github.com/SkynetAI-Labs/lab-04-aws-terraform-cloud-security) | Storage controls, logging, event configuration and risk assessment |
| [05 — IAM and CloudTrail](https://github.com/SkynetAI-Labs/lab-05-aws-iam-cloudtrail-security) | Restricted IAM, audit logging and Terraform validation |
| [06 — Kubernetes security](https://github.com/SkynetAI-Labs/lab-06-kubernetes-security) | Pod hardening, RBAC, selected-pod network policies and secret-file checks |
| [07 — Monitoring and response](https://github.com/SkynetAI-Labs/lab-07-security-monitoring-response) | AWS detection, alert delivery and incident investigation |
| [08 — Revolut Business API](https://github.com/SkynetAI-Labs/Revolut-fintech-api-security-case-study#lab-1--business-banking-api) | FastAPI, SQLite, internal transfers and financial integrity |
| [09 — Revolut authentication and API security](https://github.com/SkynetAI-Labs/Revolut-fintech-api-security-case-study#lab-2--authentication-and-api-security) | JWT, Argon2id, RBAC, customer isolation and rate limits |
| [10 — Revolut Docker and DevSecOps](https://github.com/SkynetAI-Labs/Revolut-fintech-api-security-case-study#lab-3--docker-github-actions-and-devsecops) | Container hardening, dependency checks and automated scanning |
| [11 — Revolut transaction monitoring](https://github.com/SkynetAI-Labs/Revolut-fintech-api-security-case-study#lab-4--fraud-detection-and-transaction-monitoring) | Four explainable rules, isolated alerts, administrator review and atomic integration |
| [12 — Revolut market intelligence and GTM](https://github.com/SkynetAI-Labs/Revolut-fintech-api-security-case-study/tree/main/docs/gtm) | UK SME research, competitor comparison, provisional targeting and hypothetical acquisition economics |

**Labs 08–12 are successive phases of one repository and share one combined application test suite.** The 231-test total is not a separate result for each phase.

## Commercial Research and Technical Skills

The GTM case study includes a 25-source register, competitor analysis, assumption-based segment scoring and a hypothetical 90-day pilot. Its base model assumes 75 hours and GBP150 cash, or GBP2,400 economic cost at an assumed GBP30 hourly value. Two expected activations are a model output, not customers acquired. Complete cross-border quotes and customer validation remain open.

Technical work covers Python/FastAPI/SQLite, JWT and Argon2id, Docker, GitHub Actions, security scanning, AWS/Terraform, Kubernetes RBAC/network policies and evidence-based incident investigation. Detailed implementations, historical milestones and limitations are kept in the project repositories.

**Engineering:** Design → Build → Test → Validate → Document → Improve  
**Security:** Identify → Analyse → Remediate → Rescan → Verify → Document  
**Commercial research:** Define → Research → Compare → Model → Challenge Assumptions → Document

## Independence and Contact

The Revolut work is an independent educational simulation and case study, not affiliated with or endorsed by Revolut. All banking customers, accounts and transactions are fictional. No interviews, outreach campaigns, provider partnerships or acquired customers are claimed.

[LinkedIn](https://www.linkedin.com/in/adam-b-30126024) · [GitHub projects](https://github.com/SkynetAI-Labs?tab=repositories)

**Commercial experience. Practical technical learning. Documented results.**
