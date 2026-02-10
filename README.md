# sprint_08_project

Megaline Telecommunications Project - Customer Plan Recommendation System
### Problem Context:
Development of a machine learning classification model to predict which mobile plan (Smart or Ultra) customers will choose based on their usage behavior patterns, enabling Megaline telecommunications company to provide personalized plan recommendations and optimize customer satisfaction.

### Objective:
Build and evaluate classification models to predict customer plan preferences with minimum 75% accuracy, using historical customer behavior data including calls, minutes, messages, and data usage patterns.

Technical Competencies Used:
Data Preprocessing:
- Dataset splitting into training, validation, and test sets (60:20:20 ratio)
- Feature-target separation for supervised learning
- Data type handling and structure validation

Machine Learning Model Development:
- Logistic Regression: Multiple solver optimization (liblinear, lbfgs, newton-cg)
- Random Forest Classifier: Hyperparameter tuning for n_estimators (10-80 range)
- Model comparison and selection based on validation performance
- Cross-validation approach using separate validation set

Model Evaluation:
- Accuracy score calculation for model performance assessment
- Hyperparameter optimization through systematic testing
- Final model validation on unseen test data
- Performance comparison between different algorithms

Hyperparameter Optimization:
- Systematic testing of Logistic Regression solvers
- Loop-based optimization for Random Forest n_estimators
- Best parameter selection based on validation accuracy

### Main Libraries:
- pandas: Data manipulation and DataFrame operations
- scikit-learn: Machine learning algorithms and evaluation metrics
  - RandomForestClassifier: Ensemble learning algorithm
  - LogisticRegression: Linear classification algorithm
  - train_test_split: Data splitting functionality
  - accuracy_score: Model evaluation metric

### Final Results:
Successful development of classification models exceeding the minimum accuracy requirement:

Model Performance:
- Logistic Regression: 77.8% accuracy on test set (newton-cg solver)
- Random Forest Classifier: 82.4% accuracy on test set (n_estimators=40)
- Both models surpassed the 75% minimum accuracy threshold

Best Model Selection:
- Random Forest Classifier identified as the optimal solution
- Achieved 82.4% accuracy on test data
- Demonstrated superior performance in predicting customer plan preferences

Business Impact:
- Enables automated plan recommendation system
- Provides data-driven insights for customer segmentation
- Supports personalized marketing strategies based on usage patterns
- Facilitates improved customer satisfaction through better plan matching

Technical Achievements:
- Proper data splitting methodology preventing data leakage
- Systematic hyperparameter optimization approach
- Robust model evaluation using separate validation and test sets
- Clear model comparison and selection process

The project demonstrates proficiency in end-to-end machine learning pipeline development, from data preprocessing through model selection to performance evaluation for business applications.
