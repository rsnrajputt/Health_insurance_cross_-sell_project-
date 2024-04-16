# Health_insurance_cross_-sell_project-Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue. In Exploratory Data Analysis, we categorized the Age as YoungAge, MiddleAge, OldAge.Then we categorized Region_Code and Policy_Sales_Channel to extract some valuable information from these features. We explored the independent features using some plots. Then the feature selection we used ExtraTreesClassifier and then the train test split. For Model prediction, we used supervised machine learning algorithms like logistic regression, Random forest classifier and Decision Tree.
Conclusion After loading our dataset, we initially checked for null values and duplicates. There were no null values and duplicates so treatment of such was not required. Before data processing, we applied feature scaling techniques to normalize our data to bring all features on the same scale and make it easier to process ML algorithms.

Through Exploratory Data Analysis, we categorized Age as YoungAge, MiddleAge, and OldAge. Further, we observed that customers belonging to youngAge are more interested in vehicle insurance. We observed that customers having vehicles older than 2 years are more likely to be interested in vehicle insurance. Similarly, customers having damaged vehicles are more likely to be interested in vehicle insurance.

For Feature Selection, We used feature imortance and we observed that Previously_Insured is the most important feature and has the highest impact on the dependent feature and there is no correlation between the numeric features.

Next we implemented nine machine learning algorithms namely, 'LogisticRegression', 'DecisionTreeClassifier', 'RandomForestClassifier'. We did hyperparameter tuning into improve our models performance. The 'RandomForestClassifier', 'XGBClassifier', 'LGBMClassifier' models are best performing models with test accuracy score of 92-94% but we have an imbalance dataset, So we have to consider precision and recall and roc_auc score as well, accuracy alone can be misleading.

Key points:

Customers of age between 30 to 60 are more likely to buy insurance.

Customers with Vehicle_Damage are likely to buy insurance.

Customers with Driving License have higher chance of buying Insurance.

The variable Vehicle_damage, Age, Previously_insured, Annual_premium are affecting the target variable.

