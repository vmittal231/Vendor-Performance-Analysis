# Vendor Performance Analysis

## Project Overview
An end-to-end data analytics project focused on analyzing vendor performance, purchasing patterns, sales trends, profitability, and inventory efficiency using Python, SQL, and statistical analysis.

## Objectives
- Analyze vendor-level sales and purchasing performance.
- Identify high-performing and underperforming brands.
- Evaluate vendor contribution to total purchase expenditure.
- Analyze bulk purchasing patterns and unit purchase prices.
- Identify vendors associated with slow-moving inventory.
- Perform statistical hypothesis testing to compare profit margins across sales groups.

## Tech Stack
- **Programming:** Python
- **Database:** SQL, SQLite
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Environment:** Jupyter Notebook, VS Code

## Project Structure
- `notebooks/` – Database setup, exploratory data analysis, and vendor performance analysis.
- `src/` – Data ingestion and vendor summary scripts.
- `requirements.txt` – Required Python libraries.

## Key Findings
- The top 10 vendors accounted for 65.69% of total purchase expenditure.
- DIAGEO NORTH AMERICA INC was the highest-selling vendor in the analyzed dataset.
- Jack Daniels No 7 Black was the highest-selling brand.
- Larger purchase groups had lower average unit purchase prices in the dataset.
- Statistical testing identified a significant difference in average profit margins between high-sales and low-sales groups.

## How to Run
1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Configure the source dataset and SQLite database.
4. Run the notebooks in the recommended order:
   - Database Setup
   - Exploratory Data Analysis
   - Vendor Performance Analysis

## Note
The original source datasets and generated SQLite database are not included in this repository. You must configure the required data files locally before running the complete analysis.