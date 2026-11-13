# SmartStock: An AI-Based Inventory Predictor for Small Grocery Stores

Final project for the Building AI course

## Summary

SmartStock is an AI-based system designed to help small businesses manage their inventory. It analyzes past sales data to predict future product demand and recommend when products should be restocked, helping businesses avoid shortages and excess inventory.

## Background
Small grocery stores sometimes struggle to manage their inventory. Some products sell quickly and run out of stock, while others remain on shelves for a long time. This can lead to lost sales, wasted products, and unnecessary expenses.

SmartStock aims to help solve this problem by using past sales records to predict future product demand. This project is important because it can help small grocery owners make better decisions about purchasing and restocking products.

Problems SmartStock aims to solve
1.)Products running out of stock.

2.)Overstocking and wasted products.

3.)Expired grocery items

4.)Difficulty predicting customer demand.

5.)Poor inventory tracking.

6.)Unnecessary restocking expenses.

7.)Lost sales due to unavailable products.


## How is it used?
Grocery owners enter their previous sales records into SmartStock. The system looks at the data and predicts which products customers are likely to buy in the coming days.

It then suggests which products need to be restocked and how many should be ordered. This helps grocery owners avoid running out of popular products or buying more than they need.

They can use SmartStock through a computer or smartphone, especially when checking their inventory or preparing to order new supplies.

## Data sources and AI methods
For this project, we will use sample grocery sales data that we create ourselves. The data will include product names, dates, and the number of items sold each day. We can also include the current stock of each product.

Here is an example of our sample sales data:

## Sample Sales Data

Product | Monday | Tuesday | Wednesday
--- | --- | --- | ---
Bottled water | 20 | 25 | 30
Canned sardines | 12 | 10 | 15
Instant noodles | 18 | 22 | 20
Milk | 10 | 8 | 12
Eggs (trays) | 5 | 7 | 6

For the AI method, we will use linear regression to study sales patterns and estimate how many products might be sold in the coming days.

The system will use these predictions to recommend which products need restocking and how many should be ordered.

## Challenges
SmartStock may face some challenges when predicting product demand. Its predictions may not always be accurate, especially if the sales records are incomplete or outdated.

Unexpected events, such as holidays, sudden price changes, or supplier delays, may also affect product demand. The system also depends on the grocery owner entering and updating the correct sales and inventory information.

Because of these limitations, SmartStock should be used as a guide rather than a replacement for the owner's decisions.

## What next?
In the future, SmartStock could be improved by using more sales data to make its predictions more accurate. It could also include features that track current inventory, send low-stock alerts, and help grocery owners monitor their products more easily.

To develop the project further, we would need programming skills, knowledge of AI and machine learning, and access to more realistic grocery sales data. We may also need feedback from grocery owners to make sure the system meets their needs.


## Acknowledgment
This project was inspired by the challenges small grocery stores face when managing their inventory.

The idea and project were developed as part of the Building AI course by the University of Helsinki and Reaktor, with some assistance from AI tools during the planning and writing process.

The sample sales data was also created specifically for this project and does not represent actual grocery store records.
