# 📊 Excel Dynamic Functions Portfolio: SORT, FILTER & TAKE Operations

## Overview
This Excel workbook demonstrates the power of dynamic array functions—especially `SORT`, `FILTER`, and `TAKE`—to build modular, formula-driven dashboards for sales and order analysis. It showcases how to extract insights from raw data without relying on manual filtering or pivot tables.

## 🔧 Functions Used
- `SORT(array, [sort_index], [sort_order])`
- `FILTER(array, include, [if_empty])`
- `TAKE(array, rows)`
- `SORTBY(array, by_array1, [sort_order1], ...)`
- Supporting functions: `UNIQUE`, `SEQUENCE`, `INDEX`, `LET`

## 📁 Sheet Highlights

| Sheet Name                          | Description                                                       |
|------------------------------------|-------------------------------------------------------------------|
| `North Region Big Deals`           | Filters high-value orders from the North region                   |
| `HIGH VALUE ORDERS (Using - Filter)` | Extracts orders marked as "High Value" using dynamic filtering    |
| `Region then Profit`               | Sorts orders first by region, then by descending profit           |
| `Top 10 Revenue Leaders`           | Displays top 10 orders by revenue using `SORT` + `TAKE`           |
| `Filter + Sort - North Region Ranked` | Combines filter and sort to rank North region orders by revenue |
| `top 5 laptop sales by revenue`    | Isolates top 5 laptop orders using category and revenue filters   |

## 🛠️ How to Use
1. **Excel Version**: Ensure you're using Excel 365 or Excel 2021+ (dynamic arrays required).
2. **Explore Sheets**: Each sheet demonstrates a unique use case or formula combination.
3. **Customize Filters**: Modify formulas to change criteria (e.g., region, product, value tier).
4. **Extend Logic**: Use `LET` and `LAMBDA` to modularize and reuse logic across sheets.

## 💡 Tips
- Use named ranges or structured tables for cleaner formulas.
- Combine `FILTER` with `ISNUMBER(SEARCH(...))` for partial text matches.
- Use `SORTBY` with multiple arrays for advanced multi-criteria sorting.

## 📈 Ideal For
- Sales analysts
- Excel enthusiasts
- BI professionals
- Anyone building formula-driven dashboards

---
