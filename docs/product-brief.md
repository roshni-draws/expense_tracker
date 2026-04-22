# MoneyMate — Product Brief

**Captured:** 2026-04-22
**Source:** Initial user prompt

---

## Product

**MoneyMate** — a personal finance dashboard with an embedded AI financial advisor.

## Design Aesthetic

- Warm beige background (#F5EFE0)
- Colorful pastel cards with organic shapes, `rounded-3xl` corners
- Soft shadows, playful and friendly
- Pastel palette: soft yellow, mint green, light blue, soft pink, light purple
- Modern, clean typography

## Core Features

### 1. Monthly Income Section
- Large input field for monthly salary
- Display total available funds prominently
- Warm beige/peachy background card

### 2. Fixed Expenses (4 separate colorful cards)
- Rent & Credit Card Bills — pastel yellow/orange
- Maintenance & Electricity — pastel green
- Rented Furniture — pastel blue
- Travel — pastel pink
- Each with emoji icon and number input

### 3. Subscriptions Panel
- List of recurring subscriptions
- Add/remove functionality
- Shows total subscription costs
- Light purple background

### 4. Savings Goals
- Create multiple savings goals
- Progress bars for each goal
- Target amounts
- Light green background

### 5. Financial Summary Sidebar
- Total income
- Total expenses
- Remaining balance (color-coded: green if positive, red if negative)
- Savings percentage of income

### 6. AI Financial Advisor Chat Panel
- Embedded chat interface (right sidebar)
- Ask questions about spending, affordability, budgeting
- AI responds with personalized advice based on actual financial data
- Context-aware (knows income, expenses, goals)
- Chat history during session
- Light purple background

## Functional Requirements

- Real-time calculations: total expenses, remaining balance, savings rate
- Add/remove subscriptions and goals
- AI advisor answers: affordability, savings strategies, budget optimization, subscription audits
- Data stored in component state only (no backend)
- Responsive layout: mobile, tablet, desktop

## Technical Constraints

- React with hooks
- No external backend
- Smooth transitions and hover states
- Tailwind CSS for styling
