# Movie Dataset Project - Part 1
**Student:** Neta Or Shaul  
**ID:** 323130716
**GitHub:** [View Project on GitHub](https://github.com/NetaShaul/file-ptoject)

## Project Overview
This project creates a dataset of 5,000 movies (letters U & V) by combining IMDb public data and Wikipedia web scraping.

## How to Run
1. Install requirements: `pip install pandas requests beautifulsoup4`
2. Run all cells in `Project_Part_1_Neta.ipynb`.
3. The final output is saved as `movies_dataset_final_5000.csv`.

## Data Collection & Methodology
* **Sources:** Combined IMDb datasets with supplementary movie metadata collected via Wikipedia web scraping (BeautifulSoup) and the OMDb API for data enrichment. 
* **Criteria:** Filtered for movies only, released up to 2024, with runtimes between 60-300 minutes.
* **Features:** Includes 13 fields such as ratings, genres, budget, box office, and plot summaries.
* **Data Quality:** The final 5,000 rows were chosen based on data completeness (minimal null values).

## File Structure
* `Project_Part_1_Neta.ipynb`: The complete Python pipeline (Scraping, Cleaning, Analysis).
* `movies_dataset_final_5000.csv`: The final output dataset (5,000 movies).
* `report.pdf`: Summary report and missing values analysis.
* `README.md`: This documentation.
