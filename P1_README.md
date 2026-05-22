# DecodeLabs Internship — Project 1: Data Cleaning & Preparation

**Intern:** Mudassar Abbas  
**Track:** Data Analytics  
**Batch:** 2026 | DecodeLabs  

---

## Project Overview
This project demonstrates professional data cleaning techniques applied to a raw customer sales dataset. The goal was to transform messy, unreliable data into a production-ready dataset using Python and Pandas.

## Problems Found in Raw Data
| Issue | Count |
|-------|-------|
| Missing values (Age, Revenue) | 18 |
| Duplicate rows | 1 |
| Inconsistent date formats | 20 rows |
| Text case inconsistencies | All text columns |
| Whitespace in strings | Multiple cells |

## Cleaning Steps Performed
1. **Missing Value Imputation** — Filled Age and Revenue with Median (not deleted)
2. **Duplicate Removal** — Removed 1 duplicate row
3. **Date Standardization** — Converted all formats to ISO 8601 (YYYY-MM-DD)
4. **Text Standardization** — Applied Title Case, stripped whitespace
5. **Numeric Precision** — Rounded Revenue to 2 decimal places

## Verification Results
| Check | Result |
|-------|--------|
| Missing Values | 0 — PASS |
| Duplicate Rows | 0 — PASS |
| Date Format Errors | 0 — PASS |
| Text Consistency | PASS |

## Files
- `raw_customer_data.csv` — Original messy dataset
- `Project1_Data_Cleaning.ipynb` — Full cleaning notebook with outputs
- `cleaned_customer_data.csv` — Final clean dataset

## Tools Used
- Python 3
- Pandas
- NumPy
- Jupyter Notebook
