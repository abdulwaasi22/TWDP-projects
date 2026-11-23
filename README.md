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



# TWDP: Data Analysis & Visualization Practice

## Project Overview
This Jupyter Notebook (`TWDP.ipynb`) is a practice workbook demonstrating foundational data science skills using Python. It covers two core tasks:

1. **Data Loading with Pandas** – Reading a raw retail sales CSV file into a DataFrame.
2. **Data Visualization with Matplotlib** – Plotting a dual-line chart of daily temperature and humidity for Lagos.

## Notebook Contents

### Part 1: Loading Retail Sales Data (Pandas)
```python
import pandas as pd

df = pd.read_csv('Downloads/retail_sales_raw 2.csv')
df.head()



# TWDP: Python Data Analysis & Visualization Practice

## Project Overview
This Jupyter Notebook (`TWDP.ipynb`) is a hands-on practice workbook demonstrating foundational Python data analysis and visualization skills. It covers:

1. **Loading a retail sales dataset** with Pandas.
2. **Plotting a dual-line weather chart** with Matplotlib (hardcoded data).
3. **Filtering and aggregating a weather dataset** by city using Pandas.

## Notebook Contents

### Part 1: Loading Retail Sales Data (Pandas)
```python
import pandas as pd

df = pd.read_csv('Downloads/retail_sales_raw 2.csv')
df.head()


# TWDP: Python Data Analysis & Visualization Practice

## Project Overview
This Jupyter Notebook (`TWDP.ipynb`) is a hands-on practice workbook demonstrating foundational Python data analysis and visualization skills. It covers data loading, filtering, aggregation, and plotting using **Pandas** and **Matplotlib**.

## Notebook Contents

### Part 1: Loading Retail Sales Data (Pandas)
```python
import pandas as pd

df = pd.read_csv('Downloads/retail_sales_raw 2.csv')
df.head()



# TWDP: Python Data Analysis & Visualization Practice

## Project Overview
This Jupyter Notebook (`TWDP.ipynb`) is a hands-on practice workbook demonstrating foundational Python data analysis and visualization skills. It covers data loading, filtering, aggregation, and plotting using **Pandas**, **Matplotlib**, and **Seaborn**.

## Notebook Contents

### Part 1: Loading Retail Sales Data (Pandas)
```python
import pandas as pd

df = pd.read_csv('Downloads/retail_sales_raw 2.csv')
df.head()
