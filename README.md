# Hi, I'm Goerres 👋

**M.Sc. Computer Science student at Hochschule Darmstadt**, specialising in
**Cloud Computing & Cloud Security**. Currently looking for a working-student
position (*Werkstudent*) in Cloud / DevOps in the Rhine-Main area.

- 🔐 Background in security engineering: 10 months at a post-quantum
  cryptography company (internship + bachelor thesis) working with Rust,
  HashiCorp Vault, PKI and policy-as-code
- ⚙️ Hands-on with Docker, CI/CD (GitHub Actions, GitLab CI) and Linux
- ☁️ Now building a hands-on AWS + Terraform portfolio (see roadmap below)
- 🗣️ French (native) · German (C1) · English (B1)

## Tech stack

**Cloud & DevOps:** Docker · Docker Compose · GitHub Actions · GitLab CI · HashiCorp Vault · Linux · *learning: AWS, Terraform, Kubernetes*
**Languages:** Rust · Python · TypeScript · Java · C/C++ · SQL · Bash
**Security:** PKI/X.509 · post-quantum crypto (ML-KEM, ML-DSA) · OAuth 2.0/JWT · policy-as-code (Cedar) · STRIDE

## Featured projects

| Project | What it shows |
|---------|---------------|
| [devchat](https://github.com/goen237/devchat) | Real-time chat (React, Node.js, Socket.io) with Docker, GitHub Actions CI/CD and Kubernetes manifests |
| [distributed-matrix-grpc](https://github.com/goen237/distributed-matrix-grpc) | Distributed system with gRPC, UDP health checks, Lamport mutual exclusion over MQTT, scaled with Docker Compose |
| [secure-file-sharing](https://github.com/goen237/secure-file-sharing) | File sharing with per-file envelope encryption, JWT auth and RBAC (FastAPI, MongoDB, Docker Compose) |
| [Reiseplanung](https://github.com/goen237/Reiseplanung) | Full-stack travel planner (Express, Prisma, PostgreSQL, React) with Docker Compose and GitLab CI |

## Cloud portfolio roadmap

Every infrastructure project is built with **Terraform**, deployed through a
**GitHub Actions pipeline with OIDC** (no stored cloud keys), scanned with
**Checkov/Trivy**, and designed to stay within a minimal budget.

| # | Project | Focus | Status |
|---|---------|-------|--------|
| 1 | devchat on Kubernetes | Helm, Ingress, Prometheus on a local cluster (kind) | 🔜 next |
| 2 | Serverless résumé on AWS | S3, CloudFront, Lambda, DynamoDB, CV built from LaTeX in CI | 📋 planned |
| 3 | GDPR-ready multi-tier network | VPC, private subnets, ALB, Auto Scaling across AZs in eu-central-1, KMS encryption | 📋 planned |
| 4 | Observability & auto-remediation | CloudWatch alarms, SNS, Lambda diagnostics, ChatOps notifications | 📋 planned |

## Contact

[LinkedIn](https://www.linkedin.com/in/goerres-nintidem-2790a8285)
