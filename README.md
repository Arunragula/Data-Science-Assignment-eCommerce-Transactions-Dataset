# Data-Science-Assignment-eCommerce-Transactions-Dataset

 
## Overview
 
This is a customer-behavior and product-based analysis, designed to look at patterns and understand insights. The components of the project include EDA, Clustering, and building a Lookalike Model. The goal would be to identify similar customers and similar products in terms of customer preference and group them up for focused action.
 
---
 
## Files

1. **Arun_Ragula_Clustering.ipynb**  This Jupyter notebook performs clustering algorithms that group customers according to their purchasing patterns. It makes use of techniques like K-Means clustering or hierarchical clustering to identify different customer segments.

2. **Arun_Ragula_Clustering.pdf**  PDF version of the clustering analysis notebook, which provides insights and visualizations of the clustering results.

3. **Arun_Ragula_EDA.ipynb**
This is a Jupyter notebook performing EDA on customer, product, and transaction data. It will initially explore the data, clean it, and then provide some visualization for the understanding of trends and patterns in the data.

4. **Arun_Ragula_EDA.pdf** 
   PDF version of the EDA notebook having findings and visual representations during the phase of exploratory data exploration.

5. **Arun_Ragula_Lookalike.csv**
A CSV file containing lookalike customer data. The data set could be further used for analysis on similar customers based on their behavior and demographics.

6. **Arun_Ragula_Lookalike.ipynb**   Jupyter notebook for analyzing the Lookalike customer data. It contains feature engineering, model building, and evaluation to identify similar customers.

7. **Customers.csv**
A CSV file containing customer data, including demographic information and transaction history. This data is crucial for clustering and segmentation analysis.

8. **Products.csv**  A CSV file containing product data, including product categories, prices, and other features. It is used for clustering analysis and understanding product preferences.

9. **Transactions.csv**
A CSV file with transaction records, linking customers to the products they have purchased. This data is key for clustering and identifying purchasing patterns.

---

## Installation

1. Clone this repository to your local machine.
   
   ```bash
   git clone <repository-url>
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter notebooks:

`bash
   jupyter notebook
   
-----------------------------------

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

-----------------------------------

## Analysis Flow

1. **EDA (Exploratory Data Analysis)**  
   In the `Arun_Ragula_EDA.ipynb`, we firstly load and clean the data, handle missing values, and visualize distributions and relationships between customer behavior, demographics, and product preferences.

2. **Clustering
In the `Arun_Ragula_Clustering.ipynb` we use clustering algorithms to cluster customers based on demographics and purchasing patterns. These clusters proved useful for delineating specific groupings of customer segments that can be targeted through specific strategies in marketing.

3. **Lookalike Model
The `Arun_Ragula_Lookalike.ipynb` performs analysis on the ability to identify lookalike customers. This model uses historical transaction data and customer features to predict which new customers would behave like existing ones.

---

## How to Use

1. Review `Arun_Ragula_Clustering.ipynb` for clustering results and visualizations.
2. Run `Arun_Ragula_EDA.ipynb` to explore the data.
3. Review `Arun_Ragula_Lookalike.ipynb` for similar customers.
4. To make other explorations, include `Customers.csv`, `Products.csv`, and `Transactions.csv`.

---

