# GitHub Portfolio Strategy

> A practical framework for presenting cybersecurity, DevSecOps, cloud, and software engineering work with credible evidence.

## Portfolio Objective

The profile should show one coherent engineering identity: a cybersecurity analyst who understands how software and cloud systems are built, operated, and secured. Every pinned repository should demonstrate a distinct capability, a real engineering decision, and verifiable output.

## Pinned Repository Framework

Use up to six pinned repositories. Build and publish them in this order so the strongest signal appears first.

| Priority | Recommended repository | Evidence recruiters should find |
|---:|---|---|
| 1 | `devsecops-container-pipeline` | GitHub Actions, Docker build, Trivy gates, test results, artifact flow, rollback notes |
| 2 | `aws-cloud-security-lab` | VPC diagram, EC2/ALB/ECR design, IAM decisions, logging, cost and teardown guidance |
| 3 | `soc-investigation-playbooks` | Sanitized Splunk/Wireshark investigations, triage logic, findings, remediation and limitations |
| 4 | `python-security-automation` | Focused tools with tests, safe defaults, sample output, packaging and responsible-use notes |
| 5 | `secure-flutter-firebase-app` | App architecture, Firestore rules, authentication flow, threat model and validation |
| 6 | `security-engineering-notes` | Original technical write-ups, diagrams, lab methodology and references |

Pin only repositories that meet a quality threshold. Score each candidate from 0–5 for role relevance, technical depth, security evidence, reproducibility, visual clarity, and maintenance. A pinned project should score at least 22/30 and have no category below 3.

## Naming, Descriptions & Topics

Use short lowercase names with hyphens. Prefer a name that states the system or outcome over a course name, event name, or generic label such as `project-1`.

Write repository descriptions as: **outcome + primary technology + differentiator**.

Examples:

- Secure container delivery pipeline using GitHub Actions, Docker, and Trivy with policy-based release gates.
- Reproducible AWS security lab covering segmented networking, least-privilege IAM, logging, and teardown.
- SOC investigation playbooks with sanitized Splunk queries, packet analysis, and evidence-led remediation.

Add only relevant topics. A useful set includes `cybersecurity`, `devsecops`, `aws`, `docker`, `github-actions`, `trivy`, `soc`, `splunk`, `wireshark`, `nmap`, `python`, `flutter`, and `firebase`.

## Definition of Portfolio-Ready

Before pinning a project, confirm that it has:

- A clear README built from [the repository template](./REPOSITORY_README_TEMPLATE.md)
- A current architecture diagram and explicit trust boundaries
- Setup instructions that work in a clean environment
- Sanitized example input and expected output
- Tests and automated checks that match the project risk
- A threat model, limitations, and responsible-use notes where relevant
- No secrets, employer material, private data, copied coursework, or unsupported claims
- A deliberate license and attribution for third-party work
- Screenshots, logs, scan summaries, or a demo that prove the stated outcome

## Commit & Branch Hygiene

Make commits small enough to review and complete enough to explain one change. Use imperative messages and a consistent convention:

- `feat: add container vulnerability gate`
- `fix: restrict inbound traffic to the load balancer`
- `docs: document SOC triage decision tree`
- `test: cover malformed scan input`
- `chore: update pinned dependency versions`

Create feature branches for material work and merge through pull requests, even on solo projects when the review record adds value. Squash temporary `WIP` commits before merging. Keep experiments on branches or in a clearly labeled lab directory. Never rewrite shared history to make the graph look more active.

## Contribution Graph

Optimize for evidence, not artificial volume. A steady cadence of meaningful commits is stronger than bursts of empty changes. Good contributions include implementation, tests, documentation, diagrams, issue analysis, pull-request reviews, releases, and reproducible lab reports.

Keep work visible when it is safe to publish, enable private contribution counts if desired, and record milestones through tagged releases. Do not split one change into many trivial commits or use automation solely to manufacture activity.

## Repository Governance

Use these controls as the project matures:

| Control | Purpose |
|---|---|
| `LICENSE` | Defines reuse rights and obligations |
| `SECURITY.md` | Gives a private vulnerability-reporting path and scope |
| `CONTRIBUTING.md` | Sets branch, test, review, and conduct expectations |
| `CODEOWNERS` | Makes review responsibility explicit |
| Protected default branch | Requires review and successful checks before merge |
| Dependabot and dependency review | Surfaces vulnerable or stale dependencies |
| Secret scanning and push protection | Reduces credential exposure |
| Required CI checks | Enforces tests, linting, builds, and security gates |
| Tagged releases and changelog | Makes milestones, fixes, and rollback points visible |

For public demonstrations, MIT is a clear permissive default. Use Apache-2.0 when an explicit patent grant matters. Choose GPL only when reciprocal distribution is intentional. With no license, others generally cannot reuse the code. Do not license or publish material owned by an employer, university, client, or third party without permission.

## Profile Presentation

Recommended public metadata:

- **Name:** Ahsan Mushtaq
- **Bio:** Cybersecurity & Software Engineering | DevSecOps, AWS, SOC workflows, cloud infrastructure, and security automation
- **Location:** Lahore, Pakistan
- **Website:** LinkedIn profile or a future portfolio domain

Keep claims precise. Describe NETSOL work as internship exposure and name only tools, outcomes, and workflows that can be discussed publicly. Replace the profile README roadmap entries with direct project links as each repository reaches the portfolio-ready threshold.

## Review Cadence

Review the profile monthly and after every major release. Remove stale pins, fix broken setup steps, refresh screenshots and scan evidence, archive abandoned experiments, and update the profile summary when the target role changes.
