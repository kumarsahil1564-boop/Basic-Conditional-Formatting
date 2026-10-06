# Task 29 – Basic Conditional Formatting: Rules List

## Dataset
Retail Sales

## Conditional Formatting Rules
1. **Revenue** – Apply a 3-color scale:
   - Low values → Red
   - Middle values → Yellow
   - High values → Green
   - Purpose: quickly compare revenue performance.

2. **Profit** – Highlight values **>= ₹12,000**.
   - Purpose: identify high-profit sales.

3. **Units Sold** – Highlight values **>= 30**.
   - Purpose: identify high-volume sales.

4. **Profit Margin** – Highlight values **< 20%** in red.
   - Purpose: flag low-margin transactions.

5. **Profit Margin** – Highlight values **>= 25%** in green.
   - Purpose: identify stronger-margin transactions.

## Edge Cases Tested
- Values exactly equal to 30 units are highlighted.
- Values exactly equal to ₹12,000 profit are highlighted.
- Profit margin exactly 20% is not marked as low.
- Profit margin exactly 25% is marked as strong.
