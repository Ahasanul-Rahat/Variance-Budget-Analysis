# Variance-Budget-Analysis
---

# **Budget vs Actual – Variance Analysis Dashboard**

A dynamic **Excel-based budgeting model** that tracks **actual vs budget performance**, calculates **variance and variance %**, and provides **interactive category, area, and product-level dashboards**.

---

## **📊 Project Overview**

This project demonstrates a **robust financial analysis workflow** using Excel:

* **Dynamic variance calculations** using `SUMIFS` and helper columns
* **PivotTables with calculated fields** for multi-level aggregation
* **Interactive dashboards** showing Variance & Variance % for management insights
* **Drill-down analysis** by **Category**, **Area/Region**, and **Product**

---

## **🎯 Objectives**

1. Track **budget vs actual performance** for different dimensions (category, area, product).
2. Identify **over- and under-performing areas** for informed decision-making.
3. Build a **dynamic dashboard** for real-time visualization.
4. Demonstrate advanced **Excel modeling techniques** suitable for finance and business analytics roles.

---

## **🗂️ Dataset**

* Source: [Kaggle – Budget vs Actual Financial Dataset](https://www.kaggle.com/datasets/kennathalexanderroy/budget-vs-actual-financial-dataset)
* Key columns used:

  * `Category` – e.g., Marketing, Sales, Operations
  * `Area / Region` – e.g., North, South
  * `Product` – e.g., Product A, Product B
  * `Budget` – Planned expenditure
  * `Actual` – Actual expenditure
  * `Period / Month` – Month or fiscal period

---

## **🛠️ Project Structure**

| Sheet           | Purpose                                                    |
| --------------- | ---------------------------------------------------------- |
| `Raw_Data`      | Original dataset with Budget & Actual figures              |
| `Dynamic_Table` | Lookup-driven calculations for Variance & Variance %       |
| `PivotTables`   | Multi-dimensional aggregation by Category / Area / Product |
| `Dashboard`     | Interactive visualizations for Variance & Variance % only  |

---

## **📈 Key Features**

* **Dynamic Variance Calculation:**

  ```excel
  Variance = Actual - Budget
  Variance % = (Actual - Budget) / Budget
  ```

* **Multi-dimensional Analysis:** Drill down by **Category**, **Area**, **Product**, or **Period**.

* **Interactive Dashboard:**

  * Variance displayed as **columns**
  * Variance % displayed as **line chart (secondary axis)**
  * Filters via **Slicers** or dropdowns for dynamic reporting

* **Conditional Formatting:** Quickly highlights over/under budget areas.

---

## **💻 How to Use**

1. Open `Budget_vs_Actual.xlsx`.
2. Go to **Dynamic Table** or **PivotTables** to explore variance analysis.
3. Use **Dashboard** sheet to view visual trends:

   * Select **Category, Area, or Product** from slicers/dropdowns
   * Observe **Variance & Variance %** charts updating dynamically

---

## **📌 Skills Demonstrated**

* Advanced **Excel formulas** (`SUMIFS`, `IF`, dynamic tables)
* PivotTables with **Calculated Fields**
* **Data visualization & dashboarding**
* Multi-level **variance analysis**

---

## **🔗 Project Preview**

<img width="1200" height="800" alt="Screenshot 2026-01-14 231228" src="https://github.com/user-attachments/assets/1d977341-fcfc-425a-a691-f640345fa16f" />



