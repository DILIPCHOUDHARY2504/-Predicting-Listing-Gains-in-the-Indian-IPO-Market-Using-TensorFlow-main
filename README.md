# Predicting Listing Gains in the Indian IPO Market Using TensorFlow

## Introduction
In this project I worked on the Initial Public Offerings (IPO) in the Indian market. I build a deep learning classification model to determine if there will be listing gains for the IPO. Listing gains are the percentage increase in the share price of a company from its IPO issue price on the day of listing.

The dataset for this project contains information on past IPOs in the Indian market and comes from [moneycontrol](https://www.moneycontrol.com/ipo/ipo-historic-table?classic=true).

## Data Dictionary
The data consists of following column

**Date:** date when the IPO was lised

**IPOName:** name of the IPO

**Issue_Size:** size of the IPO issue, in INR Crores

**Subscription_QIB:** number of times the IPO was subscribed by the QIB (Qualified Institutional Buyer) investor category

**Subscription_HNI:** number of times the IPO was subscribed by the HNI (High Networth Individual) investor category

**Subscription_RII:** number of times the IPO was subscribed by the RII (Retail Individual Investors) investor category

**Subscription_Total:** total number of times the IPO was subs
cribed overall

**Issue_Price:** the price in INR at which the IPO was issued

**Listing_Gains_Percent:** is the percentage gain in the listing price over the issue price

## Performance
The model evaluation output shows the performance of the model on both training and test data. The accuracy was approximately 98% on the training data and 91% on the test data. Ideally, the higher the accuracy value, the better the model is performing. It's noteworthy that the training and test set accuracies are close to each other, which shows that there is consistency and that the accuracy doesn't drop too much when we test the model on unseen data.

## Conclusion

In this project, I have built Deep Learning Classification models using the deep learning framework, Keras, in TensorFlow. I used a real-world IPO dataset and built a classifier algorithm to predict whether an IPO will list at profit or not.

The accuracy was approximately 98% on the training data and 91% on the test data. The accuracy is consistent across the training and test datasets, which is a promising sign. 
