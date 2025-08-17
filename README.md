# Developer Survey 2024 – Analysis

## Description
This project analyzes developer trends based on the 
[Stack Overflow Developer Survey 2024](https://survey.stackoverflow.co/2024/).  
We focus on three main areas: **Top 10 region,Education, AI, and Work Arrangement**, and their relationship to salary, job satisfaction, and technology preferences.

## Dataset
- Source: Stack Overflow Developer Survey 2024  
- Size: ~65,000 developer responses  
- Format: CSV (stored under `data/raw/`)  

## Analysis

- **Education** : Most developers have a bachelor’s degree, but the most used study resource is still online platforms. Tech preferences vary, and the most commonly used programming language is JavaScript.  

- **AI** : The survey shows that the average salary of non-AI users is higher than AI users. Across countries, the USA has the highest average salary for both groups. There was no significant difference in job satisfaction between AI and non-AI users.  

- **Work Arrangement** : Most survey respondents are hybrid workers, while the least are fully in-person. The USA is the top-paid country across all work arrangements. The survey also showed a clear difference in language and database preferences* between in-person developers and those working hybrid or remote.
  
## Dependencies:
The Python libraries required for this project are:
- pandas → for data manipulation and analysis.
- matplotlib.pyplot → for creating visualizations and plots.
- seaborn → for advanced statistical visualizations.
- re → for working with regular expressions (text cleaning and pattern matching).
- matplotlib.ticker → for customizing ticks and formatting in plots.
  
## How to Run:
- Clone or download this project.
- Open the Jupyter Notebook (.ipynb) file.
- Run the cells step by step.
- Make sure the dataset is placed in the correct directory.
