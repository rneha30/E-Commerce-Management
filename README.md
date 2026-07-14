E-Commerce Management README:

E-Commerce Management (Online Shopping Portal)

Simple overview of use/purpose:
A PHP and MySQL based online shopping portal that lets users browse products, add them to a cart, and checkout, while an admin panel allows managing users, products, categories, brands, and orders.

 Description

Computers and the internet have made purchasing everyday items as easy as a mouse click. This project, the Online Shopping Portal, is a GUI-based automated e-commerce system covering products such as mobile phones, laptops, clothes, books, and electronic items. Users can register an account, log in, browse products by category, add items to their cart, and check out with payment details. An admin dashboard allows adding/removing brands, categories, and products, as well as managing registered users and viewing orders. The project uses a relational database (MySQL) to store users, products, cart, and order information, with the schema normalized to reduce redundancy and maintain data integrity.

Getting Started

Dependencies

* XAMPP or WAMP server (Apache + MySQL/MariaDB + PHP)
* PHP (tested with standard XAMPP PHP version)
* MySQL / MariaDB database
* A web browser with JavaScript enabled (Chrome, Firefox, or IE 7.0+)
* OS: Windows, Linux, or macOS (developed on Windows XP era stack, but works on modern OS with XAMPP)

 Installing

* Download or clone this repository
* Install XAMPP (or WAMP) and start the Apache and MySQL/MariaDB services
* Copy the project folder into your server's root directory (e.g. htdocs for XAMPP)
* Import the provided database SQL file into MySQL/MariaDB via phpMyAdmin to create the ecommerce database (tables include admin_info, brands, cart, categories, email_info, logs, orders, orders_info, order_products, products, user_info, user_info_backup)
* Update the database connection credentials (host, username, password, database name) in the project's config file if they differ from the defaults

 Executing program

* Start Apache and MySQL/MariaDB from the XAMPP/WAMP control panel
* Open a browser and navigate to:

http://localhost/<project-folder-name>/

* As a user:
  * Register a new account, or log in with existing credentials
  * Browse categories, add products to your cart
  * Proceed to checkout and enter payment/shipping details to place an order
* As an admin:
  * Log in through the admin login page
  * Manage brands, categories, and products (add/delete)
  * View and manage registered users
  * View and manage customer orders

 Help

* If the site doesn't load, confirm Apache and MySQL are both running in the XAMPP/WAMP control panel
* If you see database connection errors, double check the database credentials and that the ecommerce database has been imported correctly
* Make sure your browser has JavaScript enabled — some pages rely on it for interactivity
* "Not currently tracking stock/quantity" and "no report generation" are known limitations, not bugs (see Future Enhancements below)

 Version History

* 0.2
    * Various bug fixes and optimizations
    * See commit change or release history
* 0.1
    * Initial Release

 Future Enhancements

* Stock/quantity tracking for products
* Monthly/yearly sales reporting
* AI/ML-based personalized recommendations
* Blockchain integration for transaction transparency and security



* Elmasri & Navathe – "Fundamentals of Database Systems" (7th Edition, 2017)
* Ramakrishnan and Gehrke – Database System (2014)
* Thomas A. Powell – "HTML and XHTML: The Complete Reference"
* Kevin Yank – "PHP & MySQL Novice to Ninja"
* W3Schools (w3schools.org)
