# Gazara Grocery Store - Test Cases Repository

# Overview
The Gazara Grocery Store is a multi-platform application (Mobile App, Web App, and Admin Panel) that allows users to shop for groceries online. This repository focuses on testing the system's functionality to ensure it works as expected under different scenarios.

## Test Case Files

1. **Valid Test Cases**
   - Contains step-by-step test cases for validating the functionality under normal conditions.
2. **Invalid Test Cases**
   - Contains step-by-step test cases for validating the response to incorrect or unexpected inputs.

### Mobile Application Test Cases
File: `MobileApplication.csv`
- Contains step-by-step test cases for the mobile application's functionality.
- Covers scenarios including:
  1. Sign-Up: Phone number, email, social media login (Facebook/Google).
  2. Login: Valid and invalid credentials, forgot password flow.
  3. Cart and Favorites Management: Adding/removing items, handling out-of-stock items, and cart persistence.
  4. Payment Processing: Credit card validation, first-time orders restrictions, and order cancellation.
  5. Offline Mode: Behavior when internet connectivity is lost.
  6. Real-time stock updates.
  7. Profile editing.

### Web Application Test Cases
File: `WebSite.csv`
- Contains step-by-step test cases for the web site's functionality.
- Covers scenarios including:
  1. Sign-Up: Phone number, email, social media login (Facebook/Google).
  2. Login: Valid and invalid credentials, forgot password flow.
  3. Home Page and Cart: UI, Adding/removing items, and cart persistence.
  4. Payment Processing: Credit card validation, first-time orders restrictions.
  5. Offline Mode: Behavior when internet connectivity is lost.
  6. Real-time stock updates.
  7. Profile editing.

### Admin Panel Test Cases
File: `AdminPanel.csv`
- Contains step-by-step test cases for the admin panel's functionality.
- Covers scenarios including:
  1. **Super Admin Sign-In**: Valid and invalid login attempts, "Remember Me" functionality, and "Forgot Password" flow.
  2. **Dashboard Navigation**: Sidebar navigation, dark/light mode toggle, profile section display, and notification menu.
  3. **Statistical Results Display**: Revenue, products, and orders cards with indication arrows and update timestamps.
  4. **Revenue Overview and Orders by Region**: Bar chart and pie chart visualization, filtering options, and "View All" functionality.
  5. **Overall Stats Dropdown and Download Report**: Filtering stats by time periods and downloading reports in Excel/PDF formats.
  6. **Orders Management**: Viewing, editing, and deleting orders from the Orders Card.
  7. **Products Management**: Adding, viewing, editing, and deleting products; pagination, filtering, and search functionality.
  8. **Users Management**: Viewing, editing, and deleting user records; filtering by region and pagination.
  9. **Admins Management**: Managing branch admins and supervisors, adding new admins, and exporting admin records.
  10. **Payments Management**: Viewing transaction details, refunding transactions, and filtering payment records.
  11. **Settings Page**: Appearance customization (light/dark mode), language selection, enabling/disabling 2FA, and notification preferences.

---

## Tools and Frameworks
The following tools and frameworks were used to design, manage, and execute the test cases:

1. **Zephyre**:
   - Zephyre was used as the primary test case management tool for organizing, executing, and tracking the test cases in this repository.
   - It provides a structured approach to defining test steps, test data, and expected results, ensuring clarity and consistency across all test cases.

2. **CSV Format**:
   - Test cases are exported from Zephyre into `.xlsx` then to `.csv` files for version control and ease of collaboration via GitHub.
