# task_10_DA
Scrape and Analyze Job Listings for Data Analyst Roles

# Job Listings Scraper for Data Analyst Roles

## Project Overview
This project scrapes and analyzes job listings for **Data Analyst** roles from the Internshala job portal. The goal is to collect structured job data and perform basic analysis to gain insights such as popular locations and in-demand skills.
The project is implemented in a **Jupyter Notebook** using Python, Selenium, BeautifulSoup, and pandas.

## Files Attached
### 1. Python Notebook (`Scrapping.ipynb`)
- Contains the complete scraping logic using Selenium and BeautifulSoup.
- Extracts job details including:
  - Job title
  - Company name
  - Location
  - Stipend
  - Skills
- Performs data cleaning by removing incomplete or missing entries.
- Analyzes the dataset to summarize key findings.
- Generates visualizations such as bar plots for top job locations.

### 2. CSV File (`internshala_data_analytics_jobs.csv`)
- Contains the final structured dataset after scraping and cleaning.
- Includes all the extracted job information from the Internshala page.
- Ready for further analysis or reporting.

### Summary of Findings
#### **Total Jobs Scraped**
- The notebook scrapes and collects job listings from Internshala.
- The total number of jobs scraped is displayed in the notebook and stored in the CSV.

####  **Top Locations**
- The dataset is analyzed to identify the locations with the most job listings.
- Top 5 locations are visualized using a bar plot.

#### **Most In-demand Skills**
- Skills from job postings are aggregated and analyzed.
- The notebook summarizes the most frequently mentioned skills in the dataset.

#### **Challenges Faced**
- Dynamic content required Selenium to load job listings.
- Some entries lacked certain fields (location, stipend, skills), requiring data cleaning.
- Variability in website structure led to the need for robust selectors.

### Visuals
- **Top 5 Job Locations**: A pie chart representing the most common locations for data analyst job postings.
- **Bar Graph for Top Skills**: A pie chart representing the top skills for data analyst job postings.
- Additional insights can be explored by analyzing the provided CSV file.

---

## 🛠 Tools Used
- Python
- Selenium (for interacting with dynamic content)
- BeautifulSoup (for parsing HTML)
- pandas (for data manipulation and analysis)
- matplotlib or seaborn (for visualization)
- ChromeDriver (for Selenium)
