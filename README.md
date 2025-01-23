# Home Sales Analysis with PySpark
## Overview
This project analyzes home sales data using PySpark in a Google Colab environment. The goal is to perform data processing, caching, partitioning, and querying to derive insights from the dataset.

## Dataset

The dataset used in this project is home_sales_revised.csv, which is retrieved from an AWS S3 bucket.
Columns in the dataset:id: Unique identifier for each sale
- date: Sale date
- price: Sale price of the home
- bedrooms: Number of bedrooms
- bathrooms: Number of bathrooms
- sqft_living: Size of the home in square feet
- sqft_lot: Lot size in square feet
- floors: Number of floors
- waterfront: Indicates if the property has a waterfront
- view: Rating of the home's view
- date_built: Year the home was built


## Conclusion

This project demonstrated how to analyze home sales data using PySpark SQL, leveraging caching and partitioning to optimize query performance.
How to Run the NotebookTo run the notebook, install the necessary dependencies in Google Colab, upload the notebook, and execute the cells sequentially.
