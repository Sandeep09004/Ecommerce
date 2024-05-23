# Clothing eCommerce Website

This project is a full-featured eCommerce website for clothing, built using the MERN stack (MongoDB, Express.js, React, Node.js).

## Overview

The Clothing eCommerce Website allows users to browse and purchase clothing items. It includes features such as user authentication, product browsing, shopping cart, and order management. The backend is powered by Node.js and Express, with MongoDB as the database. The frontend is built using React.

## Features

- User authentication (sign up, login, logout)
- Browse products by categories
- Product details page
- Shopping cart
- Order placement and management
- User profile with order history
- Admin dashboard for managing products, orders, and users

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/clothing-ecommerce-website.git
   ```
2. Navigate to the project directory:
```bash
cd clothing-ecommerce-website
```

3. Install backend dependencies:
```bash
cd backend
npm install
```

Install frontend dependencies:
```sh
cd ../frontend
npm install
```

Set up environment variables:
Create a .env file in the backend directory and add the following:
```sh
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```
Start the development server:

Backend:
```sh
cd backend
npm run dev
```
Frontend:
```sh
cd ../frontend
npm start
```
Usage
Open your browser and navigate to http://localhost:3000 to access the frontend.
Use Postman or a similar tool to test backend APIs at http://localhost:5000/api.


#### Screenshots
### Home Page
![Home Page](https://drive.google.com/uc?id=1xlWL2DY4uVV4UKkgGYg_ZJackl9m6wN5)

### Authentication Page
![Authentication Page](https://drive.google.com/uc?id=1pnNIjDzUyqd3ZdIetQZOLupFlHB3ZMU_)

### Categories
![Categories](https://drive.google.com/uc?id=16noslSHkDHGqq283xvGVJobg0gUUmq9f)

### Cart Page
![Cart Page](https://drive.google.com/uc?id=1t4KKkZ2nxrDrmbJnyKavZ0FsWTgxtYxn)

### Delivery Page
![Delivery Page](https://drive.google.com/uc?id=16zu0sxZ3crPjPwk-PgIjETBzVEducQ2S)

To add screenshots, save your images in a screenshots directory in the root of your project and reference them in the README.md file as shown above.

Project Structure
backend/: Contains the backend code (Node.js, Express)
frontend/: Contains the frontend code (React)
screenshots/: Contains screenshots of different sections of the website
README.md: Project documentation
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows the project's coding standards and includes appropriate tests.



Acknowledgements
Thanks to the open-source community for the libraries and tools used in this project.
Special thanks to contributors for their valuable inputs and support.
Contact
For any queries or suggestions, feel free to contact:

Your Name - pallsandeep454@gmail.com
