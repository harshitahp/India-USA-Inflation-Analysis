**Inflation Impact Analysis with Python**

**What I Did**
I carried out an analysis to study how **inflation in India and the United States impacts the INR/USD exchange rate**.  
The goal was to check trends, correlations, and whether the **Purchasing Power Parity (PPP)** theory holds between the two countries.

**How I Did It**
**Data Used**:-
  - Inflation rates (India & USA)
  - INR/USD exchange rate (1980–2024)
**Steps**:-
  1. Cleaned and transformed inflation data into country-year format.
  2. Merged it with historical INR/USD exchange rates.
  3. Computed the **expected exchange rate** using the PPP formula.
  4. Visualized trends with **Plotly** (line charts, comparison plots).
  5. Performed **correlation analysis** to measure the relationship between inflation and exchange rate movements.

**Tools & Libraries**:- Python, Pandas, Plotly.

**Key Findings**
- The **Indian Rupee has steadily depreciated** against the US Dollar.
- **Inflation in India is more volatile** compared to the US.
- Correlation Results:
  - Inflation (India) vs Exchange Rate: **weakly negative (~ -0.34)**  
  - Inflation (US) vs Exchange Rate: **weakly positive (~ 0.24)**
- The **PPP expected exchange rate diverges** from the actual trend, showing that **factors beyond inflation** (trade balance, capital flows, policy, etc.) also drive currency movements.

**Conclusion**
Inflation impacts the exchange rate, but it’s **not the sole determinant**.  
While the PPP theory gives a baseline, real-world exchange rates depend on multiple macroeconomic factors beyond inflation.
