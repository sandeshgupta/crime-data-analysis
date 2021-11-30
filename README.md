# Chicago Crime Data Analysis 

# Project description

This project is aimed at performing an analysis of the crime of the past 20 years in the city of Chicago. Our goal is to mine the underlying hidden patterns, similarities and find relationships between the factors involved in the crime.

# Dataset

[Crimes - 2001 to Present | City of Chicago | Data Portal](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/data)

Number of records: 7,424,694
Number of attributes: 22 

# How to run the notebook

1. Clone the repository to local folder
2. For association analysis:
   - Open Jupyter Notebook
   - Navigate to the local folder
   - Open the file `Apriori - 2021 data .ipynb`
   - Run all the cells of Notebook
3. For association analysis: (Pre and Post Covid data)
   - Open Jupyter Notebook
   - Navigate to the local folder
   - Open the file `Pre-covid.ipynb` / `Post-covid.ipynb`
   - Run all the cells of Notebook

# Proposed methodology

## Preprocessing

Format CSV file (Eg: Replace commas in the multi-valued attributes to some other delimiter)
Handle missing data
Dimensionality reduction

## Techniques/Analysis

### Association Rule Learning

Association rule learning is used to find the relationship between different attributes in a dataset. For example, market basket analysis to find products that are bought together during a shopping trip. We plan to use this to identify the relationship between different attributes of the crime. For example: how does type of crime and location relate in an occurrence of a crime. Apriori and FP-growth algorithms are some of the popular algorithms to conduct this type of analysis. 

### Clustering
We plan to use this method to determine patterns in the crime occurring in Chicago based on the locations, the time and type of crimes, and the time of year. 
Which types of crimes occur in which areas of the city
Which types of crimes occur in which areas of the city at specific times of the day
What type of crimes occur in the city during certain times of the year

Evaluation Metrics: SSE, BSS, WSS 
