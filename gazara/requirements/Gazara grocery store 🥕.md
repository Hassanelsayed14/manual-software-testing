

Gazara   
Grocery store   
Functional requirements   
---

Website

### **1.0 Functional Requirements**

This section includes the requirements that specify all the fundamental actions of the software system in the web app.

##### **1.1.1 Functional Requirement 1.1**

* **ID**: FR1  
* **TITLE**: About, Contact, and Find Us Buttons  
* **DESC**: The home page should have a top bar containing "About Us," "Contact," and "Find Us" buttons.  
* **RAT**: To provide users with accessible options for learning more about the brand, contacting support, and the business locations.  
* **DEP**: None

  ##### **1.1.2 Functional Requirement 1.2**

* **ID**: FR2  
* **TITLE**: Promotional Message  
* **DESC**: A promotional message (e.g., "40% discount on your 1st order") should be displayed in the center of the top bar.  
* **RAT**: To attract users’ attention with current promotions and encourage first-time purchases.  
* **DEP**: FR1

  ##### **1.1.3 Functional Requirement 1.3**

* **ID**: FR3  
* **TITLE**: Main Logo and Search Bar  
* **DESC**: The second bar, the largest of the three, should contain the logo on the left, a search bar in the center, and "Signup/Login" options on the right.  
* **RAT**: To establish brand identity, allow users to search easily, and enable account access from the home page.  
* **DEP**: None

  ##### **1.1.4 Functional Requirement 1.4**

* **ID**: FR4  
* **TITLE**: Main Navigation Bar  
* **DESC**: The third bar should contain the main navigation links: "Home" (in bold to indicate the current page), "Vegetables," "Fruits," "Meat," and "Shop All."  
* **RAT**: To provide easy access to key sections of the website for smooth browsing.  
* **DEP**: None

##### **1.1.5 Functional Requirement 1.5**

* **ID**: FR5  
* **TITLE:** Find Us page with booth locations  
* **DESC:** Clicking on the "Find Us" button on the first bar should open a window displaying all store booths located in major supermarkets.  
* **RAT:** To help users locate physical store booths in supermarkets.  
* **DEP:** None

##### **1.1.6 Functional Requirement 1.6**

* **ID**: FR6  
* **TITLE:** Contact page prompt  
* **DESC:** Clicking on the "Contact" button on the first bar should open a new window prompting the user to enter their first name, last name, phone number, email, subject, and message, with a "Submit" button.  
* **RAT:** To enable users to contact customer support or send inquiries.  
* **DEP:** None

##### **1.1.7 Functional Requirement 1.7**

* **ID**: FR7  
* **TITLE**: About Us Button Functionality  
* **DESC**: Clicking on "About Us" should scroll the user to the end of the home page, where a brief description of the store is displayed.  
* **RAT**: To allow users to quickly learn about the store's background and values.  
* **DEP**: FR1

##### **1.1.8 Functional Requirement 1.8**

* **ID**: FR8  
* **TITLE**: Recommended Items Display  
* **DESC**: Scrolling down the home page should display images of random recommended items with suggestions to try.  
* **RAT**: To engage users by showcasing popular or curated items, encouraging exploration and purchases.  
* **DEP**: None

##### **1.1.9 Functional Requirement 1.9**

* **ID**: FR9  
* **TITLE**: Call to Action Button  
* **DESC**: The home page should display a "Shop Now" button that redirects the user to the "Shop All" page.  
* **RAT**: To provide an actionable prompt, making it easy for users to start shopping.  
* **DEP**: None

##### **1.1.10 Functional Requirement 1.10**

* **ID**: FR10  
* **TITLE**: Vegetables Section Content  
* **DESC**: The "Vegetables" section should display all vegetable items, including details such as price, weight, image, and name.  
* **RAT**: To provide users with comprehensive information on vegetable items for informed purchases.  
* **DEP**: FR4

##### **1.1.11 Functional Requirement 1.11**

* **ID**: FR11  
* **TITLE**: Fruits Section Content  
* **DESC**: The "Fruits" section should display all fruit items, including details such as price, weight, image, and name.  
* **RAT**: To offer users clear details on all fruit items to support selection and purchase decisions.  
* **DEP**: FR4

##### **1.1.12 Functional Requirement 1.12**

* **ID**: FR12  
* **TITLE**: Meat Section Content  
* **DESC**: The "Meat" section should display all meat items, including details such as price, weight, image, and name.  
* **RAT**: To provide users with relevant details on available meat items for informed decision-making.  
* **DEP**: FR4

##### **1.1.13 Functional Requirement 1.13**

* **ID**: FR13  
* **TITLE**: Shop All Page Content  
* **DESC**: The "Shop All" page should display a combined list of all available items across categories in one place.  
* **RAT**: To allow users to browse and access all store items on a single page for a streamlined shopping experience.  
* **DEP**: FR4, FR9

**1.1.14 Functional requirement 1.14**

* **ID:** FR14  
* **TITLE:** Access restrictions on cart and payment for non-logged-in users  
* **DESC:** Users must be logged in to add items to the cart, view the cart, or proceed to payment.  
* **RAT:** To ensure user authentication before proceeding with order and payment functions.  
* **DEP:** None

**1.1.15 Functional requirement 1.15**

* **ID:** FR15  
* **TITLE:** Multi-option signup for users  
* **DESC:** Users should have the option to sign up via Google, Facebook, or email.  
* **RAT:** To provide flexible and convenient registration options.  
* **DEP:** None  
  **Field Verification for Email Signup:**  
* First Name: Required; accepts alphabets only.  
* Last Name: Required; accepts alphabets only.  
* Email: Required; valid email format.  
* Password: Required; minimum 8 characters, must include numbers and letters.

**1.1.16 Functional requirement 1.16**

* **ID:** FR16  
* **TITLE:** Side notification on adding items to cart  
* **DESC:** Upon adding an item to the cart, a side pop-up message should appear displaying the item's name, price, and size, confirming the addition.  
* **RAT:** To provide visual confirmation of items added to the cart.  
* **DEP:** FR14

**1.1.17 Functional requirement 1.17**

* **ID:** FR17  
* **TITLE:** "View Cart" button within side pop-up notification  
* **DESC:** Users should be able to click a "View Cart" button within the side pop-up to directly access the cart page with all added items.  
* **RAT:** To facilitate user navigation from the notification to the cart for order review.  
* **DEP:** FR16

**1.1.18 Functional requirement 1.18**

* **ID:** FR18  
* **TITLE:** Cart overview and order summary  
* **DESC:** Upon clicking "View Cart," users should see a list of added items, an order summary, and an option to proceed to checkout.  
* **RAT:** To allow users to review their cart contents and order details before proceeding to payment.  
* **DEP:** FR17

**1.1.19 Functional requirement 1.19**

* **ID:** FR19  
* **TITLE:** Delivery details input during checkout  
* **DESC:** During checkout, users should enter required delivery information, including first name, last name, phone number, address, region, and postal code, with options to save and continue or return to browsing.  
* **RAT:** To collect necessary delivery information for order processing and shipment.  
* **DEP:** FR18

**1.1.20 Functional requirement 1.20**

* **ID:** FR20  
* **TITLE:** Delivery details summary with edit option  
* **DESC:** After saving delivery information, users should see a summary of the details with an option to edit them if needed.  
* **RAT:** To confirm accuracy of delivery information before proceeding to payment.  
* **DEP:** FR19

**1.1.21 Functional requirement 1.21**

* **ID:** FR21  
* **TITLE:** Payment type selection during checkout  
* **DESC:** Users should select a payment type (cash on delivery or pay by card) during checkout.  
* **RAT:** To allow users flexibility in payment method selection.  
* **DEP:** FR20

**1.1.22 Functional requirement 1.22**

* **ID:** FR22  
* **TITLE:** Cash on delivery restriction for first-time users  
* **DESC:** Users can only select cash on delivery if they have previously completed at least one order by card.  
* **RAT:** To establish initial payment credibility before enabling cash on delivery.  
* **DEP:** FR21

**1.1.23 Functional requirement 1.23**

* **ID:** FR23  
* **TITLE:** Card payment option with required details  
* **DESC:** For card payments, users must enter the card number, name on the card, expiry date, and security code.

  #### **1\. For card Number:**

  **Validation Rules:**  
* Must be a numeric string with 16 digits.  
* Accepted card types (Visa, Mastercard, etc.) should be detected and displayed dynamically based on the first 4 digits.  
* Should pass **Luhn’s Algorithm** for credit card number validation.  
  **Error Messages:**  
* "Invalid card number. Please enter a 16-digit number."  
* "Card type not recognized. Please enter a valid card number."  
  **Input Masking:**  
* Display the input as "\*\*\*\* \*\*\*\* \*\*\*\* 1234" for security.

\---------------

#### **2\. Name on Card**

**Validation Rules:**

* Must be a non-empty string.  
* Allowed characters: alphabets (A-Z, a-z), spaces, and hyphens.  
* Minimum length: 2 characters.  
* Maximum length: 50 characters.  
  **Error Messages:**  
* "Name cannot be empty. Please enter the name exactly as it appears on your card."  
* "Invalid characters detected. Please use letters, spaces, or hyphens only."

#### **3\.  Expiry Date**

**Validation Rules:**

* Format: MM/YY.  
* Must be a valid future date.  
* Month (MM) should range from 01 to 12\.  
* Year (YY) should not be in the past.  
  **Error Messages:**  
* "Invalid expiry date. Please use MM/YY format."  
* "Expiry date cannot be in the past."  
* "Month must be between 01 and 12."  
  **Input Masking:**  
* Automatically format the input as "MM/YY" as the user types.

#### **4, Security Code (CVV)**

**Validation Rules:**

* Must be a numeric string with 3 or 4 digits (depending on the card type).  
* Only numbers are allowed.  
  **Error Messages:**  
* "Invalid CVV. Please enter a 3 or 4-digit security code."  
  **Input Masking:**  
* Mask input as "\*\*\*" for security.

* **RAT:** To securely collect necessary information for card payment processing.  
* **DEP:** FR21

**1.1.24 Functional requirement 1.24**

* **ID:** FR24  
* **TITLE:** Display of card type logo based on card number  
* **DESC:** When users enter the first four digits of their card number, the card type (e.g., Visa, Mastercard) should display dynamically within the card number field.  
* **RAT:** To provide visual feedback and validation of card type.  
* **DEP:** FR23

**1.1.25 Functional requirement 1.25**

* **ID:** FR25  
* **TITLE:** Order placement and payment completion  
* **DESC:** Upon entering valid payment details, users should be able to place their order and complete the payment.  
* **RAT:** To finalize the transaction and submit the order for processing.  
* **DEP:** FR23, FR24

**1.1.26 Functional requirement 1.26**

* **ID:** FR26  
* **TITLE:** Edit item quantity in cart  
* **DESC:** Within "My Cart," users should be able to add or subtract quantities of each item they have added.  
* **RAT:** To give users flexibility in adjusting quantities before checkout.  
* **DEP:** FR18

**1.1.27 Functional requirement 1.27**

* **ID:** FR27  
* **TITLE:** Remove item from cart  
* **DESC:** Users should have the option to completely delete any item from their cart.  
* **RAT:** To allow users to modify their cart by removing unwanted items before purchasing.  
* **DEP:** FR26

**1.1.28 Functional requirement 1.28**

* **ID:** FR28  
* **TITLE:** Add note to item in cart  
* **DESC:** Users should be able to add a note below each item in the cart (e.g., specific delivery instructions or food preferences).  
* **RAT:** To allow users to specify any additional details or instructions related to each item.  
* **DEP:** FR18

**1.1.29 Functional requirement 1.29**

* **ID:** FR29  
* **TITLE:** Promo code application in cart  
* **DESC:** Users should be able to enter a promo code within "My Cart" to apply discounts before proceeding to checkout.  
* **RAT:** To provide users with the option to apply discounts or special offers.  
* **DEP:** FR18

**1.1.30 Functional requirement 1.30**

* **ID:** FR30  
* **TITLE:** Search recommendations in search bar  
* **DESC:** When typing in the search bar, users should see a list of item recommendations based on partial input (e.g., typing "mushr" shows all items containing "mushroom").  
* **RAT:** To enhance search functionality by providing real-time item suggestions.  
* **DEP:** None

**1.1.31 Functional requirement 1.31**

* **ID:** FR31  
* **TITLE:** Profile drop-down menu  
* **DESC:** Upon clicking on the profile icon, a drop-down menu should appear with the following options: "My Orders," "My Wallet," "My Account," and "Logout."  
* **RAT:** To allow users easy access to account-related options in a convenient drop-down menu.  
* **DEP:** None

**1.1.32 Functional requirement 1.32**

* **ID:** FR32  
* **TITLE:** View past orders  
* **DESC:** On selecting "My Orders" from the profile menu, a page should open displaying a list of past orders. Each order should include the date it was placed, total price, recipient details, delivery day, and options to "Buy Again" or "View Item."  
* **RAT:** To allow users to review their previous orders and reorder items if desired.  
* **DEP:** FR31

**1.1.33 Functional requirement 1.33**

* **ID:** FR33  
* **TITLE:** View and edit saved address  
* **DESC:** Selecting "My Address" should open a page where users can view their current saved address details, including street name, house number, floor number, and associated phone number. Users should also have the option to edit or change this address.  
* **RAT:** To enable users to keep their address information up-to-date for future orders.  
* **DEP:** None

**1.1.34 Functional requirement 1.34**

* **ID:** FR34  
* **TITLE:** Add additional address  
* **DESC:** Users should have the option to add a completely new address within the "My Address" page, allowing them to save multiple delivery locations.  
* **RAT:** To give users flexibility by allowing multiple saved addresses for deliveries.  
* **DEP:** FR33

**1.1.35 Functional requirement 1.35**

* **ID:** FR35  
* **TITLE:** View personal information in "My Account"  
* **DESC:** Selecting "My Account" should display a page with the user's personal information, including their first name, last name, and phone number, as well as address details (street, city, and zip code). Users should be given options to discard any unsaved changes or update the information.  
* **RAT:** To allow users to easily access and update their account information as needed.  
* **DEP:** FR31

– Fin –

