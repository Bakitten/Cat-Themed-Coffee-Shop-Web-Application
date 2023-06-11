# Cat-Themed Coffee Shop Web Application

Welcome to the Cat-Themed Coffee Shop Web Application! This application combines your love for cats and coffee, creating a delightful online experience for all cat lovers out there. With adorable cat photos and a user-friendly shopping cart, you can easily browse through our menu, place orders, and even manage the application's data through phpMyAdmin.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Database Management](#database-management)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Cat-Themed Coffee Shop Web Application is designed to provide a charming and convenient way for cat enthusiasts to order their favorite coffee blends and treats. With its cute and visually appealing index page featuring adorable cat photos, it creates a warm and inviting atmosphere for customers to explore our offerings.

## Features
1. **Cat Photos**: The index page of our application displays a collection of delightful cat photos, making your browsing experience truly enjoyable.

2. **Shopping Cart**: Our user-friendly shopping cart allows you to easily add and remove items, update quantities, and review your order before checkout. It keeps track of your selected products, making the ordering process seamless.

3. **Currency Exchanger**: Catering to our foreign customers, we provide a currency exchange feature that allows you to view prices in your preferred currency. This feature ensures transparency and convenience for our international visitors.

4. **PHP Database Connection**: The Cat-Themed Coffee Shop Web Application utilizes PHP to connect to a MySQL database, enabling efficient storage and retrieval of data related to our menu, customer orders, and more. This allows for smooth management of the application's data.

## Installation

To set up the Cat-Themed Coffee Shop Web Application using XAMPP, follow these steps:

1. Download and install [XAMPP](https://www.apachefriends.org/index.html) on your local machine.

2. Clone the repository or download the source code ZIP file and extract it into the `htdocs` directory of your XAMPP installation. Rename the extracted folder to `cat-coffee-shop`.

3. Open XAMPP Control Panel and start the Apache and MySQL services.

4. Open your preferred web browser and visit `http://localhost/phpmyadmin`. This will open phpMyAdmin, the database management tool.

5. Create a new database named `cat_coffee_shop` in phpMyAdmin.

6. In the `cat-coffee-shop` folder, navigate to the `database` directory and import the provided SQL file (`cat_coffee_shop.sql`) into the `cat_coffee_shop` database. This will create the necessary tables and sample data.

7. Configure the PHP database connection in the `config.php` file located in the `cat-coffee-shop` folder. Provide the appropriate hostname, username, password, and database name for your XAMPP setup.

   ```php
   // MySQLi Configuration
   $host = 'localhost'; // Change if necessary
   $user = 'root';      // Change if necessary
   $password = '';      // Change if necessary
   $database = 'cat_coffee_shop'; // Change if necessary
   ```

8. Once the above steps are completed, open your web browser and access the application at `http://localhost/cat-coffee-shop`.

Now you can enjoy the Cat-Themed Coffee Shop Web Application on your local machine using XAMPP.

## Usage
Once the application is up and running, you can start exploring and using its features:

1. Browse the index page to enjoy the adorable cat photos.
2. Navigate to the menu section to view our offerings.
3. Add items to your shopping cart by clicking the "Add to Cart" button.
4. Manage your shopping cart by updating quantities or removing items as needed.
5. Proceed to the checkout page to finalize your order.

## Database Management
The Cat-Themed Coffee Shop Web Application integrates with a MySQL database through PHP. To manage the database:

1. Access phpMyAdmin by visiting `http://localhost/phpmyadmin` (or the appropriate URL depending on your setup).
2. Log in with your database credentials.
3. Explore the available database tables to view and modify the application's data as needed.

## Contributing
We welcome contributions from the community to enhance the Cat-Themed Coffee Shop Web Application. To contribute:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -am 'Add new feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request.

## License
The Cat-Themed Coffee

 Shop Web Application is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.
