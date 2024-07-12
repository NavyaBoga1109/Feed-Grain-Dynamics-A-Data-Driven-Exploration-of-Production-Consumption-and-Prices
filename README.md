# Feed-Grain-Dynamics-A-Data-Driven-Exploration-of-Production-Consumption-and-Prices

## Introduction
Our project embarks on a journey to explore historical trends, regional variations, and influencing factors that shape the dynamics of feed grain. We aim to address questions pertaining to market trends, regional disparities, and the impact of external factors on production and prices.

Feed grains constitute a fundamental element in the global food ecosystem, playing a critical role in sustaining livestock and influencing various agricultural sectors. The volatility and interconnectedness of feed grain production, consumption, and pricing necessitate a comprehensive and data-driven approach to unravel the underlying patterns and trends.
![image](https://github.com/user-attachments/assets/c9a88fe0-abc5-4e98-b254-e591392d057c)

Understanding the feed grain landscape is pertinent to the agricultural sector and extends its implications to broader economic aspects. Our exploration goes beyond mere statistical analysis; it seeks to uncover insights that can aid in anticipating trends and adapting to changing circumstances.

## Project Structure
- **notebooks**: Jupyter notebooks for data analysis and visualization.
    - These notebooks document the step-by-step analysis process, including data exploration, visualization, and modeling. They provide a narrative and visual representation of the analysis.

- **src**: Source code for data preprocessing, EDA, feature engineering, and modeling.
    - `data_preprocessing.py`: Scripts for cleaning and preprocessing the raw data.
    - `eda.py`: Scripts for performing exploratory data analysis to understand the data's structure and relationships.
    - `feature_engineering.py`: Scripts for creating and selecting features that will be used in modeling.
    - `modeling.py`: Scripts for building, training, and evaluating predictive models.

- **README.md**: Project introduction and instructions.
    - This file provides an overview of the project, including its purpose, structure, and how to use the repository.

- **requirements.txt**: List of dependencies required to run the project.
    - This file lists all the Python packages and libraries needed to run the scripts and notebooks in the repository.


## Data Cleaning
In this section, we detail the steps taken to clean and preprocess the data. This includes handling missing values, correcting inconsistencies, standardizing formats, and scaling numerical data.

1. **Overview of Dataset**:
    - Total Entries: 497,473
    - Total Columns: 19
    - Data Types: Integer, Float, String

2. **Initial Data Assessment**: Examined the dataset for structure, types, and range of values.

3. **Cleaning Steps**:
    - Missing Values: Checked for any missing data in key columns and removed or imputed as necessary.
    - Data Consistency: Ensured uniformity in categorical data through standardization and correction of typos.
    - Data Transformation: Scaled numerical data for analysis using normalization or standardization.
    - Handling Outliers: Identified and assessed outliers in quantitative fields and took appropriate actions such as removal or capping.
    - Data Reduction: Reduced dataset dimensions for focused analysis, considering the top 10 columns.

## Data Visualization
This section showcases various visualizations created to explore and understand the data better. It includes bar charts, line graphs, dot plots, histograms, grouped bar charts, scatter plots, and more.
![image](https://github.com/user-attachments/assets/15ee28e7-d176-40e4-a239-a5c5b5de2008)

- Visualizations illustrate trends, distributions, and relationships within the data.
- Key insights are derived from these visualizations to guide further analysis.
![feed_grain_animation](https://github.com/user-attachments/assets/ee0ddc00-bdbc-4384-92e4-1d44ba0117c3)

## Data Clustering
Here we perform clustering analysis to identify patterns and group similar data points. This section includes:

- **Hierarchical Clustering**: Using dendrograms to visualize clusters and their relationships.
- **Elbow Method**: Determining the optimal number of clusters by analyzing within-cluster variance.
- **DBSCAN Clustering**: Density-based clustering to identify distinct clusters based on production and consumption values.
- **Treemap Analysis**: Visualizing the importance of different grain types and sub-products within the dataset.
![image](https://github.com/user-attachments/assets/6e037445-05d1-4ab8-87c0-b31ed15a3ea2)

## Predictive Modeling
This section covers the development and evaluation of predictive models to forecast future trends in feed grain production and consumption.

- **Model Selection**: Choosing appropriate models such as decision trees, clustering algorithms, and regression models based on project goals.
- **Model Training**: Training the selected models using the training dataset.
- **Model Evaluation**: Assessing model performance using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and silhouette scores.
![image](https://github.com/user-attachments/assets/e4d17142-3959-436f-845b-f8f5776ded62)

## Conclusion
The conclusion summarizes the key findings and insights from the project. It highlights the importance of understanding feed grain dynamics and how the analysis can aid stakeholders in making informed decisions.

- Emphasis on the roles played by each team member.
- Overview of the tools and techniques used, particularly the use of R programming for its data analysis capabilities.
- Assessment of model performance and suggestions for further improvements.

