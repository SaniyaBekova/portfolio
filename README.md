# Saniya Bekova

M.S. candidate in Data Analytics & Computational Social Science at UMass Amherst (graduating May 2026), with ten years of backend engineering at Halyk Bank and ATF Bank in Kazakhstan. Currently focused on data engineering, applied ML, and NLP.

📍 Amherst, MA · Authorized to work in the U.S. without sponsorship

[**Portfolio site →**](https://saniyabekova.github.io) · [LinkedIn](https://linkedin.com/in/saniya-bekova) · [Email](mailto:saniyabekova@gmail.com)

---

## Featured projects

### [Fine-tuning an LLM to tell Kazakh stories](https://github.com/SaniyaBekova/kazakh-llm-finetuning)

A small-scale SFT + DPO pipeline adapting Llama-3.1-KazLLM-1.0-8B via QLoRA to generate structured Kazakh-language children's stories. Scraped 1,000+ stories from three sources, applied MinHash deduplication, curated a 240-story training corpus with control tags (age, theme, length, seed), and constructed DPO preference pairs using BERTScore F1 against gold-plan annotations. Evaluated three models against each other with automatic metrics, human judgement, and LLM-as-judge (GPT-4, Gemini).

`PyTorch` · `HuggingFace` · `QLoRA` · `SFT` · `DPO` · `BERTScore`

### [Does education spending predict math-olympiad outcomes?](https://github.com/SaniyaBekova/imo-education-analysis)

A country-year predictive model linking World Bank education indicators to International Mathematical Olympiad results. Built a panel dataset with careful entity resolution and structured handling of missingness; tuned a LightGBM regressor with cross-validation. Achieved R² 0.68, RMSE 4.71, MAE 3.11 — a 27% improvement over a linear-regression baseline.

`R` · `tidymodels` · `LightGBM`

## Also shipped

- **[NYC Taxi Batch ETL Pipeline](https://github.com/SaniyaBekova/nyc-taxi-etl)** — Spark + PostgreSQL + Docker Compose pipeline on the multi-million-row NYC TLC dataset. Distributed type casting, null filtering, feature engineering, Spark JDBC loads; raw and curated data layers cleanly separated.
- **[Diabetes Risk REST API](https://github.com/SaniyaBekova/diabetes-prediction)** — Flask REST API serving a RandomForestClassifier (77% accuracy, 0.75 F1) with `/predict` and `/reload` endpoints. PostgreSQL feature store, Streamlit UI, Swagger docs, deployed to Render. pytest integration tests for endpoint contracts and online retraining.
- **[Cinema Affordability across Kazakhstan](https://github.com/SaniyaBekova/cinema-affordability-kz)** — How many minutes of work does it take to afford a movie ticket in different Kazakh cities? Selenium scraping of cinema schedules from 10+ cities, merged with city-level average-salary data, interactive Streamlit + Plotly dashboard deployed on Streamlit Cloud.
- **[Nobel Prize Laureates — Exploratory Analysis](https://github.com/SaniyaBekova/Nobel_Prize)** — Exploratory data analysis of Nobel laureates over time: country dominance, category breakdowns, age and gender distributions. Joined with World Bank GDP and population data; outputs include an interactive map and a bar-race animation.

## What I'm doing now

- **Spring 2026** — TA for *Machine Learning for Social Scientists* at UMass; finishing coursework toward the M.S.
- **May 2026** — graduating from DACSS at UMass Amherst.
- **Job-searching** — data engineer · ML engineer · software engineer · data scientist roles, with interest in fintech, financial services, and applied ML / AI companies.

## Background

Ten years of production backend engineering across two Kazakh banks:

- **Halyk Bank** (Kazakhstan's largest bank — 10M+ customers, ~$25B in assets) — Senior Backend Developer (2019–2024). Architected the .NET monolith → CQRS microservices migration with Kafka event sourcing, reducing mortgage approval time by 80% (2 weeks → 2–3 days) for 400+ concurrent users. Built a Go + Kafka + PostgreSQL platform that onboarded 1,000+ enterprise clients onto a previously paper-based tender process.
- **ATF Bank** (top-10 Kazakhstani commercial bank) — Software Developer (2018–2019). Replaced a BizTalk integration layer with a RabbitMQ event mesh + Oracle backend, cutting loan-issuance latency by 69% (47 min → <15 min).
- **Halyk Bank** (earlier) — Software Developer → Team Lead (2013–2018). Owned the Collateral Loans module end-to-end; led the retail-lending workstream of the Halyk–Kazkommertsbank merger.

## Toolkit

| | |
|---|---|
| **Languages** | Python · R · SQL · PL/SQL · Go · C# |
| **ML / NLP** | PyTorch · scikit-learn · HuggingFace · QLoRA · SFT · DPO · LightGBM · BERTScore |
| **Data** | Apache Spark · Kafka · RabbitMQ · PostgreSQL · Oracle · MSSQL · Prefect · pandas |
| **Backend** | Microservices · CQRS · Event sourcing · REST / SOAP · .NET Core · Flask |
| **Ship** | Docker · AWS (EC2, RDS) · Git · pytest · Camunda 7 |
| **Human languages** | Kazakh · Russian · English |

---

