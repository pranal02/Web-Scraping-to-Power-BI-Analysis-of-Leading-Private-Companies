# Web-Scraping-to-Power-BI-Analysis-of-Leading-Private-Companies
# Web-Scraped Insights: Visualizing Top U.S. Private Companies

This project involves web scraping data on the top private companies in the U.S., followed by visualizing the extracted data in Power BI. The dashboard provides insights into the revenue, industry, employees, and headquarters of these companies.

## Project Overview

The dataset is web-scraped and processed to create an interactive Power BI dashboard for analysis. The dashboard allows users to explore key metrics, such as:   

- Revenue (in USD billions)
- Number of employees
- Industry classification
- Headquarters location

### Data Source

The data was extracted using web scraping techniques from publicly available online sources, gathering information on the following attributes:

- **Rank**
- **Company Name**
- **Industry**
- **Revenue (USD billions)**
- **Employees**
- **Headquarters Location**

## Dashboard Features

The Power BI dashboard includes the following visualizations:

1. **Bar Chart**: Top companies ranked by revenue.
2. **Bar Chart**: Number of employees per company.
3. **Treemap**: Breakdown of companies by industry and revenue contribution.
4. **Map Visualization**: Geographic location of company headquarters.
5. **Table View**: Detailed overview of all company data, including rank, name, industry, revenue, employees, and headquarters.

### Dashboard Slicers

- **Industry**: Filter the companies by industry.


### Dashboard Layout

- The visualizations are arranged to highlight key insights, with interactive slicers to enable a deeper analysis of the data.
- The layout emphasizes revenue and employee size while providing geographic context with the map visual.

## Tools & Technologies

- **Python (for Web Scraping)**: Data was extracted using Python's BeautifulSoup library for parsing HTML and extracting relevant data points from web sources.
- **Power BI**: Used for creating the interactive visualizations and analyzing the data.
- **Power Query Editor**: Employed for any necessary data transformation and cleaning before visualizing.

## How to Run the Project

**Web Scraping Script**: Clone this repository and run the Python script to scrape and extract the dataset. You can modify the script to adjust the target website.
The script will generate a .csv or .xlsx file containing the extracted data.
Open the Power BI .pbix file to view or modify the dashboard.

To run the web scraping part of this project, you’ll need the following Python libraries:

BeautifulSoup for parsing HTML
Requests for making HTTP requests
Pandas for data manipulation



