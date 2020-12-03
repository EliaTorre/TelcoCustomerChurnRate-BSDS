# Churn-Rate-Analysis-Hackathon
 ML Churn Rate Analysis for BSDS Hackthon 
 
This database reports data related to a “​Churn analysis​” for a ​Telecommunication company. You may already know about it, but churn analysis studies the churn rate of a company, where the churn rate represents the portion of customers that leave that specific company. Therefore, it’s fairly easy to understand why firms need and strive to have relevant information about why, how and when a customer leaves the company, the most immediate one being trying to retain that customer and prevent that to happen in the future with another customer.
Let’s try to dive into this dataset and let me explain the meaning of the following columns.
1) “gender”, Whether the customer is a male or a female
2) “Partner”, Whether the customer has a partner or not (Yes, No)
3) “PhoneService”, Whether the customer has a phone service or not (Yes, No)
4) “InternetService”, Customer’s internet service provider (DSL, Fiber optic, No)
5) “OnlineSecurity”, Whether the customer has online security or not (Yes, No, No
internet service)
6) “Contract”, The contract term of the customer (Month-to-month, One year, Two year)
7) “PaymentMethod”, The customer’s payment method (Electronic check, Mailed check,
Bank transfer (automatic), Credit card (automatic)
8) “MonthlyCharges”, The amount charged to the customer monthly
9) “TotalCharges”, The total amount charged to the customer
10) “Churn”,Whether the customer churned or not (Yes or No). This represents the label
that your model should try to predict, so you’ll find yourself facing with a ​supervised machine learning problem​ (supervised means that you know what you’re trying to predict, i.e. the “Churn” label).
What you’re asked to do is to try to deploy a machine learning algorithm in order to train a model on the set we will give you trying to predict as precisely as possible if the customer will or won’t leave the company in the next future. The “training set” that you have been given has all the 10 columns described above, while the “test set” that I, the keys-keeper, greedly enshrine in my computer, will miss the label column, the one called “Churn”, and on this dataset your ML model will be tested.
