# Amazon E-Commerce Project Documentation

## Overview
This project is an e-commerce web application inspired by Amazon. The goal of this project is to learn and practice building a simple e-commerce website that allows users to browse products, add them to the shopping cart, and simulate the checkout process. The project is based on HTML, CSS, and JavaScript and utilizes local storage for cart management.

## Project Structure
The project's file structure is organized as follows:

- `backend/`
  - `products.json`
- `data/`
  - `cart.js`
  - `products.js`
- `images/`
- `scripts/`
  - `utils/`
    - `money.js`
  - `amazon.js`
  - `checkout.js`
- `styles/`
  - `pages/`
  - `shared/`

- The `backend` folder contains a JSON file (`products.json`) that stores product information.
- The `data` folder contains JavaScript files (`cart.js` and `products.js`) responsible for managing cart and product data.
- The `images` folder stores images used in the project.
- The `scripts` folder holds JavaScript files (`amazon.js` and `checkout.js`) that implement the website's functionality.
- The `styles` folder contains CSS files for styling the pages, organized into `pages` and `shared` subfolders.
- The `utils` folder includes the `money.js` file for handling currency formatting.

## Features
- Browse products: Users can view a list of products available for purchase.
- Add to cart: Users can add products to the shopping cart.
- Delete from cart: Users can remove items from the shopping cart.
- Cart quantity display: The cart icon displays the total number of items in the cart.
- Checkout: Users can review their cart, see the order summary, and proceed to checkout.
- Order history: Users can view their past orders with details.

## Technologies Used
- HTML: Structuring the web pages.
- CSS: Styling the pages and creating a responsive design.
- JavaScript: Implementing dynamic functionality and interactions.
- Local Storage: Saving cart.

## Setup
1. Clone the repository to your local machine.
2. Open the project directory in a code editor.

## Future Improvements
While the current version of the project provides basic functionality, there are several areas that could be improved:

- User Authentication: Implement user accounts and authentication for a personalized shopping experience.
- Product Details: Add a product details page with more information about each product.
- Payment Integration: Integrate with a payment gateway to handle real transactions.
- Search Functionality: Implement a search bar to help users find products easily.
- Responsive Design: Further enhance the responsiveness of the design for various screen sizes.
- Better Styling: Improve overall styling and user interface design.
- Refactoring: Consider refactoring the codebase to improve code organization and maintainability.

Please note that the above suggestions are for future enhancements and learning purposes.
