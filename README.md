<div align="center">

# 🌍 Society to Music Analytics
### *Understanding How Global News Sentiment Shapes Music Listening Behavior*

<img src="images/architecture_diagram.png" width="85%"/>

---

### Cloud-Scale Analytics Pipeline  
**Spotify · GDELT · PySpark · Snowflake · GCP · React**

</div>

---

# 🎯 Project Vision

Music is deeply connected to emotion, behavior, and social context.

This project explores whether large-scale global events and changes in public sentiment are reflected in how people listen to music across countries and time.

Using Spotify streaming behavior, Spotify audio features, and GDELT global news sentiment data, our team built a scalable cloud-based analytics pipeline to study the relationship between news sentiment and consumer listening behavior between 2017–2021.

The project combines:

- distributed data engineering
- cloud infrastructure
- ETL pipeline orchestration
- sentiment aggregation
- statistical analysis
- and visualization-driven storytelling

---

# 🧠 Core Question

<div align="center">

## *Can global news sentiment influence music listening behavior?*

</div>

We specifically explored whether changes in news tone were associated with shifts in:

- music mood
- emotional listening patterns
- streaming behavior
- and country-level listening trends

---

# 📊 Data Sources

| Dataset | Purpose |
|---|---|
| 🎵 Spotify Daily Charts | Country-level streaming behavior |
| 🎧 Spotify Audio Features | Emotional and audio characteristics |
| 📰 GDELT News Sentiment | Global news tone and sentiment indicators |

The analysis focused on multiple English-speaking countries and major world events including:
- COVID-19
- Brexit
- elections
- geopolitical events
- economic disruptions

---

# ⚙️ Technical Stack

<div align="center">

| Area | Technologies |
|---|---|
| Programming | Python · SQL |
| Big Data | PySpark |
| Orchestration | Kedro |
| Cloud Infrastructure | Google Cloud Platform |
| Distributed Compute | Dataproc |
| Storage | Google Cloud Storage |
| Data Warehouse | Snowflake |
| Local Analytics | DuckDB |
| CI/CD | GitHub Actions |
| Backend | FastAPI |
| Frontend | React + Vite |
| Containerization | Docker |

</div>

---

# 🏗️ Architecture Overview

<div align="center">

<img src="images/pipeline_flow.png" width="95%"/>

</div>

The project was designed as a scalable cloud-based analytics workflow capable of processing large multi-source datasets across countries and time periods.

---

# 🔄 End-to-End ETL Workflow

## 📥 Extract

The pipeline ingests:

- Spotify streaming chart data
- Spotify audio feature datasets
- GDELT global sentiment datasets

across multiple years and geographic regions.

---

## 🔧 Transform

The transformation layer performs:

- schema standardization
- missing value handling
- duplicate removal
- country/date alignment
- sentiment aggregation
- feature engineering
- stream-weighted emotional scoring

Key engineered indicators included:
- valence
- energy
- joy
- anger
- sadness
- fear
- acousticness
- danceability

---

## 📤 Load

Curated outputs were loaded into analytical tables used for:
- dashboarding
- trend analysis
- correlation analysis
- lag analysis
- country-level comparisons

---

# ☁️ Cloud Workflow & CI/CD

<div align="center">

<img src="images/cicd_flow.png" width="90%"/>

</div>

The project used a production-style workflow integrating:

- GitHub Actions
- Docker
- Google Cloud Workflows
- Dataproc
- Snowflake

The automation pipeline supported:
- Docker builds
- artifact deployment
- automated Spark execution
- cloud orchestration
- Snowflake updates
- logging and cleanup

---

# 📈 Dashboard & Visualization

<div align="center">

<img src="images/dashboard_screenshot.png" width="92%"/>

</div>

The dashboard was built to explore:

- global sentiment trends
- emotional listening behavior
- lagged response patterns
- country-level comparisons
- streaming trend changes over time

The goal was to transform large-scale analytical outputs into interpretable behavioral insights.

---

# 🔍 Key Findings

<div align="center">

| Finding | Result |
|---|---|
| Correlation between sentiment and music mood | ~0.37 |
| Strongest behavioral response window | ~24 hours |
| Countries analyzed | Multiple English-speaking markets |
| Data coverage | 2017–2021 |

</div>

Additional findings included:
- measurable behavioral response patterns following major world events
- emotional audio shifts during periods of negative sentiment
- lag-based relationships between public sentiment and listening behavior

---

# 👩🏻‍💻 My Contributions

This was a collaborative team project, and my work focused primarily on cloud setup, pipeline support, data integration, and workflow validation.

---

## ☁️ Google Cloud Platform Setup

I led the initial Google Cloud setup for the project, including:

- configuring the GCP project environment
- setting up Google Cloud Storage buckets
- enabling required APIs and services
- helping manage teammate access permissions
- coordinating Dataproc-related access setup

---

## ⚙️ Pipeline & Data Engineering Support

I contributed to ETL workflow development by:

- working with PySpark and Kedro pipelines
- supporting data cleaning and transformation workflows
- validating multi-source dataset consistency
- helping structure country/date joins
- testing local and cloud-based pipeline execution

---

## 🔗 Data Integration & Validation

I helped support integration across:
- Spotify charts
- Spotify audio feature datasets
- GDELT news sentiment outputs

This included:
- validating transformed outputs
- checking schema consistency
- aligning datasets by country and date
- ensuring final analytical tables were analysis-ready

---

## 🚀 Cloud Workflow Exposure

I also worked on understanding and supporting:
- Dataproc distributed processing
- Snowflake integration
- CI/CD workflow structure
- GitHub Actions automation
- production pipeline execution

---

## 📊 Analytics & Dashboard Support

I contributed to:
- interpreting transformed outputs
- validating downstream analytical tables
- connecting curated datasets to dashboard requirements
- supporting visualization-driven insight generation

---

# 🧩 What This Project Demonstrates

This project strengthened my experience in:

✅ cloud analytics workflows  
✅ distributed data processing  
✅ ETL pipeline orchestration  
✅ multi-source data integration  
✅ analytics engineering  
✅ dashboard-driven storytelling  
✅ statistical and behavioral analysis  
✅ collaborative GitHub workflows  

---

# 📁 Repository Structure

```bash
society-to-music-analytics/
│
├── README.md
│
├── images/
│   ├── architecture_diagram.png
│   ├── pipeline_flow.png
│   ├── cicd_flow.png
│   └── dashboard_screenshot.png
│
├── docs/
│   ├── project_summary.md
│   ├── my_contributions.md
│   └── etl_pipeline_overview.md
│
├── notebooks/
│   └── analysis_sample.ipynb
│
└── src/
    ├── data_cleaning.py
    ├── feature_engineering.py
    └── analysis.py
