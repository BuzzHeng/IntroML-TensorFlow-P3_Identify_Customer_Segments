# Identify Customer Segments

## Project Overview

This project focuses on identifying customer segments for a mail-order company using demographic data from Germany. The analysis involves cleaning the data, reducing its dimensionality, and applying clustering methods to group customers into distinct segments. By comparing the demographics of the general population with the customer base, actionable insights into target audiences and potential markets are uncovered.

## Steps Involved

### 1. Preprocessing
- Handled missing or unknown values.
- Removed features and data points with excessive missing data.
- Re-encoded features based on their measurement levels.
- Cleaned both general demographic and customer datasets systematically.

### 2. Feature Transformation
- Scaled features for uniformity.
- Applied Principal Component Analysis (PCA) to reduce dimensionality.
- Selected components explaining the most variability for analysis.

### 3. Clustering
- Used k-means clustering to segment demographic data.
- Applied the same transformations to customer data.
- Compared demographic and customer clusters to identify key market segments.

## What I Learned and Applied

### Key Skills
- Data cleaning and handling missing values.
- Encoding and preparing features for analysis.
- Applying PCA for dimensionality reduction.
- Using k-means clustering for segmentation.

### Tools and Libraries
- **Python**: Core programming language.
- **pandas**, **NumPy**: For data manipulation and computations.
- **scikit-learn**: For PCA, scaling, and clustering.
- **Matplotlib**, **Seaborn**: For visualization.

## Key Takeaways

This project provided hands-on experience in customer segmentation, data preprocessing, and machine learning techniques. It strengthened my ability to analyze real-world data and derive insights relevant to business needs.

## Data Propriety

The data used in this project is proprietary and provided by Arvato Bertelsmann. It includes sensitive demographic and customer information, which must be handled and stored securely. All analysis was conducted under the terms of use specified by Udacity and Arvato, and the data was deleted upon project completion as per the agreement.

## Course Information

This project was completed as part of Udacity's "Intro to Machine Learning with TensorFlow Nanodegree Program." It showcases practical applications of data science techniques to solve real-world business problems.
