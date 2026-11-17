# Django Online Shop

> A simple online shop built with Django: product catalogue, cart and basic pages.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)


## Features

- Product catalogue with images.
- Shopping cart.
- Django admin for content management.
- Static assets and templates included.

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | Django |
| Database | SQLite |
| Frontend | Django templates, CSS |

## Quick Start

```bash
git clone https://github.com/dastonbek8747/django-online-shop.git
cd django-online-shop
python -m venv .venv && source .venv/bin/activate
pip install django
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Open http://localhost:8000 and the admin at http://localhost:8000/admin.

## Project Structure

```
config/     # Django project settings and URLs
news/       # shop app (models, views, templates)
static/     # CSS
```

## License

MIT © 2026 Doston Sultonov.
