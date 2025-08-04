# Sales-Vs-Profit-Analysis-Dashboard (Tableau)
This Tableau dashboard provides a multi-dimensional analysis of sales and profit performance across different regions, states, and cities in the United States.  It includes interactive visualizations, calculated fields, and parameter controls to help users explore trends and insights in business profitability.
---

Features

### 🔹 Geographical Analysis
- **Profit by Region** – Horizontal bar chart showing total profit per region.
- **Profit by State** – Choropleth map highlighting state-wise profit performance.
- **Profit by City** – Circle map with profit density and city-wise insights.

### 🔹 Time-Based Analysis
- **Profit Growth Prediction %** – Monthly trend with forecast logic using calculated fields and dynamic growth rate control.
- **Profit Trend** – Year-over-year comparison to analyze long-term profitability.

### 🔹 Interactive Controls
- **Multi-Dimensional View Dropdown** – Filter dashboard by Region or other dimensions.
- **Growth Rate Slider** – Adjust expected profit growth and update visualizations in real-time.

---

Calculated Fields and Parameters

- `Profit Growth Prediction %` – Custom formula used to calculate month-wise forecasted profits.
- `Growth Rate` (Parameter) – Allows users to modify expected growth percentage.
- `Multi Expect` – A derived measure combining base profit and forecast logic.

> Detailed breakdown of these fields can be found in the Tableau workbook (`.twb`/`.twbx` file).

---

## Tabs in Dashboard

- **Sales/Profit**
- **Trend**
- **Sales/Profit by State**
- **Sales/Profit by City**
- **Sales/Profit Prediction**
- **Sales vs Profit Analysis**

---

## Built With

- [Tableau Desktop Public Edition](https://public.tableau.com/)
- Sample U.S. Superstore dataset (or equivalent sales data)

---

## How to Use

1. Download and open the `.twbx` file in Tableau Desktop.
2. Interact with filters and parameters to explore data from different perspectives.
3. Customize or extend the dashboard for your own business datasets.

---

## License

This project is for educational and demonstration purposes. Feel free to fork or adapt it for your own use.

---

## Author

**Ankur Sagar**

Feel free to reach out or open an issue for suggestions, improvements, or collaboration!


