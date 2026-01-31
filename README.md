# food_delivery_data_merge
This project focus on merging separate datasets with different extensions into a single file by using LEFT JOIN. 
The dataset contains three files 
1. orders.csv
2. users.json
3. restaurants.sql
   The primary goal of this analysis is to create a unified view of the food delivery ecosystem. By merging user demographics with transactional data, the notebook explores revenue distribution, membership impact, and geographical performance.
#food_delivery_data_merge.ipynb: The core Python (Pandas) notebook containing the data cleaning, merging logic, and exploratory data analysis (EDA).
#Key Analysis Features
The notebook performs several critical data operations:

Data Merging: Connecting user_id across different tables to link names and cities with order values.

Membership Segmentation: Analyzing the difference in order frequency and value between Gold and Regular members.

City-wise Performance:

Revenue Leaders: Currently identifies Bangalore and Pune as high-revenue hubs.

Customer Density: Tracking the number of active users per city (e.g., specific counts for Gold members in Chennai).

Financial Metrics: Summing total sales and calculating average order values per segment.

#Tech Stack
Python 3

Pandas: For data manipulation and merging.

Jupyter/Google Colab: Environment for interactive analysis.

3How to Use
Ensure you have the source CSV/Excel files (Users, Orders, etc.) in the same directory as the notebook.

Run the cells sequentially to perform the inner/outer joins.

Refer to the final final_df variable for the consolidated dataset.
