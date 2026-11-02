# Akshat Kothari — Tableau EV Reference

A separate Flask website that embeds two Tableau Public visualizations shared by Akshat Kothari. The page clearly credits the original creator and does not claim ownership.

## Included visualizations

- Dashboard: `Dashboard1_17936379054230/Dashboard1`
- Story: `3TYCX9NSN`

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

Open http://127.0.0.1:5000.

## Deploy on Render

- Build command: `pip install -r requirements.txt`
- Start command: `gunicorn app:app`

The Tableau visualizations are hosted by Tableau Public. They must remain publicly accessible for the embeds to load. This is a reference page, not a copy of the original Tableau workbook.
