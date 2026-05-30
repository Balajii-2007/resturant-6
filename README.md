# Minimal Django scaffold

Files added:

- `manage.py`
- `mysite/` (package with `settings.py`, `urls.py`, `wsgi.py`)
- `requirements.txt`

Quick start

1. Create and activate a virtual environment:

```bash
python -m venv .venv
# on Windows: .venv\Scripts\activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Apply migrations and run server:

```bash
python manage.py migrate
python manage.py runserver
```
