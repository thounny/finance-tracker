# Finance Platform

Welcome to my Finance Platform project! This platform is designed to help you manage your personal or business finances effectively. With this Finance SaaS Platform, you can track your income and expenses, categorize transactions, assign them to specific accounts, and import transactions using a CSV file. Additionally, it integrates with Plaid to connect to your bank account and uses Lemon Squeezy for monetization.

## Features

- **Track Income and Expenses:** Monitor your financial transactions with ease.
- **Categorize Transactions:** Organize your transactions by categories for better clarity.
- **Account Management:** Assign transactions to specific accounts.
- **CSV Import:** Import transactions from CSV files for quick data entry.
- **Bank Integration:** Connect to your bank account using Plaid.
- **Monetization:** Monetize your platform using Lemon Squeezy.

## Tech Stack

- **Frontend:** Next.js, React
- **Backend:** Hono.js
- **CSV Upload:** Integrated CSV upload functionality
- **Database:** PostgreSQL
- **Bank Integration:** Plaid
- **Payment Processing:** Lemon Squeezy

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/thounny/finance-tracker.git
   cd finance-platform
   ```

2. **Install dependencies:**

   ```bash
   # For backend
   cd backend
   npm install

   # For frontend
   cd ../frontend
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add the following:

   ```env
   PLAID_CLIENT_ID=your_plaid_client_id
   PLAID_SECRET=your_plaid_secret
   LEMON_SQUEEZY_API_KEY=your_lemon_squeezy_api_key
   DATABASE_URL=your_postgresql_database_url
   ```

4. **Run the application:**

   ```bash
   # For backend
   cd backend
   npm start

   # For frontend
   cd ../frontend
   npm start
   ```

## Usage

1. **Track Income and Expenses:**

   - Add your income and expense transactions manually or import them from a CSV file.

2. **Categorize Transactions:**

   - Assign categories to your transactions for better organization.

3. **Account Management:**

   - Create and manage different accounts, assigning transactions to the appropriate accounts.

4. **CSV Import:**

   - Import transactions using a CSV file by navigating to the import section and uploading your file.

5. **Bank Integration:**

   - Connect your bank account using Plaid to automatically import and sync transactions.

6. **Monetization:**
   - Monetize your platform by integrating Lemon Squeezy for payment processing.
