# Gazara Grocery Store - Test Cases Repository 
# Overview 
The Gazara Grocery Store  is a multi-platform application (Mobile App, Web App, and Admin Panel) that allows users to shop for groceries online. This repository focuses on testing the system's functionality to ensure it works as expected under different scenarios. 

## Test Case Files
1. Valid Test Cases 
    - Contains step-by-step test cases for validating the functionality under normal conditions.
2. Invalid Test Cases 
    - Contains step-by-step test cases for validating the response to incorrect or unexpected inputs.
### Mobile Application Test Cases 
File : `MobileApplication.csv`
- Contains step-by-step test cases for the mobile application's functionality.
- Covers scenarios including:

  1- Sign-Up : Phone number, email, social media login (Facebook/Google).

  2- Login : Valid and invalid credentials, forgot password flow.

  3- Cart and Favorites Management : Adding/removing items, handling out-of-stock items, and cart persistence.

  4- Payment Processing : Credit card validation, first-time orders restrictions, and order cancellation.

  5- Offline Mode : Behavior when internet connectivity is lost.

  6- Real-time stock updates.

  7- Profile editing.
             
### Web Application Test Cases
File : `WebSite.csv`
 
- Contains step-by-step test cases for the web site's functionality.
- Covers scenarios including:

  1- Sign-Up and Login : email, social media login (Facebook/Google), forgot password flow..

  2- Home Page and Cart : UI, Adding/removing items, and cart persistence.

  3- Payment Processing : Credit card validation, first-time orders restrictions.

  4- Offline Mode : Behavior when internet connectivity is lost.

  5- Real-time stock updates.
  
  6- Profile editing.   
  
### Admin Panel Test Cases (Coming Soon) 
Will include test cases for the admin dashboard, including user management, inventory updates, and order tracking.


## Tools and Frameworks 
The following tools and frameworks were used to design, manage, and execute the test cases: 

1- Zephyre : 
  - Zephyre was used as the primary test case management tool for organizing, executing, and tracking the test cases in this repository.
  - It provides a structured approach to defining test steps, test data, and expected results, ensuring clarity and consistency across all test cases.
         
2- CSV Format : 
  - Test cases are exported from Zephyre into .xlsx then to .csv files for version control and ease of collaboration via GitHub.
         
  
