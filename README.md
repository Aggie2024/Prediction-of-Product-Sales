# Prediction-of-Product-Sales
This project will be a sales prediction for food items sold at various stores. The goal is to propose a model to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.

First we load the data in our colab notebook. We explore and clean the data before it is ready for analysis. 

### Data Dictionary
| Variable Name  | Description |
| ------------- | ------------- |
| Item_Identifier  | Product ID  |
| Item_Weight  | Weight of product  |
| Item_Fat_Content  | Whether the product is low-fat or regular  |
| Item_Visibility  | The percentage of total display area of all products in a store allocated to the particular product |
| Item_Type  | The category to which the product belongs  |
| Item_MRP  | Maximum Retail Price (list price) of the product  |
| Outlet_Identifier  | Store ID  |
| Outlet_Establishment_Year  | The year in which store was established  |
| Outlet_Size  | The size of the store in terms of ground area covered  |
| Outlet_Location_Type | The type of area in which the store is located  |
| Outlet_Type | Whether the outlet is a grocery store or some sort of supermarket  |
| Item_Outlet_Sales  | Sales of the product in the particular store. This is the target variable to be predicted.  |

Exploring the data showed several inconsistencies and errors that need to be cleaned

### Data Cleaning
- Observing the data: number of rows and columns, data types of the variables
- Checking for duplicates.
- Identifying missing values, addressing these with a placeholder value.
- Finding and fixing inconsistent categories of data (for example: Y, y, Yes, YES so that they are consistent).
- Summary statistics of numeric variables (min, max, mean).

### Exploratory Visualisation using both univariate and multivariate plots
- Histograms to view the distributions of numerical features in your dataset.
- Boxplots to view statistical summaries of numerical features in your dataset.
- Countplots to view the frequency of each class of categorial features in your dataset.
- Heatmap to view the correlation between features.
- Regression to explore the variables with some correlation.

