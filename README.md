#Ecommerce Website

**Author**: Alex Ukah  
**Date**: July 21, 2024

## Table of Contents

1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Setup Instructions](#setup-instructions)
    - [Prerequisites](#prerequisites)
    - [Backend Setup](#backend-setup)
    - [Frontend Setup](#frontend-setup)
5. [Usage](#usage)
6. [API Documentation](#api-documentation)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Project Overview

The E-commerce Application is designed to provide users with a seamless online shopping experience. It includes features such as user authentication, product listings, a shopping cart, and payment integration.

## Technologies Used

- **Frontend**: 
  - React
  - Redux
  - Axios
  - React Router
- **Backend**: 
  - Node.js
  - Express
  - Sequelize
  - PostgreSQL
- **Other**: 
  - JWT for authentication
  - Stripe for payments
  - dotenv for environment variables

## Features

- **User Authentication**: Registration, Login, Logout
- **Product Management**: Add, Edit, Delete, View Products
- **Shopping Cart**: Add to Cart, View Cart, Remove Items
- **Checkout**: Payment integration, Order summary
- **Admin Dashboard**: Manage products and orders

## Setup Instructions

### Prerequisites

- Node.js (v14.x or higher)
- PostgreSQL (v12.x or higher)
- Git

### Backend Setup

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/ecommerce-app.git
    cd ecommerce-app/backend
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

3. **Setup environment variables**:

    Create a `.env` file in the `backend` directory and add your PostgreSQL credentials and JWT secret:

    ```env
    DB_NAME=your_database_name
    DB_USER=your_database_user
    DB_PASSWORD=your_database_password
    DB_HOST=your_database_host
    JWT_SECRET=your_secret_key
    ```

4. **Run the server**:

    ```bash
    npm start
    ```

### Frontend Setup

1. **Navigate to the frontend directory**:

    ```bash
    cd ../frontend
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

3. **Run the application**:

    ```bash
    npm start
    ```

## Usage

Once both the backend and frontend are running, you can access the application at `http://localhost:3000`.

- **Home Page**: View a list of products.
- **Product Page**: View detailed information about a selected product.
- **Cart**: View items in your shopping cart and proceed to checkout.
- **Admin Page**: (Admin users only) Manage products and view orders.

## API Documentation

### User Endpoints

- **POST /api/users/register**: Register a new user.
- **POST /api/users/login**: Login a user.
- **GET /api/users/profile**: Get user profile.

### Product Endpoints

- **GET /api/products**: Get all products.
- **GET /api/products/:id**: Get a single product.
- **POST /api/products**: Add a new product (Admin only).
- **PUT /api/products/:id**: Update a product (Admin only).
- **DELETE /api/products/:id**: Delete a product (Admin only).

### Order Endpoints

- **POST /api/orders**: Create a new order.
- **GET /api/orders/:id**: Get order details.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any changes.

1. Fork the repository.
2. Create your feature branch: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please contact me at [alex.ukah@example.com](mailto:alex.ukah@example.com).

---
