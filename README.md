# BUDGET BUDDY (Unit 7 - Milestone 1)

                      TABLE OF CONTENTS
1. Overview
2. Product Spec
3. Wireframes
   

                         OVERVIEW

### Description
Budget Buddy is a user-friendly app designed to help users 
manage their monthly expenses, track savings, and achieve 
financial goals. It works offline for core functionalities 
like budgeting and expense tracking, with optional features 
like real-time currency conversion and financial news updates.

### App Evaluation
-------------------------------------------------------------
| Attribute     | Description                                |
|---------------|--------------------------------------------|
| Category      | Finance & Productivity                    |
| Mobile        | Designed for quick, on-the-go budgeting   |
| Story         | Empowers users to control finances easily |
| Market        | Students, professionals, families         |
| Habit         | Daily/weekly use for logging expenses     |
| Scope         | Core features feasible, optional scalable |


                        PRODUCT SPEC

1. User Features (Required and Optional)

### Required Features
- Add and categorize expenses.
- Set monthly budgets and savings goals.
- Real-time currency conversion using ExchangeRate-API.
- Receive alerts when nearing budget limits.

### Optional Features
- Fetch financial news using Alpha Vantage API.
- Export expense data to CSV.
- Visualize spending trends with graphs and charts.

-------------------------------------------------------------

2. Screen Archetypes

1. **Home Screen (HomeFragment)**
   - Displays monthly budget, total expenses, and savings.
   - Quick access to:
     - Add Expense Screen.
     - Financial News Screen.
     - Budget Settings Screen.

2. **Add Expense Screen (AddExpenseFragment)**
   - Form for logging expenses:
     - Input: Amount, Category, Date.
     - Dropdown for predefined categories: Food, Transport.

3. **Budget Settings Screen (BudgetSettingsFragment)**
   - Configure monthly budgets for categories.
   - Update or modify existing budgets and savings goals.

4. **Currency Converter Screen (CurrencyConverterFragment)**
   - Input fields for base and target currencies.
   - Displays real-time conversion rate and result.

5. **Financial News Screen (FinancialNewsFragment)** (Optional)
   - View the latest financial news articles:
     - Fetch articles using Alpha Vantage API.
     - Display article titles, summaries, and sentiment labels.
     - Provide clickable links to full articles.

-------------------------------------------------------------

3. Navigation

### Tab Navigation (Tab to Screen)
1. Home - Displays budget and expenses summary.
2. Add Expense - Navigate to log new expenses.
3. Financial News - View financial tips and updates.
4. Currency Converter - Access currency conversion tool.
5. Settings - Manage budgets and preferences.

### Flow Navigation (Screen to Screen)
1. HomeFragment ➝ AddExpenseFragment
   - Via "Add Expense" button.
2. HomeFragment ➝ FinancialNewsFragment
   - Via "Financial News" button.
3. HomeFragment ➝ BudgetSettingsFragment
   - Via "Settings" button.
4. HomeFragment ➝ CurrencyConverterFragment
   - Via Tab Navigation.


