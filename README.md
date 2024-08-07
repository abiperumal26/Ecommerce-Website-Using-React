# Ecommerce Website Using React.js

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project is an ecommerce website built using React.js. It features client-side RESTful APIs to handle user data operations. The project is a modern, responsive web application that provides a seamless shopping experience.

## Features
- User Authentication
- Product Listings
- Shopping Cart
- Checkout Process
- Order History
- Responsive Design

## Installation
To get a local copy up and running follow these simple steps.

### Prerequisites
- Node.js
- npm (Node Package Manager)

### Installation Steps
1. Clone the repository
    ```sh
    git clone https://github.com/abiperumal26/Ecommerce-Website-Using-React.git
    ```
2. Navigate to the project directory
    ```sh
    cd Ecommerce-Website-Using-React
    ```
3. Install NPM packages
    ```sh
    npm install
    ```

## Usage
To run the application locally:

1. Start the development server
    ```sh
    npm start
    ```
2. Open your browser and navigate to `http://localhost:3000`

### Client-side RESTful API
This project uses client-side RESTful APIs to handle user data. Here are some of the endpoints:

- **User Authentication**
  - `POST /api/login`: Log in a user
  - `POST /api/register`: Register a new user

- **Products**
  - `GET /api/products`: Get all products
  - `GET /api/products/:id`: Get a specific product by ID

- **Shopping Cart**
  - `GET /api/cart`: Get the current user's cart
  - `POST /api/cart`: Add a product to the cart
  - `DELETE /api/cart/:id`: Remove a product from the cart

- **Orders**
  - `GET /api/orders`: Get the current user's orders
  - `POST /api/orders`: Create a new order

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Your Name -Abinaya S - abiperumal2000@gmail.com

Project Link: [https://github.com/abiperumal26/Ecommerce-Website-Using-React](https://github.com/abiperumal26/Ecommerce-Website-Using-React)
