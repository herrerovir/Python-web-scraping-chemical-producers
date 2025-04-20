# 🏭 Web Scraping: Analyzing the Largest Chemical Producers Worldwide

This project presents an end-to-end data analysis workflow using **Python** to gather and explore data on the **largest chemical companies in the world (2021)**. Data is collected directly from **Wikipedia** using web scraping techniques and analyzed to discover patterns in company performance and regional distribution.

## 📑 Table of Contents

- [Introduction](#introduction)  
- [Goal](#goal)  
- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Dependencies](#dependencies)
- [How to Run the Project Locally](#how-to-run-the-project-locally)
- [Technical Skills](#technical-skills)  
- [Dataset](#dataset)  
- [Data Cleaning](#data-cleaning)  
- [Data Exploration](#data-exploration)  
- [Data Visualization](#data-visualization)  
- [Conclusion](#conclusion)

## 📌 Introduction

This project focuses on extracting and analyzing information on the world's leading chemical producers from data extracted from Wikipedia. The goal is to convert publicly available unstructured data into valuable information through a structured analysis workflow that involves data extraction, cleaning, exploration and visualization.

## 🎯 Goal

The main objective is to scrape and analyze data on the **largest chemical producers by sales in 2021**. The project aims to answer key questions such as:

- Which companies are the top sellers globally?
- Who are the fastest-growing chemical producers?
- Which countries host the most successful companies?
- What are the top-performing German chemical companies?

## 🧭 Project Overview

- Scrape structured data from Wikipedia using `BeautifulSoup`
- Clean and format the scraped data for analysis
- Explore the data to identify trends, outliers, and new features
- Visualize insights using Python libraries
- Summarize key findings and discuss future opportunities


## 📂 Repository Structure
```
Python-web-scraping-chemical-producers/
│
├── data/ 
│   ├── raw/
│   │   └── Scraped-largest-chemical-producers.csv
│   └── processed/
│       └── Largest-chemical-producers-cleaned.csv
│
├── notebooks/
│   └── web-scraping-largest-producers.ipynb
├── requirements.txt
└── README.md
```

## ⚙️ Dependencies

This project uses the following tools and libraries:

- Python 3
- Jupyter Notebooks
- `BeautifulSoup`, `requests` – Web scraping
- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Visualization

To run the **`python-web-scraping-chemical-producers`** project on your local machine, follow these detailed steps:

## 🏃‍♂️ How to Run the Project Locally

### 1. **Clone the Repository**

Start by cloning the repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/python-web-scraping-chemical-producers.git
```

Change to the project directory:

```shell
cd python-web-scraping-chemical-producers
```

### 2. **Install Dependencies**

Install the required dependencies listed in the `requirements.txt`:

```shell
pip install -r requirements.txt
```

This will install all necessary libraries such as `BeautifulSoup`, `pandas`, `requests`, `matplotlib`, and `seaborn`.

### 3. **Run the Jupyter Notebook**

After installing the dependencies, you can run the Jupyter notebook to perform the data analysis. To start the notebook, use the following command:

```shell
jupyter notebook notebooks/web-scraping-largest-producers.ipynb
```

This will open Jupyter Notebook in your default browser. The notebook will guide you through the process, from loading the raw data to performing analysis and generating visualizations.

## 🛠️ Technical Skills

- Web scraping
- Data cleaning & preprocessing
- Exploratory data analysis
- Data visualization

## 📊 Dataset

The dataset was collected via **web scraping** from Wikipedia. It contains:

- **50 entries**
- **5 columns**
- Data source: [Wikipedia – List of largest chemical producers](https://en.wikipedia.org/wiki/List_of_largest_chemical_producers)

## 🧹 Data Cleaning

To prepare the data for analysis:
- Column names were standardized for readability.
- Numeric fields were converted from strings and formatted correctly (e.g., decimal points, thousands separators).
- Errors in scraped values were corrected.
- A new column was derived from the "Headquarters" field to extract countries.

## 🔍 Data Exploration

The dataset was inspected for:
- Missing or duplicate values (none found)
- Incorrect formatting (resolved during cleaning)
- Useful new features (e.g., country of origin from headquarters)

This stage helped ensure the dataset’s quality and provided insights into potential patterns.

## 📈 Data Visualization

Data visualizations were created to clearly communicate the key findings:
- **Top-selling chemical producers**
- **Fastest-growing companies**
- **Country-wise distribution of producers**
- **German market leaders**

Visualizations were created using `matplotlib` and `seaborn`.

## ✅ Conclusion

This project provided a global view of the chemical industry in 2021 through Python-based data scraping and analysis.

**Key insights:**
- The top 5 chemical companies by sales were identified.
- Fastest-growing companies were highlighted.
- A country-wise breakdown showed where top firms are concentrated.
- Germany’s top-performing companies were analyzed separately.

## 🔭 Future Work

- **Predictive modeling:** Use machine learning to forecast company growth.
- **Expand the dataset:** Include more years or additional variables (e.g., R&D spending, employees).
- **Automate updates:** Build a pipeline to refresh the data annually.
