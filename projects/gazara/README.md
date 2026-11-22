# Gazara

Test design for **Gazara**, a grocery store website (vegetables, fruits and meat) with a shopping cart, checkout and user accounts. I started from the functional requirements document, wrote test scenarios, and turned them into detailed test cases in Jira + Zephyr Scale.

## Summary

| | |
|---|---|
| Requirements analyzed | 35 functional requirements (FR1 to FR35) |
| Test scenarios | 99 across the 6 modules, tracked on a Trello board |
| Test cases written | 80 (58 positive, 22 negative) |
| Priority split | 49 High, 19 Normal, 12 Low |
| Modules | 6 (header, home, catalog, authentication, profile, cart & checkout) |
| Tools | Jira, Zephyr Scale, Trello, Excel |

## Modules and Coverage

| # | Module | Requirements | Positive | Negative | Total |
|---|--------|--------------|:--------:|:--------:|:-----:|
| 01 | Header & Navigation | FR1 to FR7, FR30 | 9 | 1 | 10 |
| 02 | Home Page | FR8, FR9 | 3 | 1 | 4 |
| 03 | Product Catalog | FR10 to FR13 | 11 | 0 | 11 |
| 04 | Authentication | FR14, FR15 | 10 | 14 | 24 |
| 05 | User Profile | FR31 to FR35 | 11 | 3 | 14 |
| 06 | Cart & Checkout | FR16 to FR23 | 14 | 3 | 17 |
| | **Total** | | **58** | **22** | **80** |

## What the Test Cases Cover

- **Layout and content:** top bar, promotional message, logo, search bar and main navigation, including the bold "Home" link
- **Navigation behavior:** "About Us" scroll, Contact form, Find Us window, search suggestions, "Shop Now" redirect
- **Sign-up validation:** required fields, alphabets-only names, email format, password rules (8+ characters, letters and numbers), sign-up with Google and Facebook
- **Access control:** guest users cannot add to cart, view the cart, pay, or open the cart and payment pages by direct URL
- **Profile:** orders list, "Buy Again", saved address (view, edit, add), personal information, logout
- **Cart and checkout:** add-to-cart pop-up, cart page and order summary, delivery details form, delivery summary with edit, payment type selection, card details

Each test case has a Key (`GAZ-T1` and so on), a title, preconditions, priority, step-by-step actions with expected results, and a folder (module / Positive or Negative).

## Mockups

The mockups are illustrative screens that I used to visualize the requirements while writing test cases. They are not screenshots of a live Gazara app.

| Module | Requirements shown | File |
|--------|--------------------|------|
| Header & Navigation | FR1 to FR4 | `01-header-navigation.png` |
| Home Page | FR8, FR9 | `02-home-page.png` |
| Authentication | FR15 | `04-authentication.png` |
| User Profile | FR31 to FR35 | `05-user-profile.png` |
| Cart & Checkout | FR16 to FR30 | `06-cart-checkout.png` |

## Folder Structure

```
gazara/
├── README.md
├── requirements/
│   └── functional-requirements.md
├── test-scenarios/
│   └── gazara-test-scenarios.md
├── test-cases/
│   └── gazara-test-cases.xlsx
└── mockups/
    ├── 01-header-navigation.png
    ├── 02-home-page.png
    ├── 04-authentication.png
    ├── 05-user-profile.png
    └── 06-cart-checkout.png
```
