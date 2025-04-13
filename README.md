# Ecommerce-FoodShop

Welcome to **Ecommerce-FoodShop**, an online platform for browsing, selecting, and purchasing food items. This application provides users with a seamless shopping experience, offering features such as food categorization, user authentication, secure payment integration, and order tracking.
 **User Authentication**: 
  - User sign-up, login, and logout functionality.
  - Password encryption for secure data storage.
---

## Features

 - **User Authentication**: 
  - User sign-up, login, and logout functionality.
  - Password encryption for secure data storage.

- **Product Catalog**:
  - Browse a variety of food items organized into categories (e.g., beverages, desserts, main courses).
  - Search and filter functionality for quick navigation.

- **Shopping Cart**:
  - Add, update, and remove items.
  - Real-time cart updates with subtotal and total calculations.

- **Order Management**:
  - Place orders and track their status.
  - View order history.

- **Payment Integration**:
  - Secure online payment with popular gateways (e.g., PayPal, Stripe).

- **Responsive Design**:
  - Optimized for desktop, tablet, and mobile devices.

---

## Tech Stack

### Frontend
- **React.js**: For building a dynamic and interactive user interface.
- **Tailwind CSS**: For styling and responsive design.

### Backend
- **Node.js**: For server-side logic and API development.
- **Express.js**: For building RESTful APIs.

### Database
- **MongoDB**: NoSQL database for storing user and product data.

### Others
- **JWT**: For user authentication.
- **Stripe/PayPal**: For payment integration.

---

## Installation and Setup

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v14 or above)
- **MongoDB** (local or cloud instance)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/ecommerce-foodshop.git
   cd ecommerce-foodshop
2. **Install Dependencies: Navigate to the root directory and install server-side dependencies**:

   ```bash
cd backend
npm install

3. Then navigate to the frontend directory and install client-side dependencies:

bash
Copy
Edit
cd ../frontend
npm install
Configure Environment Variables: Create a .env file in the backend directory with the following keys:

makefile
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_API_KEY=your_stripe_api_key
Run the Application: Start the backend server:

bash
Copy
Edit
cd backend
npm start
Start the frontend development server:

bash
Copy
Edit
cd ../frontend
npm start
Access the Application: Open your browser and navigate to http://localhost:3000.


