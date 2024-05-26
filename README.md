Finance Platform
Welcome to my Finance Platform project! This platform is designed to help you manage your personal or business finances effectively. With this Finance SaaS Platform, you can track your income and expenses, categorize transactions, assign them to specific accounts, and import transactions using a CSV file. Additionally, it integrates with Plaid to connect to your bank account and uses Lemon Squeezy for monetization.

Features
Track Income and Expenses: Monitor your financial transactions with ease.
Categorize Transactions: Organize your transactions by categories for better clarity.
Account Management: Assign transactions to specific accounts.
CSV Import: Import transactions from CSV files for quick data entry.
Bank Integration: Connect to your bank account using Plaid.
Monetization: Monetize your platform using Lemon Squeezy.
Tech Stack
Frontend: Next.js, React
Backend: Hono.js
CSV Upload: Integrated CSV upload functionality
Database: PostgreSQL
Bank Integration: Plaid
Payment Processing: Lemon Squeezy
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/thounny/finance-platform.git
cd finance-platform
Install dependencies:

bash
Copy code

# For backend

cd backend
npm install

# For frontend

cd ../frontend
npm install
Set up environment variables:

Create a .env file in the root directory and add the following:

env
Copy code
PLAID_CLIENT_ID=your_plaid_client_id
PLAID_SECRET=your_plaid_secret
LEMON_SQUEEZY_API_KEY=your_lemon_squeezy_api_key
DATABASE_URL=your_postgresql_database_url
Run the application:

bash
Copy code

# For backend

cd backend
npm start

# For frontend

cd ../frontend
npm start
Usage
Track Income and Expenses:

Add your income and expense transactions manually or import them from a CSV file.
Categorize Transactions:

Assign categories to your transactions for better organization.
Account Management:

Create and manage different accounts, assigning transactions to the appropriate accounts.
CSV Import:

Import transactions using a CSV file by navigating to the import section and uploading your file.
Bank Integration:

Connect your bank account using Plaid to automatically import and sync transactions.
Monetization:

Monetize your platform by integrating Lemon Squeezy for payment processing.
