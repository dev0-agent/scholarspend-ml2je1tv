# Task List

This file shows the current progress of all tasks in this project.
It is automatically updated by dev0 as tasks are completed.

---

## Phase 1

- [ ] ⏳ **Project Initialization & Configuration**
  Initialize a new TanStack Start project. Configure Tailwind CSS for styling. Set up the basic folder structure for routes and components. Ensure the dev server runs correctly.

- [ ] ⏳ **Database Schema & Drizzle Setup**
  Set up SQLite with Drizzle ORM. Create a schema defining a 'transactions' table with fields: id, amount, type (income/expense), category, description, and date. Create a 'budgets' table for monthly limits. Generate migration files and run the initial migration.

- [ ] ⏳ **Core Layout & Navigation**
  Create the main application shell using TanStack Router's root layout. Implement a responsive Navbar/Sidebar with links to Dashboard, History, and Analytics. Include a placeholder for the 'Add Transaction' button.

## Phase 2

- [ ] ⏳ **Server Functions for Transactions**
  Implement TanStack Start Server Functions to handle CRUD operations: `getTransactions`, `createTransaction`, `deleteTransaction`. Ensure these functions interact correctly with the Drizzle/SQLite database and return typed responses.

- [ ] ⏳ **Transaction Entry Form**
  Build a form component using `react-hook-form` and `zod`. Fields: Amount, Type (toggle), Category (select), Date, Description. Connect the form submission to the `createTransaction` Server Function. Implement optimistic updates or query invalidation upon success.

- [ ] ⏳ **Dashboard Summary Components**
  Create the Dashboard view. Implement a 'Total Balance' card and a 'Monthly Spend' card. Fetch data using the server functions created in task-4 via TanStack Query loaders.

- [ ] ⏳ **Transaction History List**
  Develop a list view to display recent transactions. Group them by date. Implement the ability to delete a transaction using the `deleteTransaction` server function. Add basic empty state if no data exists.

## Phase 3

- [ ] ⏳ **Analytics Visualization**
  Install `recharts` or similar. Create a new route `/analytics`. Implement a Pie Chart showing expense distribution by category. Aggregate the data on the client or create a specific server function for aggregation.

- [ ] ⏳ **Budget Settings & Progress Bar**
  Create a simple settings modal/page to set a 'Monthly Budget Limit' (store in DB or local storage for simplicity). Add a progress bar to the Dashboard showing (Current Spend / Monthly Limit) * 100.

## Phase 4

- [ ] ⏳ **UI Polish & Responsive Design**
  Refine the Tailwind styling. Ensure cards look good on mobile. Add color-coding for categories (e.g., Food = Orange, Transport = Blue). Add simple transitions for list items.

- [ ] ⏳ **Error Handling & Validation**
  Add proper error boundaries for route loaders. Ensure the form displays validation errors (e.g., negative numbers, missing fields). Add toast notifications for success/failure actions.

---

_Last updated by dev0 automation_
