Iris Dataset Exploratory Data Analysis (EDA)
🎯 Task Objective
The primary objective of this project is to perform a comprehensive Exploratory Data Analysis (EDA) on the Iris dataset. This involves loading the data, performing statistical inspections, and using various visualization techniques to uncover patterns, trends, and distributions among different iris species.

📊 Dataset Overview
The Iris Dataset is a multi-variate dataset famously used in machine learning. It contains 150 samples from three species of Iris flowers (Iris setosa, Iris virginica, and Iris versicolor).

Features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Species (Target Label)

🛠️ Implementation Steps
1. Data Inspection
Pandas Integration: Loaded the dataset to inspect the structure using .shape and .columns.

Summary Statistics: Utilized .info() to check for missing values and data types, and .describe() to calculate the mean, standard deviation, and quartiles for each feature.

2. Data Visualization
To understand the data distribution and feature relationships, I implemented the following plots:

Scatter Plots: To visualize the relationship between variables (e.g., Petal Length vs. Petal Width). This helps identify clusters where species separate naturally.

Histograms: To observe the frequency distribution of individual features and check for normality.

Box Plots: To detect outliers and compare the range/median of features across the three species.

🚀 Key Findings
Species Separation: Petal length and width are the most significant indicators for distinguishing between species, with Iris setosa being easily separable from the others.

Data Quality: The dataset is highly clean with no missing values, making it ideal for baseline statistical modeling.

Outliers: Box plots revealed minimal outliers in sepal width, suggesting a very consistent data collection process.
