<h1 align="center">
Telco-Customers Churn-Rate Analysis</h1>

<div align="center">
  <a href="https://www.linkedin.com/in/eliatorre/">Elia Torre</a>,
  <a href="https://www.linkedin.com/in/edoardobotta/">Edoardo Botta</a>,
  <a href="https://www.linkedin.com/in/marco-antonioli/">Marco Antonioli</a>
  <p><a href="https://bidsa.unibocconi.eu">Bocconi Institute for Data Science and Analytics</a>, Bocconi University, Milan, Italy</p>
</div>

<hr/>

Project developed alongside Edoardo Botta and Marco Antonioli for the Hackathon of the Bocconi Students for Data Science (BSDS).

Churn analysis studies the churn rate of a company, where the churn rate represents the portion of customers that leave that specific company. it’s fairly easy to understand why firms need and strive to have relevant information about why, how and when a customer leaves the company, the most immediate one being trying to retain that customer and prevent that to happen in the future with another customer. One branch in which the churn analysis is particulary exploited is the Telecommunications, as in the studied case.

For this Hackathon we were presented with a dataset of customers and we were asked to predict whether a customer were going to change company or not. Let’s try to dive into this dataset and let me explain the meaning of the following columns.

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
that the model should try to predict, so we found ourselves facing with a supervised
machine learning problem.

The “training set” that we have been given has all the 10 columns described above, while the “test set” that the keys-keeper greedly enshrined in his computer, missed the label column, the one called “Churn”, and on this dataset our ML model have been tested.

For our work, which predicted the churn rate with a precision of 80.15% we ranked 2nd.
