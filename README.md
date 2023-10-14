# Next.js E-Commerce Website

![Next.js E-Commerce Website](https://github.com/DevRex-0201/Next-Ecommerce-SPEQ/blob/main/public/intro.jpg)

Welcome to the Next.js E-Commerce Website repository! This powerful e-commerce platform, developed by Abdullah Moiz, offers a seamless shopping experience with advanced features and a user-friendly interface. Built with Next.js 13, TypeScript, Tailwind CSS, Redux Toolkit, and MongoDB, this application provides multi-user functionality, secure authentication, admin panel management, order handling, and much more.

## Features

- **User Authentication**:
  - Sign In / Sign Up
  - Forgot Password
  - JWT validation on each authorized request
  - Authorization validation for Admin and Customer access

- **Admin Panel**:
  - Manage Products:
    - Add, view, update, delete products
  - Manage Categories:
    - Add, view, update, delete categories
  - Handle Orders:
    - Pending and completed order lists
    - Order delivery management
  - Search products and categories
  - Alert for out-of-stock products

- **Customer Interface**:
  - View products and categories
  - Add products to the cart
  - Remove products from the cart
  - Increase/decrease cart item quantity
  - Bookmark favorite products
  - Order products
  - Track order status and view order details

## Note

- Admin dashboard access is available only after cloning the project.

## Technologies Used

- **Next.js 13**: Powerful React framework for server-rendered React applications.
- **TypeScript**: Typed JavaScript for enhanced development.
- **Tailwind CSS**: Highly customizable, low-level CSS framework.
- **Redux Toolkit**: State management library for React applications.
- **Joi Validation**: Data validation library for Node.js.
- **MongoDB**: NoSQL database for efficient data storage and retrieval.
- **SWR Hooks**: Fetching API data with efficient caching and revalidation.

## Environment Variables

To run this project, you will need to add the following environment variables to your `.env` file:

- `DB_URI`: Your MongoDB URL
- `JWT_SECRET`: Your custom JWT secret key
- `NEXT_PUBLIC_API_BASE_URL`: Base URL for localhost (e.g., `http://localhost:3000`)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Install dependencies and run the development server:

   ```bash
   npm install
   npm run dev
   ```

3. For production build:

   ```bash
   npm run build
   npm run start
   ```

4. Preview production server:

   ```bash
   npm run preview
   ```

Thank you for choosing Next.js E-Commerce Website for your project! For any inquiries or issues, feel free to reach out. Happy coding! 🚀✨
