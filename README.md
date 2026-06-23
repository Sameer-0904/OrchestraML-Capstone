# OrchestraML

Multi-Agent Platform for Autonomous Machine Learning

## Overview

OrchestraML transforms natural language objectives into complete machine learning workflows through collaborative AI agents.

Users provide a goal such as:

> Build a customer churn prediction model

OrchestraML coordinates specialized agents to execute the ML lifecycle while keeping users involved through Human-in-the-Loop validation checkpoints.

---

## Screenshots

### Landing Page

Show the product entry experience and project positioning.

![Landing](./screenshots/landing.png)

---

### Launchpad

Natural language → ML pipeline execution.

![Launchpad](./screenshots/launchpad.png)

---

### Pipeline Execution

Multi-agent workflow with Human-in-the-Loop checkpoints.

![Pipeline](./screenshots/live_pipeline.png)

---

### Final Report

Execution summary, metrics, recommendations and artifacts.

![Report](./screenshots/report.png)

---

## Architecture

### System Architecture

![System Architecture](./architecture/system_architecture.png)

### Agent Flow

![Agent Flow](./architecture/agent_flow.png)

### Human-in-the-Loop Workflow

![HITL Workflow](./architecture/hitl_flow.png)

---

## Features

* Natural language → ML pipeline
* Multi-agent orchestration
* Automated EDA
* Data cleaning
* Feature engineering
* Model training & evaluation
* Deployment recommendations
* Final execution reports
* Human-in-the-Loop approvals

---

## Architecture (concept)

```text
User
 ↓
Orchestrator Agent
 ├── Dataset Agent
 ├── EDA Agent
 ├── Cleaning Agent
 ├── Feature Agent
 ├── Modeling Agent
 ├── Evaluation Agent
 └── Deployment Agent
```

---

## Demo Flow

1. Open Launchpad
2. Enter ML objective
3. Execute pipeline
4. Review HITL checkpoints
5. Generate final report

Example:

```txt
Build a customer churn prediction model
```

---

## Tech Stack

<!-- Badges added for a more professional appearance while keeping the original stack text -->

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/LLM-Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Gemini" />
</p>

---

## Recognition

🏆 Ranked **#24 Product of the Day** on Product Hunt

Product Hunt:
https://www.producthunt.com/products/orchestraml/launches/orchestraml

---

## Course Inspiration

Built while exploring concepts from the Google × Kaggle 5-Day AI Agents Course.

---

## Runtime Note

The current showcase deployment processes one pipeline execution at a time to maintain stable execution and consistent user experience in the demonstration environment.

The underlying architecture is designed for future scalability and support for parallel execution through infrastructure upgrades.

---

## Repository Notice

This repository is a public showcase of OrchestraML.

The production implementation remains private while the platform continues development.

Included:

* Architecture
* Screenshots
* Documentation
* Demo

Source code for proprietary orchestration is not included.

---

## Links

Website: https://orchestra-ml.vercel.app
<br>
Video Demo: https://youtu.be/7_e1PIC01X4
