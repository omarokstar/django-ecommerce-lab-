# Django E-Commerce System (DRF Backend)

This project is a web-based E-Commerce System built with Django and Django REST Framework (DRF). It provides a backend API-driven structure for building a modern online store, supporting user authentication, product management, shopping cart, and order processing via RESTful APIs.

## Features

- User registration, login, and profile (JWT authentication)
- Product categories and listings
- Shopping cart management
- Checkout and order processing
- Order history and admin management

## Getting Started

1. Create and activate the virtual environment:
   ```powershell
   python -m venv .venv
   .venv\Scripts\Activate.ps1
   ```
2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```
3. Run migrations:
   ```powershell
   python manage.py migrate
   ```
4. Create a superuser:
   ```powershell
   python manage.py createsuperuser
   ```
5. Start the development server:
   ```powershell
   python manage.py runserver
   ```

## API Endpoints

- `/api/auth/` - User authentication (register, login, profile)
- `/api/categories/` - Product categories
- `/api/products/` - Product listings and details
- `/api/cart/` - Shopping cart
- `/api/orders/` - Checkout and order management

## Notes

- Update `.env` or settings as needed for production.
- See `.github/copilot-instructions.md` for Copilot customization.
