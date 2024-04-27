## E-Commerce Website with Django
This is a simple e-commerce website built using Django, a high-level Python web framework. The project aims to provide a basic foundation for building an online store, with features such as user authentication, product management, cart functionality, and order processing.

## Features
User Authentication: Allow users to sign up, log in, and log out securely.
Product Management: Add, edit, and delete products from the admin dashboard.
Product Catalog: Display products with details such as name, price, and description.
Shopping Cart: Enable users to add products to their cart for future purchase.
Order Processing: Allow users to place orders and track their order history.
Responsive Design: Ensure the website is accessible and usable across different devices.
## Installation
1.Clone the repository:
```bash
git clone https://github.com/tasnimlima07/ecom_django.git


Navigate into the project directory:
```bash
cd ecom_django

Install dependencies:
```bash
pip install -r requirements.txt

Apply database migrations:
bash
Copy code
python manage.py migrate
Create a superuser (admin):
bash
Copy code
python manage.py createsuperuser
Run the development server:
bash
Copy code
python manage.py runserver
Access the website in your browser at http://127.0.0.1:8000/.
Usage
To access the admin dashboard, go to http://127.0.0.1:8000/admin/ and log in with the superuser credentials created earlier.
Add products via the admin interface to populate the product catalog.
Users can sign up or log in to their accounts to access features such as adding products to the cart and placing orders.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/my-feature).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/my-feature).
Create a new pull request.
License
This project is licensed under the MIT License.

Acknowledgements
This project was inspired by Django, a high-level Python web framework.
Special thanks to tasnimlima07 for initiating this project.
