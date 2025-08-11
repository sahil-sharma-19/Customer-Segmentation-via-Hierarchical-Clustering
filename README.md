# Customer-Segmentation-via-Hierarchical-Clustering
Hierarchical Clustering Analysis groups customers based on annual income and spending score using dendrograms and agglomerative clustering. The project includes data exploration, visualization, and Python implementation, helping identify customer segments for targeted marketing and business insights.

## Technologies Used

- **Python**: Core programming language used for data analysis and modeling.
- **Pandas**: Data manipulation and preprocessing.
- **NumPy**: Numerical computations.
- **Matplotlib**: Data visualization (dendrograms, scatter plots).
- **SciPy**: Hierarchical clustering and dendrogram generation.
- **scikit-learn**: Agglomerative clustering for segmenting customers.

## Data Source Information

- The dataset consists of 200 customer records from a mall’s customer database.
- Each record includes: CustomerID, Genre, Age, Annual Income (k$), and Spending Score (1-100).
- Data is used to segment customers based on spending behavior and income for targeted marketing.
- Original data file: `data/customers.csv`

### Sample Data Preview

| CustomerID | Genre  | Age | Annual Income (k$) | Spending Score (1-100) |
|------------|--------|-----|--------------------|------------------------|
| 1          | Male   | 19  | 15                 | 39                     |
| 2          | Male   | 21  | 15                 | 81                     |
| 3          | Female | 20  | 16                 | 6                      |
| ...        | ...    | ... | ...                | ...                    |
| 200        | Male   | 30  | 137                | 83                     |

## Features & Highlights

- **Customer Segmentation**: Groups customers based on Annual Income and Spending Score.
- **Hierarchical Clustering**: Uses agglomerative clustering with Ward linkage for precise grouping.
- **Dendrogram Visualization**: Helps determine the optimal number of clusters.
- **Data Exploration**: Clear inspection and understanding of dataset features.
- **Clean Code & Organization**: Well-structured project with separate folders for data, code, and notebooks.
- **Interactive Notebook**: Step-by-step Jupyter Notebook for hands-on analysis.
- **Python-based Implementation**: Built using Pandas, NumPy, Matplotlib, SciPy, and scikit-learn.
- **Scalable Approach**: Can be extended with more features or different clustering methods.

  ## Impacts & Insights

- **Customer Behavior Understanding:** Identifies distinct customer groups based on spending and income patterns, enabling targeted marketing.
- **Business Strategy Optimization:** Helps tailor promotions, product offerings, and services to specific customer segments.
- **Data-Driven Decisions:** Supports segmentation-driven decisions that improve customer satisfaction and retention.
- **Visual Exploration:** Dendrogram and cluster plots make complex relationships easier to interpret.
- **Scalable Framework:** Approach can be expanded to include more features or other clustering algorithms for deeper insights.

  
  
