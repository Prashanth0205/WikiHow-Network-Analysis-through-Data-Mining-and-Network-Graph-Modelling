# WikiHow Network Analysis through Data Mining and Network Graph Modelling

This segment focuses on the preliminary stage of the project, which involves the extraction of valuable information from WikiHow pages through web scraping techniques. The primary objective is to gather comprehensive data about various articles, including their main headings, subheadings, categories, ratings, views, and other pertinent details. By utilizing libraries such as BeautifulSoup and requests in Python, the code accesses and parses the HTML content of WikiHow pages, extracting the desired information. Once extracted, the data is structured and cleaned to ensure consistency and reliability. This phase serves as the foundation for subsequent analysis, providing a rich dataset that captures the breadth and depth of content available on WikiHow.

## Part 1: Data Mining and Processing

1. Web Scraping: Utilization of Python libraries like BeautifulSoup and requests for fetching and parsing HTML data from WikiHow pages.
2. Data Extraction: Extraction of relevant information such as main headings, sub-headings, categories, co-authors, views, etc., from the parsed HTML content.
3. Cleaning and Preprocessing: Removal of unwanted HTML tags, formatting inconsistencies, and noise from the extracted data to ensure consistency and accuracy.
4. Structuring Data: Organizing the extracted information into a structured format such as a pandas DataFrame for easy manipulation and analysis.
5. Handling Unwanted URLs: Filtering out unwanted URLs and irrelevant data to focus only on WikiHow articles related to the specified categories.
6. Batch Processing: Iterative processing of multiple WikiHow pages to accumulate a comprehensive dataset for analysis.
7. Data Storage: Saving the cleaned and structured data into a CSV file for further analysis and visualization.

Code for [Data Mining](Webscrapping_wikihow_new.ipynb) and [Data Cleaning](cleaning_wikiHow_data.ipynb) 

## Part 2: Graph Construction and Analysis

1. Network Graph Creation: Creation of a NetworkX graph to represent the relationships between main headings and their corresponding categories/sub-categories extracted from WikiHow articles.
2. Node and Edge Addition: Addition of nodes representing main headings and categories/sub-categories to the graph, with edges connecting them to depict their relationships.
3. Visualization: Visualization of the network graph using Matplotlib to provide a visual representation of the connections between main headings and categories/sub-categories.
4. Graph Metrics Calculation: Calculation of various graph metrics such as degree distribution, average degree, PageRank, diameter, and centrality measures (closeness and betweenness centrality).
5. Statistical Analysis: Statistical analysis of graph metrics to gain insights into the structure and characteristics of the WikiHow network.
6. Visualization Enhancement: Enhancement of visualizations with additional features such as highlighting major nodes, plotting histograms for centrality measures, and displaying top PageRank values.
7. Insight Generation: Generation of insights from the analyzed graph metrics to understand the importance and centrality of different categories/sub-categories within the WikiHow network.
8. Presentation of Results: Presentation of results through descriptive statistics, visualizations, and key findings to facilitate interpretation and understanding of the WikiHow network structure.

Code for [Network Visualization and Analysis](Network graph.ipynb)
