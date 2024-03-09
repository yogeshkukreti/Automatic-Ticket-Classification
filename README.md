# Automatic Ticket Classification

<hr style="border:0.2px solid gray"> </hr>

We need to build a model that can classify customer complaints based on the products/services. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

We will be doing topic modeling on the <b>.json</b> data provided by the company. Since this data is not labeled, we need to apply NMF to analyze patterns and classify tickets into the following five clusters based on their products/services:

* Credit card / Prepaid card

* Bank account services

* Theft/Dispute reporting

* Mortgages/loans

* Others 


With the help of topic modeling, we will be able to map each ticket to its respective department/category. We can then use this data to train any supervised model such as logistic regression, decision tree, or random forest. Using this trained model, we can classify any new customer complaint support ticket into its relevant department.
