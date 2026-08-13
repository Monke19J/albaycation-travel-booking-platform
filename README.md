# Albaycation — Travel & Tourism Booking Platform

Albaycation is a multi-role travel and tourism booking platform designed
to help customers discover and book tourism activities and packages in
Albay, Philippines.

This was developed as a group academic project. My primary contributions
included the front-end UI, user registration and authentication, and package
browsing, search, and filtering features.

## What it does
- Customer and Admin account registration and login
- Package browsing with search and filter functionality
- [Add 1-2 more real features here, e.g. booking flow, payment step, admin
  package management — whatever else the group built]

## Tech stack
PHP · MySQL · HTML · CSS · JavaScript · Bootstrap

## Screenshots


## Project documentation
This project followed a full design process before implementation:
- [`docs/data-flow-diagrams`](./docs/data-flow-diagrams) — DFD Level 0, 1, and 2
- [`docs/database-schema`](./docs/database-schema) — phpMyAdmin table structure export

## How to run
1. Clone the repo and place the `website` folder in your XAMPP `htdocs` directory
2. Import the database schema from `docs/database-schema`
3. Start Apache and MySQL via XAMPP
4. Visit `http://localhost/website` in your browser

## My contributions
This was a group project. My specific contributions were the front-end UI,
the customer/admin registration and login system, and the package
browsing/search/filter features.

## What I'd improve with more time
- **Security:** Improve authentication security by using stronger password
  hashing, prepared SQL statements, and better session management.
- **Payment integration:** Replace the simulated payment flow with a
  production-ready payment gateway.
- **Responsive UI:** Further improve the mobile experience across all pages
  and screen sizes.
- **Code organization:** Refactor the PHP codebase into a more maintainable
  structure by separating presentation, business logic, and database access.
- **Deployment:** Deploy the application to a production environment instead
  of running it only through XAMPP.
