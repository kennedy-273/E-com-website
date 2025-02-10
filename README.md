# E-Commerce Website

This is a Django-based e-commerce website that allows users to browse products, add them to their cart, and place orders.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (signup, login, logout)
- Browse products by category
- Add products to the cart
- View cart and checkout
- View order history

## Requirements

- Python 3.8 or higher
- Django 3.1.7
- SQLite (default database)

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/kennedy-ben/E-com-website.git
    cd E-com-website
    ```

2. Create a virtual environment and activate it:

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:

    ```sh
    pip install -r requirements.txt
    ```

4. Apply the migrations:

    ```sh
    python manage.py migrate
    ```

5. Create a superuser to access the admin panel:

    ```sh
    python manage.py createsuperuser
    ```

6. Run the development server:

    ```sh
    python manage.py runserver
    ```

7. Open your browser and go to `http://127.0.0.1:8000/` to view the website.

## Usage

- **Homepage**: Browse all products and filter by category.
- **Signup/Login**: Create an account or log in to an existing account.
- **Cart**: Add products to the cart and view the cart.
- **Checkout**: Enter address and phone number to place an order.
- **Orders**: View order history.



