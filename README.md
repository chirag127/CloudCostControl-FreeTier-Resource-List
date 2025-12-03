# CloudCostControl-FreeTier-Cloud-Services-Awesome-List

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List/ci.yml?style=flat-square)](https://github.com/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List?style=flat-square)](https://codecov.io/gh/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List)
[![License](https://img.shields.io/github/license/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List?style=flat-square)](https://github.com/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List)

<p align="center">
  <a href="https://stars.github.com/ML/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List" target="_blank"><img src="https://img.shields.io/badge/Star%20%E2%98%85%EF%B8%8F%20this%20Repo-blue?style=social&logo=github" alt="Star this Repo"></a>
</p>

---

This repository aggregates and curates a comprehensive, community-driven list of Software-as-a-Service (SaaS), Platform-as-a-Service (PaaS), and Infrastructure-as-a-Service (IaaS) offerings that provide generous, perpetually usable free tiers.

Our mission is to empower DevOps practitioners, Site Reliability Engineers (SREs), and Cloud Architects to build proof-of-concepts, small-scale applications, and personal projects while aggressively optimizing cloud expenditure.

## 🏛️ Architecture Overview

This project, being an "Awesome List," relies on structured markdown for presentation and community contribution via established GitHub workflows.

text
CloudCostControl-FreeTier-Cloud-Services-Awesome-List/
├── README.md             (Primary Documentation)
├── BADGES.md             (Badge Configuration Reference)
├── LICENSE               (CC BY-NC 4.0)
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── workflows/
│       └── ci.yml        (Build & Lint Validation)
└── *.md                  (Category Files: saas.md, paas.md, iaas.md)


## 📋 Table of Contents

1. [Features & Scope](#-features--scope)
2. [Technology Stack & Standards](#-technology-stack--standards)
3. [Contributing Guidelines](#-contributing-guidelines)
4. [License](#-license)
5. [🤖 AI Agent Directives](#-ai-agent-directives)

---

## ✨ Features & Scope

*   **Comprehensive Indexing:** Categorized listing across SaaS, PaaS, and IaaS providers.
*   **Perpetual Free Tier Focus:** Excludes time-limited trials; prioritizes always-free allowances.
*   **Community Driven:** Utilizes robust GitHub Issues and Pull Request templates for high-integrity submissions.
*   **Automated Validation:** CI pipeline (`ci.yml`) ensures basic Markdown formatting and link integrity on every submission.

## 🛠️ Technology Stack & Standards

While the artifact itself is Markdown, adherence to professional development standards is paramount for maintaining list integrity.

| Component | Standard / Tool | Rationale |
| :--- | :--- | :--- |
| **Data Format** | Markdown (GitHub Flavored) | Universal accessibility and ease of contribution. |
| **License** | CC BY-NC 4.0 | Allows non-commercial use and modification with attribution. |
| **Metadata/CI** | GitHub Actions / Shields.io | Standardized platform for automation and visual status reporting. |
| **Contribution** | Semantic Versioning (Implied) | Changes to service tiers are treated as minor version bumps to the list structure. |

## 🤝 Contributing Guidelines

We welcome contributions from the community to keep this list current and accurate. Please adhere to the following:

1.  Read **`.github/CONTRIBUTING.md`** for detailed steps.
2.  Submit new services via a Pull Request against the appropriate category file (`saas.md`, `paas.md`, or `iaas.md`).
3.  If you find an expired or inaccurate entry, please open a **Bug Report** via the Issue Tracker.
4.  All submissions are subject to CI validation.

## 📄 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**. See the [LICENSE](LICENSE) file for details.

---

<details>
<summary>🤖 AI Agent Directives (Apex Protocol)</summary>

# AGENTS.md Directives (December 2025 Implementation)

## 1. IDENTITY & PRIME DIRECTIVE (Echo)
**Role:** You are a Senior Principal Software Architect, tasked with maintaining the integrity and discoverability of this Cloud Cost Optimization resource.
**Directive:** Ensure all metadata (Description, Topics, README) remains high-fidelity, reflecting the cutting-edge value proposition of perpetually free cloud services in the 2026 landscape. Never allow this list to decay into stale information.

## 2. CONTEXT-AWARE APEX TOOLCHAIN (Markdown/List Maintenance)
Since this repository is an **Awesome List** artifact (Markdown/HTML based), the primary toolchain is focused on **validation, integrity, and documentation rendering**.

*   **LINTING/FORMATTING:** Primary validation is enforced via **GitHub Actions (`ci.yml`)** using standard Markdown link checkers and basic structure checks. Advanced validation requires **external link-checking utilities** executed within the CI environment (e.g., `lychee` or similar modern URL validator).
*   **ARCHITECTURE:** The structure follows a **Categorical Organization Pattern**, ensuring high signal-to-noise ratio for users scanning IaaS, PaaS, and SaaS sections.
*   **DATA SOURCE INTEGRITY:** Priority one is verifying that *every* listed free tier is **PERPETUAL**, not trial-based. Manual verification of provider documentation takes precedence over automated checks where ambiguity exists.

## 3. VERIFICATION COMMANDS (CI/CD Alignment)

To simulate local verification matching the CI pipeline:

1.  **Clone and Setup (Simulated):**
    bash
    git clone https://github.com/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List.git
    cd CloudCostControl-FreeTier-Cloud-Services-Awesome-List
    # No installation needed; relies on local markdown parsing/linters if available.
    
2.  **Run Local Link Check (Conceptual):**
    *(Note: Actual execution requires external tools not guaranteed in all runners, but this is the intent of the CI setup.)*
    bash
    # Hypothetical command for link validation enforced by ci.yml
    markdown-link-checker --files "*.md" --ignore-timeouts
    
3.  **Architecture Review Check:** Confirm that all new entries clearly delineate resource limits (e.g., "5GB Storage/Month" vs. "Unlimited").

## 4. FUTURE DEVELOPMENT DIRECTIVE
If this repository transitions to a dynamic web interface, the **Apex Stack** (TypeScript, Vite, Tauri) must be considered. For now, maintain Markdown purity and strict CI checks.

</details>

---

## 🔗 Repository Metadata

| Field | Value |
| :--- | :--- |
| **Username** | `chirag127` |
| **Repository Name** | `CloudCostControl-FreeTier-Cloud-Services-Awesome-List` |
| **Primary Language** | HTML/Markdown |
| **License** | CC BY-NC 4.0 |
