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

### 4. Frontend Requirements (ReactJS)
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

## Evaluation Criteria
- **Code Quality:** Clean, modular, and well-documented
- **Problem-Solving:** Efficient insights logic and smooth integration of features
- **Frontend Skills:** Clean UI/UX, responsiveness, and React best practices
- **Backend Skills:** Secure JWT handling, efficient API design, and pagination logic
- **Database Design:** Logical schema design and query optimization

## Timeline
- 2 days to complete the assignment

## Getting Started
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/expense-tracker.git
    ```
2. Install dependencies:
    ```bash
    cd expense-tracker
    npm install
    ```
3. Set up environment variables for backend:
    ```bash
    cp .env.example .env
    ```
4. Run the development server:
    ```bash
    npm start
    ```

## Technologies Used
- Frontend: ReactJS, 
- Backend: Python/NodeJS
- Database: MongoDB/PostgreSQL (with Mongoose for Mongo or Sequelize for Postgres)
