# Applied Data Science Capstone Project

## Overview
This capstone project focuses on developing a predictive model for the Falcon 9 first stage landing success. SpaceX has disrupted the space industry by offering Falcon 9 launches at $62 million, a fraction of the traditional $165+ million cost from other providers. This competitive advantage stems primarily from their innovative first stage recovery and reuse capability. Our project aims to create a model that predicts landing success, enabling more accurate launch cost estimations for companies competing with SpaceX in the launch services market.

## Objectives
Our project unfolds across multiple integrated modules, each building upon previous work to create a comprehensive predictive solution. Here's a breakdown of each module's accomplishments:

### 1. Request to the SpaceX API and Data Wrangling
- **Data Collection**: Implemented GET requests to the SpaceX API to obtain comprehensive historical launch data and associated parameters
- **Data Cleaning**: Executed thorough data preprocessing to standardize formats, handle missing values, and prepare the dataset for analysis

### 2. Web Scraping Falcon 9 Launch Records
- **Web Scraping with BeautifulSoup**: Utilized BeautifulSoup to extract detailed Falcon 9 launch records from Wikipedia
- **Data Parsing**: Transformed the scraped HTML content into a structured Pandas DataFrame for further processing

### 3. Exploratory Data Analysis (EDA) and Training Labels
- **Exploratory Data Analysis**: Implemented comprehensive data visualization using Matplotlib and Seaborn to reveal underlying patterns
- **Training Labels**: Developed and applied a systematic labeling approach for the training dataset

### 4. Database Integration
- **Loading Data into Db2**: Successfully integrated the dataset with a Db2 database system
- **Executing SQL Queries**: Developed and implemented strategic SQL queries to extract meaningful insights

### 5. Feature Engineering and Visualization
- **Feature Engineering**: Developed innovative derived features to enhance model performance
- **Visualization with Folium**: Created interactive geographical visualizations highlighting launch sites and success patterns

### 6. Interactive Visual Analytics with Plotly Dash
- **Building the Dash Application**: Engineered an interactive dashboard using Plotly Dash for real-time data exploration
- **User Interaction Components**: Integrated dynamic controls including dropdown menus and range sliders to manipulate visualizations

### 7. Machine Learning Models and Hyperparameter Tuning
- **Data Standardization and Splitting**: Implemented robust data preprocessing and partitioning protocols
- **Hyperparameter Tuning**: Conducted extensive model optimization using GridSearchCV across multiple algorithms
- **Model Evaluation**: Performed comprehensive performance analysis across different machine learning approaches

## Results
- **Decision Tree Classifier**: Demonstrated superior performance with 94.44% accuracy on test data
- **SVM and K-Nearest Neighbors**: Both achieved respectable 83.33% accuracy on test data

## Conclusion
Our analysis successfully delivered a reliable predictive model for Falcon 9 first stage landing outcomes. These predictions provide valuable insights for launch cost estimation and competitive analysis in the space launch market.

## Repository Structure
- **data/**: Houses datasets and data processing utilities
- **notebooks/**: Contains detailed Jupyter notebooks for each project phase
- **scripts/**: Includes all custom Python implementations
- **dash_app/**: Contains the interactive dashboard implementation
- **README.md**: Provides comprehensive project documentation

## Acknowledgments
- **IBM**: Project framework and educational resources
- **Coursera**: Learning platform and course delivery

This repository showcases a complete data science workflow, from initial data collection through model deployment. It serves as a valuable resource for data scientists, space industry analysts, and machine learning practitioners interested in practical applications of predictive modeling.