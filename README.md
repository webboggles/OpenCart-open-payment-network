Disclaimer: Please note that we no longer support older versions of SDKs and Modules. We recommend that the latest versions are used.

# README

# Contents

- Introduction
- Prerequisites
- Installing and configuring the module
- License

# Introduction

This OpenCart module provides an easy method to integrate with the payment gateway.
 - Supports Open versions: **3.X**

# Prerequisites

- The module requires the following prerequisites to be met in order to function correctly:
    - The 'bcmath' php extension module: https://www.php.net/manual/en/book.bc.php

> Please note that we can only offer support for the module itself. While every effort has been made to ensure the payment module is complete and bug free, we cannot guarantee normal functionality if unsupported changes are made.

# Installing the module.

1. Zip the upload folder and rename it upload.ocmod so the full filename is upload.ocmod.zip 
2. Navigate to the Extensions dropwon -> Installer
3. Upload the module useing the installer's upload option

# Installing the module option 2

You can also install the module by copying the upload folder into the root OpenCart directory

# Configuring the module

1. Navigate to the Extensions dropdown -> Extensions -> Payment methods -> PaymentNetwork and click 'Activate'
2. Navigate to the Extensions dropdown -> Extensions -> Payment methods -> PaymentNetwork and click the 'Edit' button
3. Enter your MerchantID / Secretkey and update the customer/country code
4. Select what type of integration you would like to use
5. Set what status you would like to update an order to once paid
6. Set the Enabled option to true
7. Click 'Save Changes'

License
----
MIT
