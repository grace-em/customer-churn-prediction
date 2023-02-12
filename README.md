# customer-churn-prediction

<b>CUSTOMER CHURN IN THE TELECOMMUNICATION INDUSRTY</b>
<br>

<i>What are the key factors responsible for customer churn and ways/recommendations to ensure customer retention?</i> 

<b>Business Understanding</b>
<br>
Customer churn is a big problem in any industry and one of the most important concerns for the Telecom industry. The effect on the revenues of the companies, because of this customer churns is huge, especially in the telecom field, that's why these companies are seeking to develop a predictive potential customer churn. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate, and it costs 5-10 times more to acquire a new customer than to retain an existing one, that's why customer retention has now become even more important than customer acquisition.

Therefore, finding those factors that increase customer churn is important to take necessary actions to reduce this churn. The main goal of our project is to develop an understanding of the cause of customer churn which assists telecom operators to predict customers who are most likely subject to churn, and what to do to retain the most valuable customer.


<b>Main Objective</b>
<br>
Maximize: Company's profit by retaining customer
Minimize: Customer churn by identifying the key cause of the problem

<b>The specific objectives</b>
    
   1. Finding factors and cause those influence customers to churn.
   2. Retain churn customers by taking appropriate steps
   3. Providing offers based on affecting factors.

<b>Data Understanding</b>
<br>
Breakdown of Features in the dataset:
<br>

- STATE: 51 Unique States name

- Account Length: Length of The Account

- Area Code: Code Number of Area having some States

- International Plan: Yes Indicate International Plan is Present and No Indicates no subscription for Internatinal Plan

- Voice Mail Plan: Yes Indicates Voice Mail Plan is Present and No Indicates no subscription for Voice Mail Plan

- Number vmail messages: Number of Voice Mail Messages ranging from 0 to 50

- Total day minutes: Total Number of Minutes Spent in Morning

- Total day calls: Total Number of Calls made in Morning.

- Total day charge: Total Charge to the Customers in Morning.

- Total eve minutes: Total Number of Minutes Spent in Evening

- Total eve calls: Total Number of Calls made r in Evening.

- Total eve charge: Total Charge to the Customers in Morning.

- Total night minutes: Total Number of Minutes Spent in the Night.

- Total night calls: Total Number of Calls made in Night.

- Total night charge: Total Charge to the Customers in Night.

- Customer service calls Number of customer service calls made by customer

- Churn Customer Churn, True means churned customer, False means retained customer

<b>Modelling</b>
<br>
I split the data into training and test. I used the training to fit the models and the test data to assess the models. The first model was a baseline using Decision Trees. Random Forest and Logistic Regression were also used. From these, Random Forest, Decision Tree, Linear Regression were tuned to produce better accuracy.

<b>Evaluation</b>
<br>
The evaluation metric used was accuracy score . The model had a a training score of 0.85 and a testing score of 0.8. This model performed the best, hence why it was picked as the final model. It also had an overall accuracy of 0.8, which means that the model is able to correctly classify 80% of the features.

<b>Conclusion</b>
<br>
- The four charge fields are linear functions of the minute fields(have a high correlation).
- The area code field and the state field are anomalous and can be omitted.
- Customers with the international plan tend to churn more frequently.
- Customers with four or more customer service calls churn more than four times as often as the other customers.
- Customers with high day minutes and evening minutes tend to churn at a higher rate than do the other customer.

<b>Recommendations</b>
<br>
- Improve network coverage in more states
- For international plan provide some discount plan to the customer as an incentive
- Improve the voice mail quality or take feedback from the customer
- Improve the service of call center and take frequently feedback from the customer regarding their issue and try to solve it as soon as possible
