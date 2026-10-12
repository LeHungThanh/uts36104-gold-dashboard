# Gold dashboard

A Streamlit dashboard for UTS 36104 Data Visualisation and Narratives, Session 3 Part A. It presents gold price, ETF holdings, declared official-sector activity, inferred demand, and Swiss exports.

The dashboard uses course-provided **sample data** for practice.

## Run locally

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

## Deploy

The Streamlit Community Cloud entrypoint is `app.py`. Keep `app.py`, `design.py`, `requirements.txt`, and `data/` at the repository root when deploying.

## Project files

- `app.py` — Streamlit dashboard and charts
- `design.py` — shared colours and visual design tokens
- `data/` — supplied sample CSV data
- `ingest.py` — optional sample/live data-ingestion helper from the supplied starter
