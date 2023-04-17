Bank Customer Churn Prediction
Business Perspective
•Build a model to predict the churn of the bank customer.
•Parameters affecting the churn of the customer.
•Business Suggestions to have better churn.
               Factors Not affecting Churn




• Salary and Credit Score are similarly distributed for both existing and
  non existing customers.
• Salary and Credit score is not affecting the churning of the customer.
 Days of LIC are gone..




• No pattern in tenure of customers leaving.
• Old and New Customers are equally Likely to exit.
                                      Major Stack Holders…




• Average age of the exiting customer is more than the existing by almost 10years, mostly in late 40s.
• Average balance is significantly higher for people exiting.
     Quality Products are the key…




• Customers exiting had experience of more products, but still they chose to leave.
• Case should have been inverse.
Suggestive Measures…
§The Salaries & Credit score are mostly similar for the customers who have not churned as well
 as churned.
§People having all spend less or long time with bank have same probability of churning.
§Pattern in customers churning
 § Average age is higher.
 § Average balance is higher than exiting customers.
 § Customers late stage of life & good amount of money.

§Having quality products is the key
 § Insurances and SIPs are not the only needs of customers now.
 § With growth of technology, customers seek better returns from there money.
 § Cryptocurrencies, Better trading options along with better feasibility is needed.
Technical Details Ahead…
Technical Details
                    • 4 Models, 2weak learner and 2 strong learners where
                      chosen.
                    • Dataset was highly bias, used ADASYN over sampling
                      techniques was used.
                    • Hyperparameter tuning was done for models for there
                      best performance.
                    • RandomForestClassifier showed the best accuracy, but
                      the final decision was made on Precision Score.
                    • Precision Score is better metric for churn analysis.
Thank You
