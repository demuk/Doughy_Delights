---

# Doughy Delights Bakery

Welcome to Doughy Delights Bakery, your one-stop destination for delicious baked goods! This Flask-based e-commerce project aims to provide a seamless online shopping experience for customers to explore and purchase a variety of bakery delights, from cakes and pastries to bread and cookies.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Product Catalog**: Browse a wide selection of bakery products categorized for easy navigation.
- **Detailed Product Pages**: View detailed product descriptions, images, and prices to make informed decisions.
- **Shopping Cart**: Add products to your shopping cart and proceed to a secure checkout.
- **Order Management**: Receive order confirmation and updates via email.
- **Admin Dashboard**: Manage products and orders efficiently with an easy-to-use admin dashboard.
- **User Authentication**: Secure user authentication and authorization to protect customer data using Flask-SQLAlchemy and Werkzeug for password hashing.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/demuk/doughy-delights-bakery.git
    cd doughy-delights-bakery
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the database**:
    ```bash
    flask db init
    flask db migrate -m "Initial migration"
    flask db upgrade
    ```

5. **Run the application**:
    ```bash
    flask run
    ```

## Usage

- Navigate to `http://127.0.0.1:5000` to browse the product catalog and make purchases.
- Access the admin dashboard at `http://127.0.0.1:5000/admin` to manage products and orders.

## Project Structure

- **app/**: Contains the main application code.
  - **models.py**: Defines the database models.
  - **routes.py**: Defines the application routes.
  - **static/**: Contains static files like CSS and images.
  - **templates/**: Contains HTML templates.
- **migrations/**: Contains database migration files.
- **tests/**: Contains unit tests.
- **venv/**: Contains the virtual environment.
- **config.py**: Contains configuration settings.
- **requirements.txt**: Lists the project dependencies.
- **doughydelights.py**: Entry point for running the application.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact [yours truly](mailto:kiptoodenns@gmail.com).

---