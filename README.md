# Expense Tracker

This is a web application for tracking expenses and income, built with Vue.js and using vue-toastification for toast notifications. The app helps users manage their finances by displaying income, expenses, balance, and transaction history.

## Features

- **Income & Expense Tracking:** View total income, expenses, and current balance.
- **Transaction History:** See a history of all transactions with the ability to delete individual entries.
- **Expense Formatting:** Enter expenses by starting with a '-' followed by the amount.
- **Toast Notifications:** Get feedback and notifications using vue-toastification.

## Tech Stack

- **Frontend:** Vue.js
- **Toast Notifications:** vue-toastification

## Installation

### Prerequisites

- Node.js & npm

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/HoussemMhiri/Expenses_Tracker.git
    cd expense-tracker
    ```

2. Install JavaScript dependencies:

    ```bash
    npm install
    ```

3. Run the development server:

    ```bash
    npm run dev
    ```

4. Visit `http://localhost:8080` in your browser to access the application.

## Usage

1. **Add Transactions:** Enter income and expenses. Expenses should start with '-' followed by the amount (e.g., `-50`).
2. **View Balances:** Check your total income, expenses, and current balance on the dashboard.
3. **View History:** See a list of your transactions and delete any entry if needed.
4. **Notifications:** Receive toast notifications for actions and updates.

## Configuration

You can customize the toast notifications by editing the configuration in your Vue app’s `main.js` file.

### Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.
 
### Contact
For any inquiries, feel free to reach out to me at houssemmhiri95@gmail.com.
