Overview
Designed a modular payment reminder automation system for a financial services platform.
A central orchestration workflow runs every evening and delegates reminder execution to reusable sub-workflows based on configurable reminder intervals. Each sub-workflow retrieves eligible unpaid installments, applies business rules, and triggers the appropriate reminder process.
Architecture
Modular Design – One orchestrator coordinates reusable reminder workflows.
Configuration-driven Messaging – Message templates are stored outside the workflow for easier maintenance.
Business Rule Isolation – Eligibility is evaluated before entering the messaging pipeline.
Observability – Every candidate and every provider response is logged for monitoring and coverage analysis.
Reliability – Automatic retries protect against temporary messaging provider failures.
Key Features
Tech Stack
Project Structure
How to Run
Case Study →
Architecture Principles
