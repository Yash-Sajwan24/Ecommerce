# E-Commerce Website

A full-stack eCommerce platform built with the MERN stack offers user-friendly interfaces for users and administrators. Features include product search, filtering, sorting, secure authentication, and PayPal integration for payments.


## Live Link
https://ecommerce-1-ex1a.onrender.com/auth/login

## Tech Stack
- **Frontend**: React.js, ShadCN, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **State Management**: Redux Toolkit
- **Payment Gateway**: PayPal REST SDK
- **File Storage**: Cloudinary
- **Authentication**: JWT, Bcrypt



https://github.com/user-attachments/assets/fc62670c-85fb-4011-9b5f-9420cf3b8245



## Features

### User Panel:
- **Product Filtering & Sorting**: Filter by brand, price, and categories.
- **Search Functionality**: Search products easily.
- **Checkout**: Add addresses and pay via PayPal.
- **Reviews**: Leave product reviews after purchase.

### Admin Panel:
- **Product Management**: Add, edit, or delete products.
- **Order Management**: Update order statuses.
- **Banner Management**: Upload and manage homepage banners.

## Security
- **Authentication**: JWT for user authentication.
- **Password Protection**: Bcrypt for secure password hashing.
- **Role-based Access**: Route validation to restrict access based on user roles (admin/user).

  ### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
https://github.com/Yash-Sajwan24/Ecommerce.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js

CLOUDINARY_CLOUD_NAME = 
CLOUDINARY_API_KEY = 
CLOUDINARY_API_SECRET = 

PAYPAL_CLIENT_ID = 
PAYPAL_CLIENT_SECRET = 

MONGO_URL = 
PORT = 
CLIENT_BASE_URL = 


```

```js

VITE_API_URL =


```


### Start the app

```shell
npm run dev
```



