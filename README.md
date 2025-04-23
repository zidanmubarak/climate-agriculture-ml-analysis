# Machine Learning Project: Climate Change Impact on Agriculture

This repository contains the final submission project for the Dicoding Machine Learning for Beginners class, sponsored by DBS Foundation. The project explores the impact of climate change on agriculture using machine learning techniques for both clustering and classification.

## Project Overview

In this project, I applied machine learning techniques to analyze climate change effects on agricultural data. The project consists of two main components:

1. **Clustering Analysis**: Identifying natural groupings in agricultural climate data to reveal patterns and relationships.
2. **Classification Analysis**: Predicting specific agricultural outcomes based on climate variables.

## Dataset

The project uses the [Climate Change Impact on Agriculture](https://www.kaggle.com/datasets/waqi786/climate-change-impact-on-agriculture) dataset from Kaggle, which contains various climate and agricultural metrics across different regions and time periods.

## Repository Structure

```
├── climate_change_impact_on_agriculture_2024.csv    # Dataset for clustering analysis
├── climate_agriculture_clustered_optimized.csv      # Dataset for classification analysis
├── [Clustering]_Submission_Akhir.ipynb              # Python notebook with clustering implementation
├── [Klasifikasi]_Submission_Akhir.ipynb             # Python notebook with classification implementation
├── README.md                                        # Project documentation
├── requirements.txt                                 # Required Python packages
```

## Implementation Details

### Clustering Analysis
- Implemented unsupervised learning to identify natural patterns in climate-agriculture data
- Applied data preprocessing, feature scaling, and dimensionality reduction
- Used **K-Means clustering algorithm** to group similar data points
- Performed feature engineering to improve the Silhouette Score
- Created detailed visualizations of cluster distributions
- Provided comprehensive interpretation of each identified cluster

### Classification Analysis
- Used the clustering results as the basis for classification models
- Implemented **Random Forest** and **Gradient Boosting** classifiers
- Performed hyperparameter tuning on the Gradient Boosting model to optimize performance
- Compared model performance metrics including accuracy, precision, recall, and F1-score
- Created confusion matrices to visualize classification results

## Installation and Usage

1. Clone this repository:
```bash
git clone https://github.com/zidanmubarak/climate-agriculture-ml-analysis.git
cd climate-agriculture-ml-analysis
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Open and run the notebook files in VSCode:
```bash
code .
```

## Technologies Used

- Python 3.x
- Pandas for data manipulation
- Scikit-learn for machine learning algorithms
- Matplotlib and Seaborn for data visualization
- Visual Studio Code (VSCode) as the development environment

## Connect with Me

Feel free to connect with me on LinkedIn to discuss this project or other data science topics:
[My LinkedIn Profile](https://www.linkedin.com/in/zidan-mubarak-87b880283/)

I'm always open to feedback, collaboration opportunities, or just chatting about machine learning and data science!
