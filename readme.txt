# Online Food Ordering Website

Welcome to the repository for the Online Food Ordering Website. This project is developed using PHP, JavaScript, HTML, and CSS. This web application allows users to browse a menu, add items to their cart, and place orders online.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- User registration and login capabilities
- Browse and search an extensive menu
- Add items to your cart
- Update quantities and remove items from the cart
- Place orders and view order history
- Admin panel for managing menu items and order statuses
- Responsive design for mobile and desktop viewing

## Installation

### Prerequisites
1. Web server (e.g., Apache)
2. PHP (>=7.4)
3. MySQL database
4. Composer (for PHP dependencies)

### Manual Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/harsi15/Foody.git
    ```

2. Navigate into the project directory:
    ```sh
    cd online-food-ordering
    ```

3. Install PHP dependencies using Composer:
    ```sh
    composer install
    ```

4. Create a `.env` file from `.env.example` and fill in your database credentials:
    ```sh
    cp .env.example .env
    ```
    ```ini
    DB_HOST=your_db_host
    DB_NAME=your_db_name
    DB_USER=your_db_user
    DB_PASS=your_db_password
    ```

5. Start your local development server:
    ```sh
    php -S localhost:8000
    ```

6. Open your browser and navigate to:
    ```
    http://localhost:8000
    ```

## Usage
- Register a new user account or log in with an existing account.
- Browse the menu and add items to your cart.
- Review your cart and proceed to checkout.
- Place your order and view the order status in the order history section.
- Admin users can log into the admin panel to manage menu items and order statuses.


## Contributing
We welcome contributions from the community. To contribute:
1. Fork the repository.
2. Create a new feature branch:
    ```sh
    git checkout -b feature-branch-name
    ```
3. Commit your changes:
    ```sh
    git commit -m "Add some feature"
    ```
4. Push to the branch:
    ```sh
    git push origin feature-branch-name
    ```
5. Open a Pull Request.

## Contact
For any questions or feedback, please open an issue or reach out to us.

---

Thank you for using our Online Food Ordering Website! We hope you find it useful and enjoyable. Happy ordering!  
