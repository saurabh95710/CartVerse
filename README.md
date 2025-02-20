# E-Commerce Website

## Description
This is a fully functional e-commerce website built using PHP, HTML, AJAX, jQuery, and JavaScript, running on an Apache server with XAMPP. The project supports user authentication, product management, cart functionality, and order processing.

## Features
- User authentication (login, registration, logout)
- Product listing and search
- Shopping cart functionality
- AJAX-based add-to-cart and remove-from-cart features
- Order placement and management
- Admin panel for product and order management

## Technologies Used
- **Backend:** PHP, MySQL
- **Frontend:** HTML, CSS, JavaScript, jQuery, AJAX
- **Server:** Apache (XAMPP)

## Installation
### Prerequisites
- XAMPP installed on your system
- Web browser (Chrome, Firefox, etc.)

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecommerce-website.git
   ```
2. Move the project folder to the XAMPP `htdocs` directory:
   ```bash
   mv ecommerce-website /xampp/htdocs/
   ```
3. Start Apache and MySQL in XAMPP.
4. Import the database:
   - Open phpMyAdmin (`http://localhost/phpmyadmin/`)
   - Create a new database (e.g., `ecommerce_db`)
   - Import the provided SQL file (`database/ecommerce_db.sql`)
5. Configure database connection:
   - Open `config/db.php` and update credentials:
   ```php
   define('DB_HOST', 'localhost');
   define('DB_USER', 'root');
   define('DB_PASS', '');
   define('DB_NAME', 'ecommerce_db');
   ```
6. Open the project in a browser:
   ```
   http://localhost/ecommerce-website/
   ```

## Usage
- **User:** Register/login, browse products, add to cart, place orders.
- **Admin:** Manage products, view and process orders.

## Folder Structure
```
/ecommerce-website/
│── index.php        # Homepage
│── config/
│   └── db.php      # Database connection
│── assets/
│   ├── css/
│   ├── js/
│── includes/
│   ├── header.php
│   ├── footer.php
│── products/
│── cart/
│── admin/
│── database/
│   └── ecommerce_db.sql  # Database schema
```

## Contributing
Feel free to contribute by creating pull requests or opening issues.

## License
This project is licensed under the MIT License.

## Contact
For any queries, contact: [your email or GitHub profile]
