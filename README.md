# Web Scrapping - Real-Estate-Data-Analysis-with-Rentberry.com
This project focuses on developing a comprehensive pipeline for web scraping, data analysis, and machine learning to derive insights and make predictions about real estate rental properties. The project is structured into four distinct phases, each contributing to a robust solution for analyzing rental data from multiple cities worldwide

### Learning Outcomes
Through this project, I developed key skills in cloud and enterprise development, web services, and machine learning, addressing the following learning outcomes:

#### Create Scalable Data Solutions
Built a scalable pipeline using web scraping techniques to collect large volumes of real estate data from Rentberry and other real estate platforms. This data was processed and analyzed to extract valuable insights.

#### Critical Evaluation of Tools and Services
Evaluated various tools and libraries such as Pandas, BeautifulSoup, and Scikit-learn to ensure efficient data handling, analysis, and model training.

#### Develop Distributed Applications
Implemented data integration using SQL and Pandas, enabling seamless interaction between different data sources in a distributed environment.

#### Apply Machine Learning for Predictions
Built and trained machine learning models to predict rental prices and property area, optimizing model performance through hyperparameter tuning and avoiding overfitting.

#### Implement Design Patterns
Applied design patterns for scalability and maintainability, ensuring the system can handle diverse data inputs and large datasets efficiently.

## Project Phases
####  Phase 1: Web Scraping
Scraped rental property data from Rentberry.com and additional real estate platforms.
Extracted key features: city, rental price, deposit, number of rooms, and amenities.
Converted all rental prices to INR using predefined conversion rates.
Tools Used: BeautifulSoup, Requests, Pandas

#### Phase 2: SQL Queries
Stored data in three structured CSV files.
Wrote 15 standalone and 7 join SQL queries to analyze the data. Queries included:
Calculating average rental prices.
Identifying top deposits by city.
Retrieving records with specific amenities.
Tools Used: Oracle SQL, Pandas (for CSV generation)

#### Phase 3: Exploratory Data Analysis (EDA)
Merged the three datasets into a single DataFrame.
Conducted a detailed Exploratory Data Analysis to uncover trends and patterns.
Visualized data insights using Matplotlib and Seaborn.
Key Insights:

Identified cities with the highest rental prices.
Analyzed the distribution of amenities across properties.
Highlighted correlations between rental prices, property size, and amenities.
Tools Used: Pandas, Matplotlib, Seaborn

#### Phase 4: Machine Learning
Developed predictive models for:
Rental Price prediction.
Property Area prediction.
Applied Linear Regression, Random Forest, and XGBoost, selecting the best model based on performance metrics.
Optimized models using scaling techniques and hyperparameter tuning.
Tools Used: Scikit-learn, XGBoost

#### Key Features
Scalable Web Scraping: Efficiently scraped and standardized data across multiple real estate platforms.
Data Integration and Querying: Integrated structured datasets using SQL and analyzed them with advanced queries.
Data Visualization: Used graphical representations to gain deeper insights into rental property trends.
Predictive Modeling: Built machine learning models to forecast rental prices and property sizes with high accuracy.

#### Technologies Used
**Web Scraping:**
Selenium: Automated data scraping from dynamic web pages.
BeautifulSoup: Parsed and extracted data from static web content.
pprint: For clean and structured data representation.
time & os: Managed system-level operations and task scheduling during scraping.
Programming Languages: Python

**Data Storage and Querying:**
SQL for querying and data integration.
Pandas for data manipulation.

**Machine Learning:**
Scikit-learn and XGBoost for building and optimizing predictive models.
