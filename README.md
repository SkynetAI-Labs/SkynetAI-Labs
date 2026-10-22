# Adam Baig | SkynetAI - LABS

**Business Development & B2B Sales Leader | Enterprise Client Acquisition | Revenue Growth | SaaS | AI | Cybersecurity | Cloud**

I bring a commercial perspective to technology through business development, enterprise client acquisition, and revenue growth.

At **SkynetAI - LABS**, I build practical cybersecurity, DevSecOps and fintech engineering projects to deepen my technical understanding of how systems are developed, assessed, secured, tested, and delivered.

This portfolio documents hands-on implementation, security findings, remediation, automated testing and verification.

## GitHub DevSecOps & Fintech Labs

| Project | Focus |
|---|---|
| [Lab 1: Linux Security Assessment and Hardening](https://github.com/SkynetAI-Labs/GitHub-DevSecOps-Lab-1-Linux-Security-Assessment-and-Hardening) | Ubuntu/WSL2 assessment with Lynis, password policies, firewall configuration, and remediation evidence |
| [Lab 2: Automated Security Scanning with GitHub Actions](https://github.com/SkynetAI-Labs/GitHub-DevSecOps-Lab-2-Automated-Security-Scanning-with-GitHub-Actions) | Python testing, Semgrep, Gitleaks, dependency auditing, Trivy, and container vulnerability remediation |
| [Lab 3: Secure CI/CD Pipeline Engineering with GitHub Actions](https://github.com/SkynetAI-Labs/GitHub-DevSecOps-Lab-3-Secure-CICD-Pipeline-Engineering-with-GitHub-Actions) | Protected pull requests, automated security checks, non-root containers, and gated delivery to GitHub Container Registry |
| [Lab 4: AWS Infrastructure as Code & Cloud Security](https://github.com/SkynetAI-Labs/lab-04-aws-terraform-cloud-security) | Terraform, AWS, Checkov security scanning, 41 passed security checks, and cloud security risk assessment |
| [Lab 5: AWS IAM and CloudTrail Security](https://github.com/SkynetAI-Labs/GitHub-DevSecOps-Lab-5-AWS-IAM-and-CloudTrail-Security) | Least-privilege IAM testing, verified CloudTrail log delivery, Terraform deployment and cleanup; Checkov: 55 passed, 8 findings documented |
| [Lab 6: Kubernetes Security](https://github.com/SkynetAI-Labs/GitHub-DevSecOps-Lab-6-Kubernetes-Security) | Local Kubernetes hardening, RBAC, enforced network policies and secret-file testing; Checkov improved to 279 passed with 4 documented findings; cleanup verified |
| [Lab 7: Security Monitoring and Incident Response](https://github.com/SkynetAI-Labs/GitHub-DevSecOps-Lab-7-Security-Monitoring-and-Incident-Response) | AWS CloudTrail and CloudWatch detection, verified SNS/SQS alert delivery, incident investigation and cleanup; Checkov: 54 passed, 10 open findings documented |
| [Lab 8: Revolut Business Fintech API Development](https://github.com/SkynetAI-Labs/Revolut-business-fintech-security-gtm#lab-1--business-banking-api) | Python, FastAPI, SQLite, fictional business banking accounts, atomic payment transfers, financial integrity validation and transaction history; initial API and payment suite: 11 passing tests |
| [Lab 9: Revolut Business Authentication and API Security](https://github.com/SkynetAI-Labs/Revolut-business-fintech-security-gtm#lab-2--authentication-and-api-security) | JWT authentication, Argon2id password hashing, administrator role checks, tenant isolation, rate limiting and security headers; expanded project suite: 38 passing tests, with Bandit, dependency auditing and secret scanning |
| [Lab 10: Revolut Business Docker, GitHub Actions and DevSecOps](https://github.com/SkynetAI-Labs/Revolut-business-fintech-security-gtm#lab-3--docker-github-actions-and-devsecops) | Digest-pinned Python 3.14.9 Alpine image, non-root execution, reproducible test configuration, 38 passing tests and a passing GitHub pipeline with Bandit, pip-audit, Gitleaks and Trivy; completed candidate scan reported zero HIGH/CRITICAL vulnerabilities |
| [Lab 11: Revolut Business Fraud Detection and Transaction Monitoring](https://github.com/SkynetAI-Labs/Revolut-business-fintech-security-gtm#lab-4--fraud-detection-and-transaction-monitoring) | Four explainable monitoring rules, customer-isolated alerts, administrator review, duplicate-safe historical analysis and atomic payment integration; expanded combined suite: 200 passing tests, with a passing GitHub security pipeline |

Labs 8–11 document successive phases of the same Revolut-inspired portfolio repository. The combined suite expanded from the initial 11-test API milestone to 38 tests during Lab 9, was verified again during Lab 10, and expanded to 200 tests during Lab 11.

## Practical Skills Demonstrated

### Cybersecurity & DevSecOps

- Linux security assessment and hardening
- Git, GitHub, and pull request workflows
- Automated application testing and security scanning
- Docker container security and vulnerability remediation
- GitHub Actions pipeline engineering
- Least-privilege workflow permissions and controlled image delivery
- Static application analysis with Bandit
- Dependency vulnerability auditing with pip-audit
- Secret detection with Gitleaks
- Container vulnerability scanning with Trivy
- Security failure thresholds and remediation verification
- Technical documentation and evidence-based reporting

### AWS & Cloud Infrastructure

- AWS cloud infrastructure and security fundamentals
- Terraform Infrastructure as Code (IaC) configuration and validation
- Checkov infrastructure security scanning and risk assessment
- AWS security monitoring with CloudTrail and CloudWatch
- Verified alarm delivery through SNS and SQS
- Security-event correlation and incident investigation
- Resource cleanup and independent verification

### Kubernetes & Container Security

- Local Kubernetes deployment with kind and Calico
- Kubernetes RBAC and restricted pod-security enforcement
- Non-root containers, read-only filesystems and runtime security verification
- Network-policy enforcement and file-based secret handling
- Digest-pinned container base images
- Build-context exclusions for secrets, databases and development files
- Alpine compatibility testing and removal of unnecessary runtime installation tools

### Fintech API Engineering & Security

- Python and FastAPI application development
- SQLite relational database design
- REST API endpoints and OpenAPI documentation
- Simulated business banking accounts and transactions
- Atomic financial transfers and database rollback
- Payment validation and transaction integrity controls
- JWT access-token creation, signature validation and expiry enforcement
- Argon2id password hashing and credential verification
- Role-based access control and administrator route protection
- Customer-level tenant isolation
- IP-based rate limiting and HTTP security headers
- Automated testing with pytest
- Isolated test databases and financial balance verification
- API tests rejecting missing-expiry, expired and tampered tokens
- Separate runtime and development dependency manifests
- Fresh-environment testing without the local banking database or `.env`
- Container health, authentication-rejection and non-root execution checks
- GitHub project documentation and version control

### Transaction Monitoring & Alert Review

- Explainable rules for large transfers, transfer frequency, cumulative outgoing value and repeated transfers
- Configurable thresholds and structured detection evidence
- UTC time-window boundaries and transaction ordering
- Persistent alerts with customer ownership and duplicate prevention
- Atomic payment and alert storage with rollback on monitoring failure
- Bounded, resumable historical-analysis batches
- Customer-scoped alert retrieval with validated filters and pagination
- Administrator-only review decisions with recorded reviewer and timestamps
- Protection against overwriting final decisions or modifying detection evidence
- Tests covering threshold boundaries, replay safety, access controls and financial integrity

## How I Approach the Work

**Identify → Analyse → Remediate → Rescan → Verify → Document**

Each lab explains its purpose, implementation, results, and limitations. Historical findings remain documented so visitors can follow the remediation process.

For software engineering projects, I apply a complementary approach:

**Design → Build → Test → Validate → Document → Improve**

The objective is to demonstrate practical implementation, measurable results and an understanding of both technical requirements and commercial applications.

## Current Development Roadmap

**Revolut Business — Fintech Security & GTM Portfolio**

| Revolut project lab | Focus | Status |
|---|---|---|
| 1 | Business Banking API Development | Completed — portfolio Lab 8 |
| 2 | Authentication and API Security | Completed — portfolio Lab 9 |
| 3 | Docker, GitHub Actions and DevSecOps | Completed — portfolio Lab 10 |
| 4 | Fraud Detection and Transaction Monitoring | Completed — portfolio Lab 11 |
| 5 | Revolut Business Market Intelligence and GTM Strategy | Planned |

Latest verified Revolut project evidence, confirmed through **23 October 2026**:

- **200 tests passed**, with **10 dependency deprecation warnings** in the latest local full-suite run.
- GitHub Actions passed for Lab 4 implementation commit **`72d40c3`** and completion-documentation commit **`aee8d56`**.
- Bandit reported no issues, dependency auditing reported no known vulnerabilities, and application/test secret scans reported no leaks.
- The completed Lab 4 application image scan reported **zero HIGH/CRITICAL vulnerabilities** at scan time.
- Customer-isolated alert access, administrator review, duplicate prevention and payment rollback were verified through automated tests.
- The repository working tree was clean and synchronized after publication.

Earlier container remediation replaced the Debian base with a verified Alpine image and removed pip and ensurepip after dependency installation. The HIGH/CRITICAL failure threshold remained unchanged, with no explicit vulnerability exceptions added.

Monitoring alerts identify rule matches for review, not confirmed fraud. Thresholds are educational demonstration settings. The project does not implement machine learning, automatic account blocking or external banking integration.

Direct dependencies are pinned; a complete transitive dependency lockfile remains outstanding. Dependency warnings, historical-data assumptions, monitoring performance and database setup and persistence limitations are documented in the repository. Scan results are point-in-time evidence.

The Revolut project is an independent educational simulation, not affiliated with or endorsed by Revolut. All banking customers, accounts and transactions are fictional. It does not demonstrate access to Revolut's production systems, and passing tests and security scans do not establish production readiness.

## Connect

- [LinkedIn](https://www.linkedin.com/in/adam-b-30126024)
- [GitHub repositories](https://github.com/SkynetAI-Labs?tab=repositories)

---

**Commercial experience. Practical technical learning. Documented results.**
