# Modeling Survival: Predictive Analytics on the Titanic
## Introduction
This project stems from my interest in understanding how different machine learning algorithms perform when applied to real-world classification problems. Using the Titanic dataset from Kaggle, I explored three models—Linear Regression, K-Nearest Neighbors (KNN), and Decision Tree—to predict passenger survival. My primary goal was not only to build accurate models, but to evaluate and compare their performance in order to determine which approach best captures the underlying patterns in the data. This process deepened my understanding of model behavior, trade-offs in interpretability and accuracy, and the importance of thoughtful preprocessing in predictive analytics.

## Methodology
To evaluate which machine learning model performs best in predicting Titanic passenger survival, I followed a structured analytical process:

### 1. Data Preparation:
I began by selecting relevant features (Age, Fare, Sex, Pclass, Parch) and handling missing values using median imputation for numerical variables. Categorical variables were encoded using binary and one-hot encoding techniques.

### 2. Feature Scaling:
Since distance-based models like KNN are sensitive to feature magnitudes, I standardized all numerical features. Additionally, I adjusted the weight of the Age feature to enhance its impact based on exploratory analysis.

### 3. Model Development:
I trained three models—Linear Regression, K-Nearest Neighbors, and Decision Tree—using the preprocessed data. Each model was built within a pipeline to ensure consistent transformation and evaluation.

### 4. Evaluation:
Model performance was assessed using classification accuracy on the test set. For Linear Regression, predicted probabilities were thresholded at 0.5 to produce binary outcomes.

### 5. Submission:
The best-performing model’s predictions were formatted according to Kaggle’s submission requirements and saved for evaluation on the Titanic competition leaderboard.

## Conclusion
After building and evaluating three machine learning models—Linear Regression, K-Nearest Neighbors (KNN), and Decision Tree—to predict survival outcomes on the Titanic dataset, KNN demonstrated the highest predictive performance. Through careful preprocessing, feature scaling, and model tuning, KNN consistently outperformed the other models in validation accuracy. This outcome highlights the effectiveness of distance-based algorithms for structured datasets where feature scaling and local data patterns play a significant role. The project reinforced the importance of model selection, hyperparameter tuning, and evaluation in building accurate and reliable predictive models.
