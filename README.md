# Personal Finance Visualizer

## Overview
Personal Finance Visualizer is a web application built using Next.js, React, and MongoDB to help users track their expenses, categorize transactions, and set monthly budgets. It provides insightful visualizations using Recharts.

## Features
### Stage 1: Basic Transaction Tracking
- Add, edit, and delete transactions
- Transaction list view
- Monthly expenses bar chart
- Basic form validation

### Stage 2: Categories
- Predefined categories for transactions
- Category-wise pie chart
- Dashboard with summary cards: total expenses, category breakdown, and most recent transactions

### Stage 3: Budgeting
- Set monthly category budgets
- Budget vs. actual comparison chart
- Simple spending insights

## Tech Stack
- **Frontend:** Next.js, React, shadcn/ui
- **Data Visualization:** Recharts
- **Database:** MongoDB (for transaction storage)
- **Styling:** Tailwind CSS

## Installation
1. Clone the repository:
   ```sh
   git clone
   ```
2. Navigate to the project directory:
   ```sh
   cd personal-finance-visualizer
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```


## Usage
1. Add transactions by entering the amount, description, and date.
2. Categorize transactions using predefined categories.
3. View expense breakdown via charts and summaries.
4. Set budgets for each category and compare them with actual spending.

## Deployment
To deploy the application, use platforms like Vercel or Netlify:
```sh
vercel deploy
```
Ensure the database connection is properly configured in the environment variables.

## Contribution
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License
This project is open-source and available under the MIT License.

