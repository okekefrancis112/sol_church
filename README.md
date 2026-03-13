# Sol Church

A Django web application for a church organization with Paystack payment integration for donations and board management.

## Overview

A church management platform built with Django, featuring board/mission management, Paystack integration for processing donations and payments, and member accounts.

## Features

- **Board Management** — Create and manage church boards/missions
- **Paystack Integration** — Payment processing for donations
- **User Accounts** — Member registration and authentication
- **Content Pages** — About, home, and mission field pages

## Tech Stack

- **Python** 3.x
- **Django** — Web framework
- **Paystack** — Payment gateway
- **HTML/CSS** — Frontend templates

## Getting Started

```bash
git clone https://github.com/okekefrancis112/sol_church.git
cd sol_church
cp .env.example .env
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Project Structure

```
├── board/
│   ├── models.py          # Board models
│   ├── views.py           # Board views
│   ├── forms.py           # Django forms
│   ├── paystack.py        # Paystack integration
│   └── templates/         # HTML templates
├── accounts/              # User management
└── manage.py
```

## License

MIT
