# livraria-django

Sistema de livraria fullstack com Django, templates e upload de mídia.

## Stack

- **Lang:** Python
- **Framework:** Django
- **Banco:** SQLite (dev)
- **Deploy:** Heroku

## Como rodar

```bash
poetry install
poetry run python manage.py migrate
poetry run python manage.py loaddata livraria.json
poetry run python manage.py runserver
```
