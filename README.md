# Stack Overflow Survey 2024 Data Analytics

This project provides a complete workflow for analyzing and visualizing data from the Stack Overflow Survey 2024. It covers the full data analytics pipeline, from data collection to dashboard creation, using Python and Jupyter Notebooks.

## Project Structure

- **01 Data Collection/**
	- Collects job and technology data using APIs and web scraping.
	- Contains raw data files (CSV, Excel, JSON) and notebooks for data acquisition.

- **02 Data Wrangling/**
	- Cleans, normalizes, and preprocesses the collected data.
	- Includes notebooks for handling missing values, removing duplicates, and preparing data for analysis.

- **03 EDA/** (Exploratory Data Analysis)
	- Performs statistical analysis and explores data distributions, outliers, and correlations.
	- Notebooks provide step-by-step EDA processes.

- **04 Data Visualisation/**
	- Visualizes data using various chart types (histograms, box plots, scatter plots, pie charts, stacked charts, line charts, bar charts).
	- Notebooks demonstrate how to create and interpret each visualization.

- **05 Dashboards/**
	- Contains PDF dashboards summarizing key findings:
		- Current Technology Usage
		- Demographics
		- Future Technologies

## How to Use

1. **Clone the repository**
	 ```powershell
	 git clone https://github.com/aimless-coder/stackoverflow_survey_2024_data_analytics.git
	 ```
2. **Navigate to the project directory**
	 ```powershell
	 cd stackoverflow_survey_2024_data_analytics
	 ```
3. **Open Jupyter Notebooks**
	 - Use JupyterLab or VS Code to open and run the notebooks in each folder.

## Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Common data science libraries: pandas, numpy, matplotlib, seaborn, etc.

Install dependencies (if needed):
```powershell
pip install pandas numpy matplotlib seaborn openpyxl
```

## Folder Details

### 01 Data Collection
- Notebooks: `Collecting_job_data_using_APIs-Lab.ipynb`, `Jobs_API (1).ipynb`, `Web-Scraping-Lab.ipynb`
- Data files: `job-postings.xlsx`, `jobs_by_technology.xlsx`, `jobs_data.xlsx`, `jobs.json`, `popular-languages.csv`
- Initial exploration: `M1ExploreDataSet-lab_V2.ipynb`

### 02 Data Wrangling
- Notebooks: `Hands-on Lab 7-10`, `M2DataWrangling-lab-v2.ipynb`
- Cleaned data: `cleaned_survey_data.csv`

### 03 EDA
- Notebooks: `Hands-on Lab Exploratory Data Analysis.ipynb`, `Lab 11-13`

### 04 Data Visualisation
- Notebooks: `Lab 14-21`, `Lab Data Visualization.ipynb`

### 05 Dashboards
- Dashboards: `Current_Technology_Usage.pdf`, `Demographics.pdf`, `Future_Technologies.pdf`

## License

This project is for educational and research purposes.

## Author

- [aimless-coder](https://github.com/aimless-coder)
