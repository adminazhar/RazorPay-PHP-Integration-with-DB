# RazorPay-PHP-Integration-with-DB
Razorpay Payment Gateway Integration(PHP,MySQL) with Custom Form Page and Database insertion when the payment is successful.

## How to Use

1. Change the API KEY and API SECRET KEY in config.php

   ```sh
   $keyId = 'rzp_test_9TB3asShG3RvdV';
   $keySecret = 'zrpWBMrytnHq5UMUeVikNgfn';
   ```
2. Change the Database Connection in config.php
   ```sh
   $host = "localhost";
   $username = "root";
   $password = "root";
   $dbname = "gothamshop";
   ```
3. Import the database.sql in your database or create below table
   ```sh
   id int(255) NOT NULL
   order_id varchar(255) NOT NULL
   razorpay_payment_id varchar(255) NOT NULL
   status varchar(50) NOT NULL,
   email varchar(50) NOT NULL,
   price int(50) NOT NULL
   ```
