## Portfolio

---

### [IS 6850 Home Credit Default Risk Project 🏡](https://github.com/owen-simon/IS-6850-home-credit-project) 

Graduate capstone project (MSBA, University of Utah) using data from the Kaggle [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk) competition.

**Overview**
Built an end to end credit default prediction pipeline by cleaning, integrating, and engineering features across multiple relational datasets.

**Highlights**
- Engineered client level features from application, bureau, POS, credit card, installment, and prior loan data
- Applied robust data cleaning, anomaly handling, and missing value strategies
- Maintained strict train and test separation to prevent data leakage
- Developed reusable, modular R functions for data processing and feature engineering

**Modeling**
- Compared Logistic Regression, LASSO, and Random Forest (cross validated ROC AUC)
- Selected LASSO for strong generalization and interpretability
- Performed threshold optimization to inform approval and profit strategy

**Extras**
- Model card covering performance, fairness, and deployment considerations
- Quarto notebooks and rendered HTML outputs for reproducibility

---

### [Formula One Constructor Championship Predictions 🏎️](https://github.com/owen-simon/Formula-1-Constructor-Repository.git)

Predictive modeling project forecasting Formula One Constructors' Championship winners using historical race results, team characteristics, driver performance, and engineered competitive metrics.

**Overview**
Developed a machine learning pipeline to estimate each constructor's preseason probability of winning the Formula One Constructors' Championship using historical data from the 2000 through 2025 seasons.

**Highlights**
- Engineered team, driver, engine, and historical performance features from multiple Formula One seasons
- Designed a leakage resistant preprocessing pipeline using only information available before each season
- Implemented expanding window cross validation to preserve the chronological nature of the data
- Produced preseason championship probability estimates for every constructor

**Modeling**
- Compared Logistic Regression, Decision Trees, Bagging, Random Forest, Gradient Boosting, AdaBoost, Ridge, LASSO, Elastic Net, Naive Bayes, KNN, Neural Networks, and Support Vector Machines
- Evaluated models using ROC AUC, Accuracy, Precision, Recall, F1 Score, and Specificity
- Selected a Radial Support Vector Machine as the final model based on cross-validated performance

**Extras**
- Comprehensive feature engineering and modeling documentation
- Prediction visualizations comparing preseason forecasts with the 2026 championship standings
- Fully reproducible R workflow and project documentation

---

## Conference Abstracts

Carmichael, C., Bertholf, C., Simon, O., Guidroz, R., Karam, A., Newton, D., & Champagne, C. (2025). A five-week diet and education intervention increased skin carotenoid levels in children: Results from a pilot Veggie Meter® study. Journal of the Academy of Nutrition and Dietetics, 125(10), A104. https://doi.org/10.1016/j.jand.2025.06.376

Carmichael, C., Camel, S., Bertholf, C., Simon, O., & Champagne, C. (2026). Inter-device reliability of the Veggie Meter®: Paving the way for future collaborations. Journal of the Academy of Nutrition and Dietetics, 126(10). https://doi.org/10.1016/j.jand.2026.156694
