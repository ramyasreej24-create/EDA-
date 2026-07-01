# EDA Analysis Project

Exploratory Data Analysis (EDA) notebook that scrapes company data (Top 500 companies list from [Screener.in](https://www.screener.in/screens/355742/top-500-companies/)) and analyzes it using Python's data science stack.

## 📁 Contents

- `EDA_Analysis_Project.ipynb` — Jupyter notebook containing the data scraping and analysis workflow.

## 🛠️ Tech Stack

- **Python 3**
- **pandas** — data manipulation
- **numpy** — numerical computing
- **matplotlib** / **seaborn** — data visualization
- **requests** — HTTP requests for web scraping
- **BeautifulSoup (bs4)** — HTML parsing
- **re** — regular expressions for text cleaning

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3 installed, then install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn requests beautifulsoup4
```

### Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

3. Open `EDA_Analysis_Project.ipynb` and run the cells in order.

## 📊 Project Overview

This notebook:
- Scrapes company data from a public financial data source (Screener.in Top 500 companies screen)
- Parses and cleans the HTML content into structured data
- Performs exploratory data analysis to uncover patterns, trends, and relationships in the data
- Visualizes findings using matplotlib and seaborn

## 📌 Notes

- Web scraping is dependent on the target website's structure; if Screener.in updates its page layout, the scraping logic may need adjustments.
- Please review and respect the target website's `robots.txt` and terms of service before running scraping scripts.

## 📄 License

This project is open source and available for personal and educational use.
