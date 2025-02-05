# Mini Expense Tracker Application

## Overview
The Mini Expense Tracker application allows users to authenticate securely, manage expenses, and gain insights into their spending patterns. The frontend is built using ReactJS, while the backend is implemented using Python or NodeJS, with MongoDB or PostgreSQL as the database.

## Features
### 1. Authentication
- **JWT-based authentication with HTTP-only cookies**
- Users can:
  - Register with first name, last name, email, and password
  - Log in to receive a secure token
  - Log out to invalidate the token
  - Handle token expiry, including refresh tokens

### 2. Expense Management (CRUD)
- Users can:
  - Add, update, delete, and view expenses
  - Each expense includes:
    - Amount (numeric, required)
    - Category (e.g., Food, Travel, etc.)
    - Date (required)
    - Description (optional)
  - Expenses are paginated and filterable by date range and category

### 3. Spending Insights
- Calculate:
  - Total spending per category
  - Percentage distribution of expenses across categories
- Display:
  - Bar chart or pie chart visualizing category-wise spending on the frontend

### 4. Frontend (ReactJS)
- Pages:
  - **Login/Registration:** Handle JWT securely via HTTP-only cookies
  - **Dashboard:** List expenses (with pagination and filters) and display the spending insights chart
  - **Add/Edit Expense:** Simple form for creating or editing expenses
  - **Delete Expense:** Delete an expense that was added by mistake or duplicated

## Deliverables
- A deployed app on platforms like AWS, Vercel, or Heroku
- A GitHub repository with:
  - A clear README explaining:
    - The approach taken
    - Brief documentation for:
      - JWT implementation
      - Expense management
      - Spending insights endpoint

## Getting Started
1. Clone the repository:
    ```bash
    git clone https://github.com/Pavanuppula/my-expenses-.git
    ```
2. Go to the project directory:
    ```bash
    cd my-expenses-
    ```
3. Go to the frontend directory and install dependencies:
    ```bash
    cd frontend
    npm install
    ```
4. Go to the backend directory and install dependencies:
    ```bash
    cd backend
    npm install
    ```

5. start the frontend server:
    ```bash
    npm start
    ```
6. start the backend server:
    ```bash
    npm run dev
    ```
## Technologies Used
- Frontend: ReactJS
- Backend: Python/NodeJS
- Database: MongoDB/PostgreSQL (with Mongoose for Mongo or Sequelize for Postgres)
