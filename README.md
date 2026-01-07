# Dolam Payments Platform

Production-ready Django fintech platform (MonCash-compatible), audited and secured.

## Features
- Secure payment flow
- Webhooks
- Admin dashboard
- Refund tracking
- Invoice PDFs
- REST API
- Hash-locked dependencies

## Setup
1. python -m venv venv
2. source venv/bin/activate
3. pip install --require-hashes -r requirements.txt
4. python manage.py migrate
5. python manage.py runserver
