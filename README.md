# Learn Django

Worked examples from the official Django documentation, kept together while learning the framework.

## Contents

- `djangotutorial/` — the "Writing your first Django app" tutorial: the `mysite` project with a `polls` app (`Question`/`Choice` models, class-based index/detail/results views, voting).
- `news/` — the app from the Django overview docs: `Reporter`/`Article` models and a `year_archive` view.

## Built with

- Django
- SQLite

## Run it

```bash
python -m venv .venv && source .venv/bin/activate
pip install django
cd djangotutorial
python manage.py migrate
python manage.py runserver
```

Learning project following the official Django docs.
