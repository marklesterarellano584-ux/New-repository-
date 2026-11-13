# SmartStock: An AI-Based Inventory Predictor for Small Businesses

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


This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
