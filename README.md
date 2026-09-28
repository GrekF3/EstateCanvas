# Real Estate Showcase

A Django showcase for residential properties, apartment selection, and mortgage enquiry flows.

## Run locally

```bash
cd skazka
python -m venv .venv
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Lead notifications are optional and configured through Telegram environment variables.
