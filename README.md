# Data Processing Project — Stock Market ETL

An ETL pipeline and exploratory data analysis built around stock market data for the **GLTO** ticker. Developed for the Data Processing university course.

## Overview

The project extracts raw stock data, cleans and transforms it, and loads it into a structured format ready for analysis and forecasting. A Jupyter notebook walks through the full pipeline with visualizations and commentary.

## Files

| File | Description |
|------|-------------|
| `ETL.ipynb` | Main notebook: extraction, transformation, load, and analysis |
| `GLTO_data.csv` | Raw stock market data |
| `GLTO_Clean_data.csv` | Cleaned and processed dataset |

## Tech Stack

| Category | Libraries |
|----------|-----------|
| Data processing | Pandas, NumPy |
| Database | SQLAlchemy, psycopg2, python-dotenv |
| Forecasting & ML | Prophet, scikit-learn, statsmodels |
| Geospatial | GeoPandas, Shapely, Folium |
| Visualization | Matplotlib, Seaborn, Plotly, Streamlit |
| Orchestration | Apache Airflow |

## Getting Started

```bash
pip install pandas numpy requests sqlalchemy psycopg2-binary prophet scikit-learn plotly streamlit jupyterlab
jupyter lab ETL.ipynb
```
