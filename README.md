The analysis performed aims to enhance Airbnb listing performance by analyzing the dynamics of achieving Super host status. Utilizing advanced 
machine learning models and a rich panel dataset, the notebooks provide insights to improve guest experiences and boost overall platform sccess.

**Methodology**

1. **_superhost-classifier_**:  A predictive model designed to forecast whether a host will achieve Superhost status based on their listing history.
   This code analyzes past performance and various metrics to determine the likelihood of a host meeting the criteria for Superhost recognition.
2. **_superhost-loss-classifier_**: A predictive model designed to forecast whether a host will lose Superhost status based on their listing history.
   This code analyzes past performance and various metrics to determine the likelihood of a host meeting the criteria for Superhost recognition.
3. **_overall-rating_**: employs linear and backward linear regression models to identify key factors that significantly influence achieving a high
   overall rating. This approach allows for a detailed understanding of which variables most strongly impact a listing's success in terms of guest satisfaction

**Feature selection**

Our methodology incorporates a specialized feature selection process, particularly effective in handling large datasets with constrained computational resources. Initially,    a gradient boosting model identifies the most influential features, selecting the top 15 for further analysis. From this group, we eliminate features with high correlation     to refine our feature set. This streamlined subset is then analyzed using linear regression to evaluate the individual impact of each feature. This dual-step approach          enhances our model's accuracy while ensuring interpretability is maintained.
