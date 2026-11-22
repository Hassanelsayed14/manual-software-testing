# Gazara: Test Scenarios

High-level test scenarios written from the functional requirements for each module of the Gazara website. These scenarios were the starting point for designing the detailed test cases (steps, test data and expected results).

| Module | Positive | Negative | Total |
|--------|:--------:|:--------:|:-----:|
| 01 Header & Navigation | 10 | 1 | 11 |
| 02 Home Page | 3 | 1 | 4 |
| 03 Product Catalog | 11 | 0 | 11 |
| 04 Authentication | 10 | 14 | 24 |
| 05 User Profile | 11 | 3 | 14 |
| 06 Cart & Checkout | 22 | 13 | 35 |
| **Total** | | | **99** |

## 01. Header & Navigation

### Positive scenarios

| # | Scenario |
|---|----------|
| 01-P1 | Verify that the top bar displays "About Us", "Contact", and "Find Us" buttons |
| 01-P2 | Verify that the promotional message "40% Discount on Your 1st Order" is displayed in the center of the top bar |
| 01-P3 | Verify that the second bar contains the logo on the left, search bar in the center, and Login/Signup on the right |
| 01-P4 | Verify that the third bar contains navigation links: Home, Vegetables, Fruits, Meat, and Shop All |
| 01-P5 | Verify that "Home" link is bold by default (indicating current page) |
| 01-P6 | Verify that clicking "About Us" scrolls the page to the About section at the bottom |
| 01-P7 | Verify that clicking "Contact" opens the Contact form popup/window |
| 01-P8 | Verify that clicking "Find Us" opens a window showing store booth locations |
| 01-P9 | Verify that typing in the search bar displays relevant item suggestions |

### Negative scenarios

| # | Scenario |
|---|----------|
| 01-N1 | Verify that searching with no matching keyword shows "No results found" |

## 02. Home Page

### Positive scenarios

| # | Scenario |
|---|----------|
| 02-P1 | Verify that recommended items are displayed when scrolling down the home page. |
| 02-P2 | Verify the button "Shop Now" in the home page |
| 02-P3 | Verify the button "Shop Now" redirects user to "Shop All" page. |

### Negative scenarios

| # | Scenario |
|---|----------|
| 02-N1 | Verify that recommended item images are not displayed when scrolling down the home page. |

## 03. Product Catalog

### Positive scenarios

| # | Scenario |
|---|----------|
| 03-P1 | Verify that the Vegetables tab is displayed on the Main Navigation Bar |
| 03-P2 | Verify that the “Vegetables” section displays all vegetable items |
| 03-P3 | Verify that each vegetable item displays its details (e.g., price, weight, image, and name) |
| 03-P4 | Verify that the Fruits tab is displayed on the Main Navigation Bar |
| 03-P5 | Verify that the “Fruits” section displays all fruit items |
| 03-P6 | Verify that each fruit item displays its details (e.g., price, weight, image, and name) |
| 03-P7 | Verify that the Meat tab is displayed on the Main Navigation Bar |
| 03-P8 | Verify that the “Meat” section displays all meat items |
| 03-P9 | Verify that each meat item displays its details (e.g., price, weight, image, and name) |
| 03-P10 | Verify that the Shop All tab is displayed on the Main Navigation Bar |
| 03-P11 | Verify that the “Shop All” page displays a combined list of all available items across categories in one place |

## 04. Authentication

### Positive scenarios

| # | Scenario |
|---|----------|
| 04-P1 | Verify that a user can successfully sign up using Email with valid data. |
| 04-P2 | Verify that a user can sign up using Google. |
| 04-P3 | Verify that a user can sign up using Facebook. |
| 04-P4 | Verify that the First Name field accepts alphabets only. |
| 04-P5 | Verify that the Last Name field accepts alphabets only. |
| 04-P6 | Verify that the Email field accepts a valid email format. |
| 04-P7 | Verify that the Password field accepts a password of 8 characters or more containing letters and numbers. |
| 04-P8 | Verify that a logged-in user can add items to the cart. |
| 04-P9 | Verify that a logged-in user can view the cart. |
| 04-P10 | Verify that a logged-in user can proceed to payment. |

### Negative scenarios

| # | Scenario |
|---|----------|
| 04-N1 | Verify that the First Name field shows an error when left empty. |
| 04-N2 | Verify that the Last Name field shows an error when left empty. |
| 04-N3 | Verify that the Email field shows an error when left empty. |
| 04-N4 | Verify that the Password field shows an error when left empty. |
| 04-N5 | Verify that the First Name field rejects numbers and special characters. |
| 04-N6 | Verify that the First Name and Last Name fields show an error when they contain spaces only. |
| 04-N7 | Verify that the Password field shows an error when it contains fewer than 8 characters. |
| 04-N8 | Verify that a guest user cannot add items to the cart. |
| 04-N9 | Verify that a guest user cannot view the cart. |
| 04-N10 | Verify that a guest user cannot proceed to payment. |
| 04-N11 | Verify that a guest user cannot access the Cart or Payment page via a direct URL. |
| 04-N12 | Verify that the Last Name field rejects numbers and special characters. |
| 04-N13 | Verify that the Email field shows an error for an invalid email format. |
| 04-N14 | Verify that the Password field shows an error when it doesn't contain both letters and numbers. |

## 05. User Profile

### Positive scenarios

| # | Scenario |
|---|----------|
| 05-P1 | Verify that the profile icon is displayed when the user is logged in |
| 05-P2 | Verify that clicking the profile icon displays options: My Orders, My Account, My Address, and Logout |
| 05-P3 | Verify that selecting "My Orders" displays a list of past orders |
| 05-P4 | Verify that each order displays: date, total price, recipient details, delivery day, Buy Again, and View Item |
| 05-P5 | Verify that clicking "Buy Again" adds the same products to the cart |
| 05-P6 | Verify that selecting "My Address" displays the saved address details (street, house number, floor, phone) |
| 05-P7 | Verify that the user can edit the saved address |
| 05-P8 | Verify that the user can add a new additional address |
| 05-P9 | Verify that selecting "My Account" displays personal information (first name, last name, phone, address) |
| 05-P10 | Verify that the user can edit personal information in My Account |
| 05-P11 | Verify that clicking Logout logs the user out successfully |

### Negative scenarios

| # | Scenario |
|---|----------|
| 05-N1 | Verify that guest user cannot access My Orders / My Account / My Address |
| 05-N2 | Verify that required fields show error when left empty while editing address |
| 05-N3 | Verify that required fields show error when left empty while editing personal information |

## 06. Cart & Checkout

### Positive scenarios

| # | Scenario |
|---|----------|
| 06-P1 | Verify that a side pop-up displaying the item’s name, price, and size appears upon adding an item to the cart. |
| 06-P2 | Verify that the “View Cart” button is displayed within the side pop-up. |
| 06-P3 | Verify that clicking “View Cart” opens the cart page with all added items. |
| 06-P4 | Verify that the cart page displays the list of added items with product details. |
| 06-P5 | Verify that the cart page displays the order summary. |
| 06-P6 | Verify that the cart page displays an option to proceed to checkout. |
| 06-P7 | Verify that users can enter all required delivery information during checkout. |
| 06-P8 | Verify that users can save the delivery information and continue with checkout. |
| 06-P9 | Verify that users can return to browsing from the checkout page. |
| 06-P10 | Verify that users can view a summary of their saved delivery information. |
| 06-P11 | Verify that users can edit their saved delivery information. |
| 06-P12 | Verify that the user can select pay by card as the payment type. |
| 06-P13 | Verify that the user can select cash on delivery after completing at least one order by card. |
| 06-P14 | Verify that the user can enter valid card details (card number, name on card, expiry date, and security code). |
| 06-P15 | Verify that the card number and security code are masked, and the expiry date is formatted as MM/YY. |
| 06-P16 | Verify that the card type logo is displayed when the user enters the first four digits of the card number. |
| 06-P17 | Verify that the user can place the order and complete the payment with valid card details. |
| 06-P18 | Verify that users can increase the quantity of an item in the cart |
| 06-P19 | Verify that users can decrease the quantity of an item in the cart |
| 06-P20 | Verify that users can remove an item completely from the cart. |
| 06-P21 | Verify that users can add a note below an item in the cart. |
| 06-P22 | Verify that users can apply a valid promo code to get a discount. |

### Negative scenarios

| # | Scenario |
|---|----------|
| 06-N1 | Verify that users cannot continue checkout when required delivery fields are empty. |
| 06-N2 | Verify that the user cannot proceed to checkout when the cart is empty. |
| 06-N3 | Verify that users cannot save the edited delivery information when required fields are left empty. |
| 06-N4 | Verify that the user cannot select cash on delivery without a previous order paid by card. |
| 06-N5 | Verify that an error is displayed for an invalid card number (not 16 digits or fails the Luhn check). |
| 06-N6 | Verify that an error is displayed for an invalid name on card (empty or contains numbers or symbols). |
| 06-N7 | Verify that an error is displayed for an invalid expiry date (past date, month above 12, or wrong format). |
| 06-N8 | Verify that an error is displayed for an invalid security code (letters or less than 3 digits). |
| 06-N9 | Verify that the user cannot place the order when the card details are empty. |
| 06-N10 | Verify that an error is displayed when applying an invalid promo code. |
| 06-N11 | Verify that the item quantity cannot go below 1. |
| 06-N12 | Verify that no discount is applied when the promo code field is empty. |
| 06-N13 | Verify that an error is displayed when applying an expired promo code. |
