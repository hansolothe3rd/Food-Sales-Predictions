# Food Sales Predictions
## Analyzing Sales Trends and Making Predictions

**Daniel Barella**: 

### Often times in buisness, you are given too much information, or it's scattered and seems unrelated. With the powers of data science, we are able to peer deeper, and see clearer:

### Data Source:
sales_predictions.csv
https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view

## To prepare this data, the data was cleaned, and the following processes were performed:

### Exploratory Data Analysis
    - During the exploratory data analysis, a boxplot and histogram was visualized.
    - Also, a heatmap was produced.
    - This helped visualize what was correlated.
    
 ### Expanatory Data Analysis
    - To visualize the data for explantory purposes, a scatterplot, and a bargraph were created.
    - The bargraph was chosen to show how the Outlet Type is related to the sales.

#### Item Outlet Sales vs. Item MRP
![image](https://user-images.githubusercontent.com/114630422/202842496-085e1ca8-011b-46be-9eb0-6d25795586eb.png)
It seems that as the Item MRP goes up the Item Outlet Sales do as well.  With the Outlet Type as the legend, you can see that Supermarket Type 3 leads the pack with Item Outlet sales.

#### Item Outlet Sales vs. Outlet Type
![image](https://user-images.githubusercontent.com/114630422/202842626-f6e0bbdf-1c4e-4bd5-a3b4-2409e5e78b0b.png)
Having the Outlet Types and the Outlet Location Type seperate but on the same 
graph, we get a real picture of what type of stores and what type of location produces the most sales.

## Maching Learning Using the Following Models:
    - Linear Regression Model
    - Decision Tree Regressor Model
    
## Results

## Linear Regression Model

MAE 804.9409381511028,
 MSE 1194416.6540692842,
 RMSE: 1092.8937066656044,
 R^2: 0.5670799251055714 

## Regression Tree Model

MAE 1044.290584702018,
 MSE 2248752.903184245,
 RMSE: 1499.584243443577,
 R^2: 0.18493243379615865 

## Recommendations:

More Models

## Limitations & Next Steps

Hypertune both models to acheive less error.

### For further information


For any additional questions, 
please contact 
**Daniel Barella**
**hansolothe3rd@hotmail.com**
