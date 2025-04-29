# Scrape-to-Store
Project Details
Data Extraction
Objective: Identify the target website and extract relevant data.
Process: Using web scraping techniques, data such as book titles, prices, ratings, availability, and links were collected.

Output: Raw data stored in a structured CSV file for further analysis.

Data Cleaning, Processing, and Regular Expressions
Objective: Clean the extracted data and process textual information using Regular Expressions.

Process:

Removed unnecessary or incorrect values from the dataset.

Applied Regular Expressions (Regex) to process and clean text fields (e.g., extracting meaningful data such as prices, dates, or product descriptions).

Data Analysis
Objective: Compute basic statistics and identify patterns.

Process:

Basic statistics, such as the average price and ratings, were computed.

Identified relationships between variables like price vs. rating, rating distribution, etc.

Data Visualization
Objective: Present findings using visualizations.
Process:
Created graphs and charts to present data clearly, including bar charts, line graphs, and heatmaps.

Visualized the data in an interactive manner using Python libraries such as Matplotlib and Seaborn.

Data Storage
Objective: Store processed data for future use.

Process:

The final processed data was stored in a  sqllite database for efficient querying and usage

Interactive Web App:

The project was further enhanced by deploying the results using Streamlit, creating an interactive web app that allows users to explore and visualize the data dynamically.

Technologies Used
Python: The main programming language used for the entire project.

Libraries:

BeautifulSoup / Selenium for web scraping.

Pandas for data manipulation.

Matplotlib / Seaborn for data visualization.

Regular Expressions (Regex) for text processing.

sqllite for storing processed data.

Streamlit for building the interactive web app.
