# Exploratory Data Analysis on the Sample Superstore Dataset

Exploratory Data Analysis (EDA) serves as a foundational step in the data analysis workflow. It involves examining, visualizing, and interpreting datasets to uncover insights, spot trends, and detect irregularities. In this analysis, we will explore the "SampleSuperstore" dataset, which contains information on a fictional retail store's sales and profit performance.

Importing Libraries:  
To begin, we import essential Python libraries such as Pandas for handling data, NumPy for numerical operations, and visualization tools like Matplotlib and Seaborn to create informative plots.

Loading the Dataset:  
We load the "SampleSuperstore.csv" file into a Pandas DataFrame, making it easier to work with and manipulate the dataset.

Initial Data Exploration:  
Using functions like `head()`, `info()`, and `describe()`, we take a closer look at the dataset’s structure, including data types, non-null values, and summary statistics for numerical fields.

Handling Missing and Duplicate Values:  
We check for missing data using `isnull().sum()` and identify duplicates with `duplicated().sum()`. Addressing these issues ensures data quality and improves the reliability of the analysis.

Data Visualization:
Visualization helps us better understand data distributions and relationships. We create various plots such as bar charts, scatter plots, and histograms to explore metrics like regional sales performance and the link between sales and profit.

Correlation Analysis:  
To explore the relationships between numerical features, we generate a correlation matrix and use a heatmap to visualize how variables like sales and profit are interrelated.
