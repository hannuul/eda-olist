# Wrangling & Viz: Best-Selling Product Analysis
Full-Report on https://medium.com/@rjannahwork/exploring-e-commerce-data-8610074ad9bb

# Objectives
It will start by looking for the product category with the highest sales. Once we get it, I want to see the characteristic of products selling well in that category. The plan was to find the best formulation for a product in the category identified as the best seller by browsing through all the data.
- What is the Best-Selling Product Category?
- What is the price range for “cama_mesa_banho” products that sell?
- Are there specific characteristics of “casa_mesa_banho” products that correlate with the selling price?
- What are the characteristics of the best-selling products of “casa_mesa_banho” category?

# Data Overview
![image](https://user-images.githubusercontent.com/96038150/205501448-ee329b49-b74a-417d-8224-73bc2da3e208.png)

The database given contains data on sellers, products, customers, orders, payments, and reviews. It also provides a table of geolocation data to detail the address of sellers and buyers stored in each respective table. Above is a simple description of the relationship between the tables. You can read the details about this dataset further in (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_order_reviews_dataset.csv). Only two tables would be involved here: olist_product_dataset (shortened as ‘product’) and olist_order_items_dataset (shortened as ‘items’).

# Summary
Some of the points obtained in this article can be a reference for sellers in marketing products in this e-commerce, either those who are just starting or old sellers:
- Top 3 categories with the most sales are Bath&Table&Bed, Health&Beauty, and Sport&Leisure
- The price range for products in the popular Bath&Table&Bed category is in the $6 — $200 range, mainly between $50–$117
- The selling price of Bath&Table&Bed has the strongest positive correlation with Product Weight, where customers are willing to pay a higher nominal amount for heavier products
- Summed up from the TOP 10, the most sales in that category weigh under 1kg even though the weight of the Bath&Table&Bed products can make the selling price reasonable
- Some of the characteristics that can be applied when marketing Bath&Table&Bed products in this e-commerce are: 50 characters long product name, costs $100, attach 2–3 product photos
