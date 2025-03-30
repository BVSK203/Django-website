# Django-website
# Django E-Commerce Website

## Overview
This is a fully functional e-commerce website built using **Django** and **Bootstrap**. The project includes user authentication, product management, cart functionality, order processing, and an admin dashboard.

## Features
- User authentication (Register, Login, Logout)
- Product listing and categorization
- Shopping cart functionality
- Order management system
- Admin dashboard for managing products and orders
- Media file handling for product images
- Responsive design with Bootstrap

## Installation
### Prerequisites
Ensure you have Python installed (recommended: Python 3.8+). You also need `pip` and `virtualenv`.

### Steps to Set Up
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/django-ecommerce.git
   cd django-ecommerce
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run migrations:
   ```sh
   python manage.py migrate
   ```
5. Create a superuser for admin access:
   ```sh
   python manage.py createsuperuser
   ```
6. Start the development server:
   ```sh
   python manage.py runserver
   ```
7. Open the website in your browser:
   ```sh
   http://127.0.0.1:8000/
   ```

## Project Structure
```
├── accounts/         # User authentication
├── cart/             # Shopping cart functionality
├── dashboard/        # Admin dashboard
├── media/products/   # Product images
├── online_shop/      # Main project folder
├── orders/           # Order management
├── shop/             # Product listing and details
├── db.sqlite3        # Database file (SQLite)
├── requirements.txt  # Dependencies
├── README.md         # Project documentation
```

## Technologies Used
- **Backend:** Django, SQLite.
- **Frontend:** HTML, CSS, Bootstrap , javascript.
- **Authentication:** Django Auth System.

## Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License.


