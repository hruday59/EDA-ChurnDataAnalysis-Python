# EDA-ChurnDataAnalysis-Python
This project analyzes customer churn using Python, Pandas, Matplotlib, and Seaborn. The main objective is to understand customer behavior and identify service-related and account-related factors associated with customers leaving the company.
<img width="489" height="489" alt="image" src="https://github.com/user-attachments/assets/5618384c-ac46-4380-a14a-ec9325a94b48" />


Key observations
1. PhoneService: Most customers have phone service. Both churners and non-churners are more numerous among customers with phone service.

2. MultipleLines: Customers with and without multiple lines show substantial numbers of non-churners. Customers without phone service form a smaller group.

3. InternetService: Fiber optic customers have a relatively high number of churners, while DSL customers show fewer churners. Customers without internet service have comparatively low churn.

4. OnlineSecurity: Customers without online security show considerably higher churn than customers who have online security. This may indicate that online security is associated with better customer retention.

5. OnlineBackup: Customers without online backup have more churners than customers who have online backup, although churn is present in both groups.

6. DeviceProtection: Customers without device protection show more churners than customers with device protection.

7. TechSupport: Customers without tech support have considerably more churners than customers who receive tech support.

8. StreamingTV: Churn occurs among customers both with and without streaming TV. The differences in raw counts should be interpreted alongside the number of customers in each group.

9. StreamingMovies: Similar to StreamingTV, churn occurs in both categories. Customers without streaming movies also include a substantial number of non-churners.
Overall conclusion
The plots suggest that InternetService, OnlineSecurity, and TechSupport may be particularly useful features for predicting customer churn. Fiber optic customers appear to have a relatively high churn count, while customers without online security or technical support also show substantial churn.
