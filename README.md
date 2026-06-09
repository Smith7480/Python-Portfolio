# Joe's Interactive Expense Tracker
A resilient, production-ready command-line application built in Python to help users manage their monthly budgets and track categorised expenses.

## Key Features
- **Custom Budget Initialisation**: Dynamic starting financial threshold set by the user.
- **Robust Exception Handling**: Completely crash-proof input validation systems using `try/except` filters for monetary inputs.
- **Dynamic Session Dashboard**: Real-time console utilities including an in-progress log reviewer (`View`) and an absolute target deletion/refund engine (`Remove`).
- **Defensive Design Patterns**: String stripping and uniform token parsing (`.strip().title()`) to guarantee total immunity to lowercase or whitespace human entry errors.

## Technical Concepts Mastered
- Dynamic Dictionary & Matrix Mutations
- Control Flow Routing (`while True`, `break`, `continue`)
- Exception Handling & Data Validation (`ValueError`)
- Human-Centric Terminal Interface Design (UX)
