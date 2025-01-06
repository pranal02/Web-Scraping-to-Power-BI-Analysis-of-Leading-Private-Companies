# Web-Scraped Insights: Visualizing Top U.S. Private Companies

This project involves web scraping data on the top private companies in the U.S. and visualizing the extracted data in Power BI. The interactive dashboard provides valuable insights into key company metrics such as revenue, industry, number of employees, and headquarters location.

---

## Project Overview

The goal of this project is to analyze and visualize data of the top U.S. private companies. The data is scraped from publicly available online sources, processed, and presented in an interactive Power BI dashboard. Users can explore key metrics, including:

- **Revenue** (in USD billions)
- **Number of employees**
- **Industry classification**
- **Headquarters location**

---

## Data Source

The data was extracted using web scraping techniques from publicly available sources. The dataset contains the following attributes:

- **Rank**
- **Company Name**
- **Industry**
- **Revenue (in USD billions)**
- **Number of Employees**
- **Headquarters Location**

---

## Dashboard Features

The Power BI dashboard includes a variety of interactive visualizations for in-depth analysis:

1. **Bar Chart**: Top companies ranked by revenue.
2. **Bar Chart**: Number of employees per company.
3. **Treemap**: Breakdown of companies by industry and revenue contribution.
4. **Map Visualization**: Geographic locations of company headquarters.
5. **Table View**: Detailed overview of all company data, including rank, name, industry, revenue, employees, and headquarters.

---

## Dashboard Slicers

- **Industry**: Filter the companies by industry for a more targeted analysis.

---

## Dashboard Layout

The visualizations are strategically arranged to highlight key insights:

- Emphasis on revenue and employee size through prominent visualizations.
- Geographic context is provided with the map visual, showing the locations of company headquarters.
- Interactive slicers allow users to drill down into the data and explore specific segments.

---

## Tools & Technologies

This project uses the following tools and technologies:

- **Python (for Web Scraping)**: Data was extracted using Python's BeautifulSoup library for parsing HTML and extracting relevant data from online sources.
- **Power BI**: Used for creating interactive visualizations and conducting in-depth data analysis.
- **Power Query Editor**: Employed for data transformation and cleaning before visualization.

---
## Conclusion 
- This project successfully combines web scraping and data visualization to provide meaningful insights into the performance of top U.S. private companies. By utilizing Python and Power BI, this project offers a comprehensive view of key business metrics, such as revenue, employees, and industry segmentation. The interactive dashboard enables users to explore the data through multiple visualizations, offering both high-level trends and detailed company-specific insights.

- This approach can be applied to a variety of data analysis and business intelligence scenarios, helping organizations make data-driven decisions based on actionable insights.

---
## How to Run the Project

### 1. **Web Scraping Script**

To start the project, clone this repository and run the Python script to scrape the data. The script will extract and save the data as a `.csv` or `.xlsx` file. You can modify the script to adjust the target website if necessary.

Once the data is scraped, open the provided Power BI `.pbix` file to view or modify the dashboard.

---

### 2. **Requirements**

To run the web scraping part of this project, you will need the following Python libraries:

- **BeautifulSoup**: For parsing HTML and extracting relevant data.
- **Requests**: For making HTTP requests to the target websites.
- **Pandas**: For data manipulation and cleaning.

You can install the required libraries using:

```bash
pip install beautifulsoup4 requests pandas


BeautifulSoup for parsing HTML
Requests for making HTTP requests
Pandas for data manipulation



