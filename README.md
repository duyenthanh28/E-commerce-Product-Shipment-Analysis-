#Product-Shipment-Analysis
Ecommerce shipping is the process of delivering an online order from the fulfilment center
to the customer’s provided address.
Ecommerce shipping involves multiple steps:
Order Processing - Customers place an online order and order gets allocated to a particular
fulfilment center using the optimization algorithm based on the distance from destination
address, cost of delivery, already scheduled delivery near the destination address, availability of
the products.
Shipping Service - To gain customer satisfaction, companies are fighting to optimize the
shipping services targeting same day delivery etc. However, not all retailers can afford that or it
even makes sense as not every city/state has the fulfilment centers of each company.
There are multiple shipping methods that companies offer like - 2 day shipping, Overnight
shipping, Same day delivery, International shipping, Expedited shipping, Eco friendly shipping
and Freight shipping.
All the above shipping methods come at different costs and it depends on various factors
like distance, item dimensions, weight, destination accessibility etc.

This project targets to use supervised learning  to predict the outcome based on the various input
parameters available to us. The Outcome variable for this data set is  "Reached on time" - where 1 Indicates that the product has
NOT reached on time and 0 indicates it has reached on time.
The outcome variable "Reached On Time" is a classification variable and hence I will 
use the LogisticRegression() Algorithm in Python. I will also be doing predictor reduction
methodologies to see what set of variables gets us higher confusion matrix accuracy.
I will then also be exploring Unsupervised learning like Cluster Analysis to identify the
categories of the data impacting the different outcomes.
