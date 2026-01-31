# ScholarSpend 🎓💸

> Smart, student-centric finance tracking powered by TanStack Start.

## Overview

ScholarSpend is a full-stack expense manager designed to help students keep track of their finances without the headache of complex accounting software. Built with the modern **TanStack Start** framework, it offers a snappy, server-rendered experience with real-time data persistence.

Whether you're tracking textbook costs or late-night pizza runs, ScholarSpend gives you a clear visual breakdown of where your money is going and helps you stick to your monthly budget.

## Tech Stack

- **Framework:** TanStack Start (React + Vinxi)
- **Routing:** TanStack Router
- **Data Fetching:** TanStack Query
- **Database:** SQLite
- **ORM:** Drizzle ORM
- **Styling:** Tailwind CSS
- **Validation:** Zod

## Features

- 📊 **Dashboard:** Instant view of current balance and monthly spending.
- 💸 **Quick Add:** Rapid transaction entry optimized for mobile.
- 📈 **Analytics:** Visual breakdown of spending categories.
- 📝 **History:** Searchable list of past income and expenses.
- 🛑 **Budget Caps:** Set monthly limits and track progress.

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/scholarspend.git
   cd scholarspend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Setup Database**
   Ensure you have the environment variables set up (if applicable) and push the schema:
   ```bash
   npm run db:push
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000` to start tracking!

## Documentation

- [Task List](./TASKLIST.md) - Track project progress
- [Learnings](./LEARNINGS.md) - Technical insights and decisions
- [Rules](./.dev0/RULES.md) - AI Coding Agent guidelines