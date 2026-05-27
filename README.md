# Society to Music Analytics  
### From Global News Sentiment to Music Listening Behavior

This project explores whether global news sentiment is connected to how people listen to music across countries and time.

As part of a collaborative analytics project, we built an end-to-end data pipeline using Spotify streaming data, Spotify audio features, and GDELT global news sentiment data. The goal was to understand whether large world events and changes in public sentiment could be reflected in music mood, listening behavior, and emotional audio patterns.

---

## Core Question

Can global news sentiment help explain shifts in music listening behavior?

More specifically, we wanted to understand whether changes in news tone were associated with changes in music features such as valence, energy, joy, sadness, fear, and anger.

---

## Data Sources

| Dataset | Purpose |
|---|---|
| Spotify Charts | Country-level music streaming behavior |
| Spotify Audio Features | Song-level mood and audio indicators |
| GDELT News Sentiment | Global news tone and emotion signals |

---

## Tech Stack

| Area | Tools |
|---|---|
| Programming | Python, SQL |
| Big Data | PySpark |
| Pipeline Orchestration | Kedro |
| Cloud | Google Cloud Platform, Dataproc, Google Cloud Storage |
| Warehouse | Snowflake |
| Local Analytics | DuckDB |
| Dashboard | React, FastAPI |
| Collaboration | GitHub |

---

## Pipeline Overview

```text
Spotify + GDELT Data
        ↓
Data Cleaning + Standardization
        ↓
Country-Date Level Aggregation
        ↓
Feature Engineering
        ↓
Statistical Analysis
        ↓
Dashboard + Insights
