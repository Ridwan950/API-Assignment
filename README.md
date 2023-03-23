# API-Assignment 
This is a PHP Assignment to create a RESTful API
# API_protect
# API_protect Requirement
API tester(POSTMAN), LAMP/XAMP/WANMP

#instalation
clone/Download the project filr to the htdocs server directory
create a database in the localhost/phpmyadmin panel "clothing-company"
import the sql database in the confiq folder
make sure the database details specified in  the confiq/database.php file matches with the apache web-servweer details.
on linux os, make sure to attivate the PDO

#running
open and create a new http request in your POSTMAN application

#End point
http://localhost/API_Project/api/projects/read_single.php?product.id=5
TO read a single product from the product table in the database clumn by passing the product-id parameter
http://localhost/API_Project/api/projects/read.php

To read all the product from the database 

http://localhost/API_Project/api/projects/read_single.php?customer.id=3
To read a sngle customer from the customer from the customer table the customer table in the database column by passing the product_id parameter

http://localhost/API_Project/api/customer/read.php
To read all the customer from the database

