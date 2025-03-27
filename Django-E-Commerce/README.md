
# TO run this file

pip install django
python manage.py runserver

# Django E-Commerce

A simple e-commerce website built with Django, featuring product browsing, cart management, and payment processing via PayPal (with Stripe mentioned as an alternative).

## Project Summary

This project allows users to:

- Browse and view products.
- Add/remove items to/from a cart and adjust quantities without logging in.
- Enter a shipping address and complete purchases using a payment gateway.

The application is designed for learning purposes, showcasing Django's MVT architecture and third-party API integration.

## Features

- **Product Display**: Lists products with details like name, price, and image.
- **Cart Management**: Session-based cart for unauthenticated users.
- **Checkout**: Address input and payment processing via PayPal (or Stripe).
- **Admin Interface**: Manage products (assumed via Django admin).

## Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS
- **Database**: SQLite (default, configurable)
- **Payment Gateway**: PayPal (Stripe referenced)
