# E-Commerce Website with Django

This is a simple e-commerce website built using Django, a high-level Python web framework. The project aims to provide a basic foundation for building an online store, with features such as user authentication, product management, cart functionality, and order processing.

![Example Image](media/item_images/ecom.png)


## Features
- **Multiple Vendors**: The platform allows multiple vendors to sign up and create their own storefronts to sell products. Each vendor has their own dashboard to manage their products, orders, and store settings.
- **Product Listings**: Vendors can add, edit, and delete their products from their dashboard. They can specify product details such as title, description, price, quantity, and images.
- **Analytics and Reporting**: endors have access to sales analytics and reports within their dashboard. They can track sales performance, monitor inventory levels, and identify trends to optimize their business strategies.
- **User Authentication**: Allow users to sign up, log in, and log out securely.
- **Product Management**: Add, edit, and delete products from the admin dashboard.
- **Product Catalog**: Display products with details such as name, price, and description.
- **Contact Seller**: Enable users to message the seller etc

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/tasnimlima07/ecom_django.git
    ```

2. Navigate into the project directory:

    ```bash
    cd ecom_django
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

5. Create a superuser (admin):

    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

7. Access the website in your browser at `http://127.0.0.1:8000/`.

## Usage

- To access the admin dashboard, go to `http://127.0.0.1:8000/admin/` and log in with the superuser credentials created earlier.
- Add products via the admin interface to populate the product catalog.
- Users can sign up or log in to their accounts to access features such as adding products to the cart and placing orders.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/my-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/my-feature`).
6. Create a new pull request.


## Acknowledgements

- This project was inspired by [Django](https://www.djangoproject.com/), a high-level Python web framework.
