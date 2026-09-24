# Michal Uhrin — Software Engineering Portfolio

I develop software that connects business workflows, backend systems and external services. My work includes AI model integration, database-backed applications and automated tests for application logic.

This portfolio supports my individual application to the Halif Hatch Workbench challenge, **Agentic AI for Operations**. It presents three projects through implementation-based case studies, with SalesLoop as the main example of AI integrated into an operational workflow.

## Selected projects

| Project | Purpose | Engineering focus | Status |
| --- | --- | --- | --- |
| **[SalesLoop](projects/salesloop.md)** | Product campaigns and basket recommendations for WooCommerce | AI model calls, semantic product retrieval, background jobs, storefront integration and event reporting | Backend and bundled plugin inspected; separate UI repository unavailable for review |
| **[Cenorama](projects/cenorama.md)** | Price quotations for a small engineering company | Quotation editing, reusable customer and item records, PDF export and email sharing | Backend and frontend inspected; runtime behaviour not verified |
| **[DHZ PWA](projects/dhz-pwa.md)** | Purchase planning, approvals and funding balances for a volunteer fire brigade | Transactional workflows, mobile web interface, passkeys and application tests | Core complete according to the owner; behavioural biometrics under development |

SalesLoop is the product name for the AI-Basket implementation. Its backend, plugin and separate UI belong to **one project**.

## Engineering highlights

- **AI connected to application data:** SalesLoop retrieves product candidates from a synchronised catalogue and passes them to a model for selection. Backend services handle persistence, validation and job progression; the WooCommerce plugin handles storefront and cart interactions.
- **Business workflows across the stack:** Cenorama connects a React quotation editor to a Python API, stored customer and line-item records, generated documents and sharing flows.
- **State and permissions:** DHZ separates purchase-plan approval from receipt approval and updates funding balances inside database transactions.
- **Test automation:** SalesLoop contains tests for product-change detection, event handling and outcome calculations. DHZ contains tests for roles, session locking and purchase workflows. Their presence is evidence of testing work, not a claim that these suites passed during this review.

## Evidence and availability

The case studies are based on read-only inspection of local source checkouts on **24 September 2026**. Features described as implemented were found in code. Applications and test suites were not run for this portfolio; deployments, adoption and commercial results were not independently verified. Each project page states its specific limits.

The source code remains private. This repository contains original descriptions and high-level diagrams only. Technical walkthroughs or demonstrations can be arranged.

[GitHub: MichaelU6](https://github.com/MichaelU6)
