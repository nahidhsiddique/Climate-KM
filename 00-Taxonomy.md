\# Knowledge Management Taxonomy



This document outlines the standard classification system, naming conventions, and tag structures used to organize knowledge across our repositories and internal wikis.



\---



\## 1. High-Level Core Domains

All documentation must fall under one of the following primary categories:



\*   \*\*Engineering \& Tech (`/eng`):\*\* Software development, architecture, DevOps, infrastructure, and API references.

\*   \*\*Product \& Design (`/prod`):\*\* Product requirements (PRDs), user research, wireframes, and UX guidelines.

\*   \*\*Operations \& HR (`/ops`):\*\* Employee onboarding, company policies, legal compliance, and internal tools.

\*   \*\*Growth \& Marketing (`/growth`):\*\* Sales playbooks, brand assets, SEO strategies, and campaign post-mortems.



\---



\## 2. Document Types (Faceted Taxonomy)

To keep formats consistent, prefix or suffix files using these standard document types:



\*   `guide-`: Step-by-step instructional tutorials or how-tos.

\*   `policy-`: Rules, compliance guidelines, and organizational standards.

\*   `playbook-`: Execution frameworks and repeatable strategies for teams.

\*   `spec-`: Technical designs, requirements, and system architecture blueprints.

\*   `log-`: Decision journals, meeting minutes, and architectural change logs (ADRs).



\---



\## 3. Global Tagging System

Use the following standardized tags in the document frontmatter metadata to improve searchability:



\### Status Tags

\*   `#status/draft`: Work in progress; not verified.

\*   `#status/active`: Current, verified, and up-to-date source of truth.

\*   `#status/archived`: Deprecated or historical information for reference only.



\### Audience Tags

\*   `#audience/internal`: Only for full-time internal staff.

\*   `#audience/public`: Safe for external vendors, clients, or open-source.



\### Lifecycle Tags

\*   `#review/q1-2026`: Scheduled for review or update by the specified deadline.



\---



\## 4. File Naming Conventions

Maintain lowercase, kebab-case formatting for all directory and file paths to avoid cross-platform linking bugs.



\*   \*\*Correct:\*\* `/eng/guides/setup-ssh-gitbash.md`

\*   \*\*Incorrect:\*\* `/Eng/Guides/Setup\_SSH\_GitBash.MD`



