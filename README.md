# Brazil_E-commerce_by_Olist
Improve customer experience in Eastern and Northeastern Brazil when ordering on Olist
# Introduction
Olist is a Brazilian E-commerce that has faced some lossed recently. It want to imporve customer experience in Eastern and Northeatern Brazil by setting up its own logistics center to reduce delivery time and freight cost.
# Objective
* Answer the question: Why does Olist need to own the logistics center.
* Which state Olist should set up the logistics center and what categories should be put there?
* Estimate the performance of building the logistics center, including the time saved and freight cost.
# Datasets
* Dataset characteristic.
* On Kaggle, ist data of 100k orders from September 2016 to August 2018. And each of dataset saved information about orders, products, customers and sellers. The data model has been described in image below and it is organised and normalised for each category.
* Source: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
# EDA and Visualizations
* In E-commerece, there are certain factors from the customer's point of view which influece their purchasing decision. Here's a look at those concerns that leverage customer buying behavior.
1. Good product quality
2. Free shipping experience
3. Easy return policy
4. Reviews from customers.
5. Easy navigation
# 1.1 Wordcloud
![wordclould_review](https://user-images.githubusercontent.com/122089400/228762936-dd3edb74-2b18-4fd0-b1c0-53de438129d5.png)
This is a wordcloud made from customer revew. Time, delivery, and arrived are customers care. Thus, delivery service is very important to Olist customers.
# 1.2 Exploratory and analysis datasets
# 1.2.1 Delivery time and product category.
![image](https://user-images.githubusercontent.com/122089400/228765343-db01409d-1fbe-4213-bb03-ca20e20efde1.png)
* The payment time is roughty the same. The carrier time is the time from platform approve order to the seller delivery the goods. It can be inferred that office furniture need assembly or customized production, the carrier time is the longest. If Seller can offer dissembled furniture-reducing assembly time and quickly shipping (such as IKEA's product).
* All category of goods, the delivery time is the longest of the total time and the delivery time has no corelation with category.
# 1.2.2 Correlation coefficient matrix
![image](https://user-images.githubusercontent.com/122089400/228767020-f0938e76-99c1-4ac2-b372-15d31e0e77a5.png)



