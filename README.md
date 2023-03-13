# Unsupervised-Machine-Learning

## Overview

![alt text](https://github.com/yasmina-99/Unsupervised-Machine-Learning/blob/main/6FDBF20F-FB04-4035-B3CA-A4F50C905FF1_1_201_a.jpeg)

This project is an application of Ubsupervised Machine Learning project using Principal Component Analysis (PCA) on the "Countries of the World" dataset. The dataset contains information on 227 countries, including their region, population, area size, GDP, mortality, and more.

## Data Card
`Context:` World fact sheet, fun to link with other datasets.
`Content:` Information on population, region, area size, infant mortality and more.
`Acknowledgements:` Data compiled from US Government; Source: The World Factbook (public domain)
`Inspiration:` When making visualisations related to countries, sometimes it is interesting to group them by attributes such as region, or weigh their importance by population, GDP or other variables.
Social Science: `Categorical`
Global Usability: 8.24
License: CC0: Public Domain
Expected update frequency: Not specified
File: `countries of the world.csv` (38.3 kB)
Number of columns: 20
`About the Code`
The code for this project is written in Python and is available in the pca_countries.ipynb notebook. It uses the following libraries:

- pandas
- seaborn
- matplotlib
- sklearn
- Principal Components

The code performs the following tasks:

*Load the dataset and perform exploratory data analysis (EDA)
*Preprocess and clean the data (handle missing values, normalize data)
*Preliminary Exploratory Data Analysis of the dataset
*Perform PCA and visualize the results
*Interpret the principal components and their contributions to the variance
*The code is documented and should be easy to follow even for beginners.

## Discussion
The PCA results show that the first two principal components explain around 70% of the variance in the data. The first principal component is strongly correlated with GDP, while the second principal component is strongly correlated with population. This suggests that these two factors are the main drivers of the differences between countries.

The visualization of the principal components shows how countries are clustered based on their attributes. Countries with similar attributes are closer together, while countries with dissimilar attributes are farther apart. This can be useful for identifying patterns and relationships in the data.

## About the Dataset
The "Countries of the World" dataset contains information on 227 countries, including their region, population, area size, GDP, mortality, and more. The data is compiled from the US Government and is available in the public domain.

The dataset is useful for exploring the relationships between different country attributes and for visualizing patterns and trends in the data. It can also be combined with other datasets to perform more complex analyses.

## License
This project and the "Countries of the World" dataset are released under the CC0: Public Domain license. This means that they can be used, modified, and distributed without any restrictions or permissions required.



