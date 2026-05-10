# Movie Dataset Project - Part 1
**Student:** Neta Or Shaul  
**ID:** 323130716

## Project Overview
This project creates a dataset of 5,000 movies (letters U & V) by combining IMDb public data and Wikipedia web scraping.

## How to Run
1. Install requirements: `pip install pandas requests beautifulsoup4`
2. Run all cells in `Project_Part_1_Neta.ipynb`.
3. The final output is saved as `movies_dataset_final_5000.csv`.

## Data Collection
- **Initial Data:** Filtered from IMDb datasets (Movies, 1900-2024, 60-300 min).
- **Enrichment:** Scraped Wikipedia for Language, Country, Budget, Box Office, and Plot.
- **Selection:** The final 5,000 rows were chosen based on data completeness (minimal null values).

# Movie Dataset Project - Part 1
**Student:** Neta Or Shaul  
**ID:** 323130716

---

## Project Description
This project builds a dataset of 5,000 movies starting with the letters **U** and **V**. It combines official IMDb data with additional metadata scraped from Wikipedia.

## Data Collection & Methodology
***Sources:** Combined IMDb datasets with supplementary movie metadata collected via Wikipedia web scraping (BeautifulSoup) and the OMDb API for data enrichment. 
* **Criteria:** Filtered for movies only, released up to 2024, with runtimes between 60-300 minutes.
* **Features:** Includes 13 fields such as ratings, genres, budget, box office, and plot summaries.
* **Data Quality:** The final 5,000 records were selected based on maximum data completeness.

## File Structure
* `Project_Part_1_Neta.ipynb`: The complete Python pipeline (Scraping, Cleaning, Analysis).
* `movies_dataset_final_5000.csv`: The final output dataset (5,000 movies).
* `report.pdf`: Summary report and missing values analysis.
* `README.md`: This documentation.

## How to Run
1. Install requirements: `pip install pandas requests beautifulsoup4`
2. Run all cells in `Project_Part_1_Neta.ipynb`.
3. The final output is saved as `movies_dataset_final_5000.csv`.


#