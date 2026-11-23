# TWDP: Retail Sales Data Analysis

## Project Overview
This Jupyter Notebook (`TWDP.ipynb`) contains an exploratory data analysis (EDA) workflow for a retail sales dataset. The project begins by loading raw transactional data into a Pandas DataFrame and inspecting its structure, with the goal of uncovering insights into sales performance, product trends, and customer behavior.

## Dataset
- **File:** `retail_sales_raw 2.csv`
- **Location:** `Downloads/` (local path used in the notebook)
- **Format:** CSV (Comma-Separated Values)
- **Content:** Retail sales transactions (columns include order details, product information, pricing, and customer data — exact schema will be shown by `df.head()`).

> **Note:** The notebook currently references a local file path (`Downloads/retail_sales_raw 2.csv`). To make the notebook portable, consider uploading the CSV to the same repository and changing the path to a relative one, e.g., `pd.read_csv('retail_sales_raw 2.csv')`.

## Notebook Structure

### 1. Data Loading & Initial Inspection
```python
import pandas as pd

df = pd.read_csv('Downloads/retail_sales_raw 2.csv')
df.head()
