# Big-Data-ETL-
This is Kokila's Big Data ETL Project
## Part 1
* Uploaded the part_one_starter_code.ipynb into Google Colab and create a duplicate of this file.
* Explored the Amazon ReviewsLinks to an external site. datasets and picked two datasets to perform ETLand they are Sports.tsv and Toys.tsv files.

## Extract the Data
* Read in each dataset using the correct header and sep parameters.
* Get the number of rows in the dataset.

## Transform the Data
* For each dataset use the schema.sql file located in the Resources folder of the Starter_Code.zip file to create the four DataFrames as follows:
* Create the "review_id_df" DataFrame with the appropriate columns and data types.
* Create the "products_df" DataFrame that drops the duplicates in the "product_id" and "product_title columns.
* Create the "customers_df" DataFrame that groups the data on the "customer_id" by the number of times a customer reviewed a product.
* Create the "vine_df" DataFrame that has the "review_id", "star_rating", "helpful_votes", "total_votes", and "vine" columns.

## Load the Data into an RDS Instance
* Export each DataFrame into the RDS instance to create four tables for each dataset.