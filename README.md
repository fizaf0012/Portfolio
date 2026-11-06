# Data Science & ML Portfolio — Fiza Fatima

Data Science graduate (COMSATS University Islamabad, 2022–2026) with hands-on experience building end-to-end AI and data-driven systems: multilingual NLP pipelines, transformer-based sentiment analysis, SQL data modeling, BI dashboards, and cloud deployments.

This portfolio collects my projects, skills, experience, and certifications. It is updated regularly.

- **Email:** [fizaf0012@gmail.com](mailto:fizaf0012@gmail.com)
- **LinkedIn:** [linkedin.com/in/fiza-fatima-aa2b9a272](https://www.linkedin.com/in/fiza-fatima-aa2b9a272/)
- **GitHub:** [github.com/fizaf0012](https://github.com/fizaf0012)
- **Location:** Islamabad, Pakistan

---

## Table of Contents

- [Featured Projects](#featured-projects)
- [More Projects](#more-projects)
- [Experience](#experience)
- [Core Competencies](#core-competencies)
- [Education](#education)
- [Certifications](#certifications)

---

## Featured Projects

### 1. PolicyPulse — AI-Powered Public Opinion Analytics Platform
*Final Year Project · COMSATS University Islamabad · NLP · Full-Stack Data Science*

<!-- Replace with your own screenshot after uploading it to Projects/PolicyPulse/screenshots/ -->
[![PolicyPulse](Projects/PolicyPulse/screenshots/dashboard.png)](Projects/PolicyPulse/)

An end-to-end AI web platform that collects, processes, and visualizes public sentiment on Pakistani government health and education policies. I collected **6,000+ multilingual records** (Urdu, Roman Urdu, English) from the YouTube Data API v3 and Pakistani news outlets (Dawn, Geo, Express Tribune), tagged by policy, region, and source.

- Designed a custom multilingual NLP pipeline: language detection, emoji normalization, slang standardization, spam filtering.
- Deployed **XLM-RoBERTa** for Positive/Negative/Neutral classification with confidence scoring, plus a keyword-based fallback for offline inference.
- Trained a **TF-IDF + Logistic Regression** chatbot with 6-category intent classification.
- Built a **7-page Streamlit dashboard**: ETS trend forecasting, citizen vs. media comparison, word clouds, political impact analysis, PDF/CSV export.
- Designed a **PostgreSQL** database and **FastAPI** backend with **JWT authentication and RBAC** (3 user roles).
- Automated the pipeline with Python subprocess orchestration and APScheduler.

**Tech:** Python · FastAPI · Streamlit · PostgreSQL · SQLAlchemy · XLM-RoBERTa · HuggingFace Transformers · PyTorch · scikit-learn · Plotly · pandas · JWT · YouTube Data API v3

📂 [Screenshots & details](Projects/PolicyPulse/)

---

### 2. Social Media Analytics — Tesla Cybertruck Brand Sentiment
*NLP · Data Visualization*

<!-- [![Tesla](Projects/Tesla-Cybertruck-Sentiment/screenshots/dashboard.png)](Projects/Tesla-Cybertruck-Sentiment/) -->

End-to-end analysis of Reddit data to evaluate public sentiment and discussion trends around the Tesla Cybertruck.

- Sentiment analysis with **VADER**, keyword extraction with **TF-IDF**, topic modeling with **LDA**.
- Delivered insights through interactive **Tableau** dashboards, with UI planning in **Figma**.

**Tech:** Python · VADER · TF-IDF · LDA · Tableau · Figma · Reddit API

🔗 [Source code (tesla-cybertruck-dashboard)](https://github.com/fizaf0012/tesla-cybertruck-dashboard)

---

### 3. Fake News Detection — Big Data Analytics
*PySpark · Machine Learning · Cloud*

<!-- [![Fake News](Projects/Fake-News-Detection/screenshots/results.png)](Projects/Fake-News-Detection/) -->

A scalable fake news classification system that processes large-scale text data with **PySpark**.

- Built a TF-IDF feature extraction pipeline.
- Trained and compared **Logistic Regression** and **Random Forest** models on accuracy and performance metrics.
- Deployed the solution on **AWS S3** for cloud-based access.

**Tech:** Python · PySpark · TF-IDF · Logistic Regression · Random Forest · AWS S3

🔗 [Source code (fake-news-api)](https://github.com/fizaf0012/fake-news-api)

---

### 4. DevOps & Cloud Engineering
*AWS · Docker · Kubernetes · CI/CD*

<!-- [![DevOps](Projects/DevOps-Cloud/screenshots/pipeline.png)](Projects/DevOps-Cloud/) -->

Hands-on DevOps work (2025 coursework) taking one full-stack app, the **Reddit Sentiment Analyzer** (React · FastAPI · PostgreSQL), from local code to production-style deployment.

- **Containerized** the app with Docker and Docker Compose; pushed images to Docker Hub and deployed on **AWS EC2**.
- Built a **Jenkins CI/CD pipeline** (Pipeline as Code) that pulls from GitHub and deploys automatically.
- Wrote **10 Selenium + pytest UI tests** and added a test stage with an HTML report to the pipeline.
- Deployed on **Kubernetes (Minikube)** with persistent storage, Nginx reverse proxy, and CPU/memory-based **autoscaling**.

**Tech:** AWS EC2 · Docker · Docker Compose · Jenkins · Selenium · pytest · Kubernetes (Minikube) · GitHub

🔗 [App code](https://github.com/fizaf0012/reddit-sentiment-analyzer) · 🔗 [Selenium tests](https://github.com/fizaf0012/reddit-selenium-tests) · 📂 [Screenshots & full walkthrough](Projects/DevOps-Cloud/)

---

### 5. Hotel Booking Cancellation Predictor
*Machine Learning · MLOps · REST API · Web App*

[![Hotel Booking Cancellation Predictor](https://raw.githubusercontent.com/fizaf0012/ml_app_assignment/main/screenshots/streamlit_app.png)](https://github.com/fizaf0012/ml_app_assignment)

An end-to-end ML application that predicts whether a hotel booking will be cancelled, from model training and experiment tracking through to a working API and web interface.

- Trained a **Random Forest** classifier (100 trees, max depth 8) and evaluated it with a **confusion matrix**, ROC curve, and precision-recall curve.
- Tracked parameters, metrics, and artifacts with **MLflow** (training accuracy 69.4%, ROC AUC 0.76).
- Served the model through a **FastAPI** REST API with a `/predict` endpoint returning the decision and cancellation probability, with Pydantic input validation.
- Built a **Streamlit** web app where users enter booking details and see the risk probability with a Low / High indicator.

**Tech:** Python · scikit-learn · Random Forest · MLflow · FastAPI · Pydantic · Streamlit

🔗 [Source code & full details](https://github.com/fizaf0012/ml_app_assignment)

---

<!--
### 6. Jobify — Recruitment Analytics & BI Dashboard  (COMING SOON)
Add this later. Repo: https://github.com/fizaf0012/Jobify-Recruitment-Analytics
-->

## More Projects

| Project | Description | Tech | Links |
|---|---|---|---|
| **FAMBZZHH** — Business Website | Responsive multi-section website (Home, About, Services, Projects, Contact). EmailJS contact form delivery and Firebase real-time database. | React · Firebase · EmailJS · HTML/CSS | [Details](Projects/FAMBZZHH-Website/) |
| **Library Management System** | Desktop app with GUI for administrators and customers: book inventory, user authentication, borrowing workflows. | Java · Advanced Java · GUI | [Details](Projects/Library-Management-System/) |
| **Bike Sharing Dashboard** | Interactive D3.js dashboard analyzing bike-sharing trends. | JavaScript · D3.js | [Repo](https://github.com/fizaf0012/Bike-Sharing-Dashboard) |
| **Excel Work** | Spreadsheet analysis and exercises. | Excel | [Repo](https://github.com/fizaf0012/EXCEL) |
<!-- Jobify row will be added here later -->

> Only PolicyPulse, FAMBZZHH, and Library Management System use a `Projects/` folder in this repo, because they have no public source code. All other projects link directly to their own repositories.

---

## Experience

### IT & Software Engineering Intern — Cymax Technologies, NSTP
*August 2026 – September 2026*

- Conducted R&D, Design of Experiments (DOE), and POC planning for an **Odoo + PostgreSQL High Availability** architecture, evaluating failover, replication, and disaster-recovery strategies across two candidate designs.
- Built a reusable **resource capacity estimation model** for application and database infrastructure sizing.
- Developed a recruitment analytics reporting dashboard using SQL views and Looker Studio.

### Data Analyst Intern — Data n Dashboards Limited, NASTP
*July 2025 – August 2025*

- Completed an 8-week Data Analytics internship at the National Aerospace Science & Technology Park (NASTP), working with diverse real-world datasets.
- Built dashboards and analytical reports in **Tableau**, focusing on data storytelling to support decision-making.

---

## Core Competencies

- **Languages:** Python, SQL, Java, HTML/CSS, JavaScript
- **Data & ML:** Pandas, PySpark, Statistics, NLP, scikit-learn, PyTorch, HuggingFace Transformers
- **Backend & Apps:** FastAPI, Streamlit, React, REST APIs, JWT/RBAC
- **Databases:** PostgreSQL, MySQL/MariaDB
- **BI & Visualization:** Looker Studio, Tableau, Plotly, Data Modeling & Dashboard Design
- **Cloud & DevOps:** AWS, Docker, Docker Compose, Kubernetes (Minikube), Jenkins, CI/CD, Git/GitHub

---

## Education

- **Bachelor of Data Science** — COMSATS University Islamabad (2022 – 2026)
- **FSc (Pre-Engineering)** — KRL Model College (2020 – 2022)
- **Matric** — KRL Model College (2018 – 2020)

---

## Certifications

- [Data Science & Analytics Internship Certification](Certificates/)
- [Introduction to Networking — Cisco](Certificates/)
- [Tinder Clone Project — Microsoft DevTown](Certificates/)

> Tip: after uploading each certificate into the `Certificates/` folder, replace the `Certificates/` link above with the exact file path, e.g. `Certificates/cisco-networking.pdf`.

---

*Last updated: November 2026*
