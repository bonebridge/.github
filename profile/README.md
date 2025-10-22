# Bonebridge GitHub Organization

Welcome to the **Bonebridge** GitHub organization.  
This space hosts all repositories related to Bonebridge’s software development, automations, and infrastructure.

---

## 📁 Repository Structure

Repositories follow a consistent naming convention and organizational structure to keep the codebase clean and scalable.

### Naming Convention

**Format:**
<area>-<scope>-<name>[-<qualifier>]


| Component | Description | Example |
|------------|-------------|----------|
| **area** | Defines the purpose or category of the repository | `proj`, `infra`, `ops`, `qa`, `lib`, `template`, `sandbox`, `archive` |
| **scope** | Refers to the project, system, or business domain | `asea`, `edhr`, `shared` |
| **name** | Identifies the main functionality or focus | `api`, `ui`, `ci`, `sync` |
| **qualifier** *(optional)* | Adds context such as language, cloud, or version | `python`, `gcp`, `v2` |

**Examples:**
proj-asea
archive-ops-gh-actions-ci
qa-pre-commit-python
sandbox-snippets


### Area Definitions

| Area | Purpose |
|------|----------|
| **proj-*** | Project-specific repositories (e.g., ASEA, eDHR) |
| **ops-*** | Internal automation and operations repositories |
| **qa-*** | Quality assurance and code quality tools |
| **AppsScript** |
| **template-*** | Template repositories for bootstrapping new projects |
| **sandbox-*** | Experimental or prototype code |
| **archive-*** | Retired repositories retained for reference |

---

## 🧭 Active Repositories

| Repository | Description | Status |
|-------------|-------------|---------|
| **proj-asea** | Atlassian Space Export Automation | 🟢 Active |
| **proj-edhr** | eDHR project automation | 🟢 Active |
| **qa-pre-commit-python** | Shared Python pre-commit hooks and code quality tools | 🟢 Active |
| **sandbox-snippets** | Playground for testing small-scale scripts | 🟡 Experimental |
| **archive-ops-gh-actions-ci** | GitHub Actions templates for CI/CD pipelines | 🟥 Inactive |

---

## 🧱 Standards and Practices

To ensure maintainability and compliance across all repositories:

- Each repository must include a **README.md**, **LICENSE**, and (if applicable) a **CODEOWNERS** file.  
- Code must follow internal **Apps Script** and **Python Standards**, documented in Confluence.  
- Major changes are tracked in the **Internal Automation Register**.  
- CI/CD pipelines should use shared templates. 
- Version control is handled via GitHub with appropriate branching and review workflows.  
- Automated pre-commit checks are provided via `qa-pre-commit-python`.

---

## 🧪 Sandbox and Prototypes

Experimental or proof-of-concept work belongs in `sandbox-*` repositories.

- Use clear descriptions indicating the goal or experiment.
- Once validated, promote the work into a new or existing `proj-*` repository.
- Outdated prototypes can be archived (see below).

---

## 🗂️ Archiving Policy

- Repositories no longer maintained are renamed to `archive-*` and set to **Archived** status in GitHub.  
- Archived repositories remain read-only but available for reference and learning.  
- Critical or reusable code should be extracted into `lib-*` or `qa-*` repositories before archiving.

---

## 🤝 Contribution

Internal contributors should follow the established Git workflow:

1. Fork the repository or create a feature branch.
2. Commit using meaningful messages following internal commit guidelines.
3. Run pre-commit checks from `qa-pre-commit-python`.
4. Open a Pull Request for review and approval.
5. Merge only after successful tests and peer review.

---

## 🛠️ Maintenance & Governance

| Role | Responsibility |
|------|----------------|
| **Process Automation Specialist** | Maintains automation scripts and CI/CD processes |
| **Developers** | Implement and maintain project-specific repositories |
| **QM&RA** | Ensure software documentation and processes meet QMS standards |

---

*© Bonebridge — Internal Use Only*
