# Adaptive-AI-Based-Financial-Anomaly-Detection-System-


## Team Members

| Name | ID Number |
|---|---|
| MahaLakshmi |2420030313 |
| Sreehitha | 2420030410 |
| Lahari | 2420030055 |



## Abstract

Small and Medium Enterprises (SMEs) increasingly conduct their operations through digital transactions but rarely have access to enterprise-grade fraud and anomaly detection tools, leaving irregular cash flow, invoicing, and payment activity largely unmonitored. This project proposes a web-based Adaptive AI-Based Financial Anomaly Detection System that combines machine learning with statistical and behavioral analysis to flag unusual SME financial transactions. Its central objective is to build an SME-specific behavioral baseline that reflects the normal transaction patterns of an individual business rather than applying generic, one-size-fits-all thresholds. Anomaly scoring uses a hybrid methodology that integrates the Isolation Forest algorithm (via Scikit-learn) with statistical measures computed using Pandas and NumPy, allowing the system to identify both isolated outlier transactions and gradual behavioural drift. The core novelty of the work is its feedback-driven adaptation mechanism: administrators review flagged anomalies and label them as genuine or false positives, and this feedback is used to progressively refine the SME’s baseline and improve detection quality over time. As an Adaptive Software Engineering project, development follows an Agile methodology, with Jira used to manage the product backlog, user stories, sprint planning, and task and bug tracking across iterations. The system is implemented with a React.js frontend and a Python FASTAPI backend, with transaction and feedback data stored in an SQLite database, Postman used for API testing, and Git/GitHub used for version control. The expected outcome is a working prototype that demonstrates more business-specific and adaptive anomaly detection than static rule-based approaches, giving SME administrators an interpretable tool for monitoring financial irregularities within a short academic development timeframe.

## Technologies Used

React.js, Python,  FASTAPI , Scikit-learn, SQLite, Jira, GitHub

## Setup and Execution Instructions



```bash
git clone <your-github-repository-link>
cd <project-folder>
