# 📈 HR/Sales Performance Analysis with Advanced Excel Logic

This project showcases mastery in using **seven advanced logical functions** in Microsoft Excel to automate complex business rules, specifically for an **Employee Performance and Bonus Analysis** scenario.

The analysis evaluates employee metrics, assigns performance grades, checks eligibility, and determines tiered bonus structures while ensuring calculations are robust and error-free.

---

## 🔑 Key Excel Concepts Demonstrated

This workbook applies a comprehensive set of logical operations to transform raw data into actionable business decisions.

| Excel Function | Project Application | Outcome / Data Result |
| :--- | :--- | :--- |
| **IF** | Determines the basic status based on a single condition (e.g., did they hit the revenue goal?). | `Met Target` or `Below Target` Status |
| **Nested IF** | Assigns granular performance grades based on multiple thresholds. | `Excellent` / `Good` / `Average` / `Poor` Grade |
| **AND** | Checks bonus eligibility—all mandatory criteria must be true. | Bonus Eligibility Status (Must meet **ALL** criteria) |
| **OR** | Awards special recognition if an employee meets at least one specific high-level goal. | Special Recognition Status (Meets **ANY** criteria) |
| **NOT** | Flags individuals who do *not* meet a minimum, mandatory improvement standard. | `Needs Improvement` Flag |
| **IFS** | Calculates tiered, conditional bonus amounts efficiently without nesting. | Variable Bonus Payout ($) |
| **IFERROR** | Ensures commission rate calculations do not break if a prerequisite value is zero. | Error-Protected Commission Rate Calculation |

---

## 📊 Analysis Highlights

* **Automated Grading:** Performance grades are instantly assigned based on a complex Nested IF structure.
* **Tiered Bonus:** The `IFS` function provides a clean, scalable method for calculating variable payouts.
* **Eligibility Gates:** The `AND` and `OR` functions clearly define the multiple, complex paths to receiving incentives.
* **Robust Error Handling:** The use of `IFERROR` demonstrates a focus on producing clean, reliable reports.

---

## 🛠️ Getting Started

### Prerequisites

You only need Microsoft Excel (or a compatible spreadsheet program) to open the file.

### Repository Content

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/aryandadwal001/excel-data-analysis-portfolio.git](https://github.com/aryandadwal001/excel-data-analysis-portfolio.git)
    ```
2.  **Open the Excel file:** Navigate to the project directory and open `[Your Excel File Name Here].xlsx` to examine the formulas in the calculated columns.

---

## 🖼️ Visual Snapshot (Optional but Recommended)

*(If you include a screenshot of your final table or chart, place the image file in your repository, and update the filename below.)*

![Screenshot of the Final Sales Analysis Dashboard](analysis_screenshot.png)

---

**Author:** Aryandadwal001
**Date:** October 2025
**License:** [MIT/Standard (Recommend including a LICENSE.txt file)]
