# Cora Recap Engine

## Project Overview

Provides an API and worker service that automates lead management and recap processes.

---

## Business Problem

The Cora Recap Engine addresses the challenge of managing and automating lead processes for businesses, particularly those handling inbound and outbound leads. It streamlines recap workflows, reducing manual effort and improving efficiency for sales teams.

---

## Objective

- Automate lead management and recap processes to enhance operational efficiency.
- Integrate AI capabilities for generating summaries and insights from lead interactions.
- Provide a reliable API service to replace complex workflows like those offered by Zapier.

---

## Tools & Technologies

- FastAPI
- PostgreSQL
- Redis
- RQ
- OpenAI
- SQLAlchemy
- Docker
- Pydantic

---

## Project Workflow

- The API service receives lead data through webhooks and processes it using FastAPI.
- Data is stored persistently in PostgreSQL, ensuring authoritative state management.
- The worker service utilizes RQ to handle background job execution for processing leads.
- AI-driven summaries are generated using OpenAI, enhancing the quality of recaps.
- The system integrates with external services like GHL for CRM updates and Synthflow for callback scheduling.

---

## Key Insights

- By using PostgreSQL as the authoritative state store, the system ensures data integrity and reliability across multiple components.
- The integration of OpenAI for AI analysis allows for automated insights, reducing the manual workload for sales teams.
- Containerized deployment with Docker facilitates easy scalability and consistent environments across development and production.

---

## Final Dashboard / Project Preview

![Final Dashboard](https://raw.githubusercontent.com/KesetebirhanDelele/cora-recap-engine/main/Recap_Engine_Dashboard_Operator_Guide.png)

---

## Business Impact

- Enhanced efficiency in lead management processes, allowing teams to focus on higher-value tasks.
- Demonstrated capability in managing complex system architectures with multiple integrated components.
- Showcased practical AI engineering skills in a production-grade application, highlighting readiness for real-world challenges.

---

[← Back to portfolio](../README.md)
