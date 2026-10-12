# Week 4 Lab: Savings Goal Planner

## Task

Create `lab04_savings_planner.py`. Ask for a starting balance, a monthly deposit, a monthly interest rate (%) and a savings goal. Re-prompt when the starting balance or interest rate is negative, or when the deposit or goal is not positive.

Simulate the savings month by month. Each month, first add interest on the current balance (`balance * rate / 100`), then add the deposit. Print one table row per month showing the month number, the interest earned that month and the new balance. Stop as soon as the balance reaches the goal. Stop after 60 months if the goal is still not reached.

At the end, print whether the goal was reached and in how many months, the final balance and the total interest earned.

## Acceptance Checks

1. A balance exactly equal to the goal counts as reached. Starting balance `0`, deposit `1000`, rate `0`, goal `3000` reaches the goal in 3 months.
2. Starting balance `1000`, deposit `500`, rate `1`, goal `3000` reaches the goal in 4 months with a final balance of `3070.80` and total interest of `70.80`.
3. Starting balance `0`, deposit `10`, rate `0`, goal `10000` stops after 60 months with a final balance of `600.00` and a "not reached" message.
4. If the starting balance already meets the goal, the program says so and prints no table rows.
5. Use at least one `while` loop for input validation and `break` to stop the monthly loop early.

## GitHub Submission

1. Create `week04/lab-quiz/` in your own course repository and save `lab04_savings_planner.py` there. Keep weekly homework in `week04/` outside this folder.
2. Add a short README note with one test you ran and one thing you changed after testing.
3. Commit with a specific message, such as `week04: complete savings goal planner`.
4. Show the running program and your commit history to the instructor.

## Assessment (10 Points)

- Working behavior and required rules: 5
- Meaningful tests, including a boundary or error case: 2
- Readable names and clear output: 2
- GitHub commit and README note: 1
