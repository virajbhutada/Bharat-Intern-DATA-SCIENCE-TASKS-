## 🚢 Titanic Classification

The objective of this project was to design a robust system capable of predicting a person's likelihood of survival in the event of the Titanic disaster. This challenge involved meticulously analyzing the dataset, extracting meaningful insights, and constructing predictive models to forecast survival outcomes.

## Key Conditions

### Factors for Prediction
The primary focus was on understanding the influence of various factors on survival probabilities:

| Factor                | Description                                   |
|-----------------------|-----------------------------------------------|
| **Socio-economic status** | Class of the passenger (1st, 2nd, 3rd)     |
| **Age**               | Age of the passenger                          |
| **Gender**            | Gender of the passenger                       |
| **Family relationships** | Number of siblings/spouses aboard          |
| **Fare**              | Ticket price paid by the passenger            |

---

### Machine Learning Models
Several classification algorithms were employed to create accurate predictive models:

| Model                    | Description                                 |
|--------------------------|---------------------------------------------|
| **Decision Tree Classifier** | A tree-based model for classification   |
| **Logistic Regression**   | A statistical model for binary outcomes    |
| **AdaBoost Classifier**   | An ensemble technique for boosting         |
| **Random Forest Classifier** | An ensemble of decision trees           |
| **K-Nearest Neighbors (KNN)** | A distance-based classification model  |

---

## Approach

### Data Exploration
🔍 **Initial Analysis**: An in-depth exploration of the Titanic dataset to comprehend its structure and the variables within. This included examining data distributions and relationships between variables.

### Data Preprocessing
⚙️ **Data Cleaning and Preparation**:
- **Handling Missing Values**: Missing values were imputed using appropriate strategies.
- **Encoding Categorical Variables**: Categorical variables were encoded to be compatible with machine learning algorithms.
- **Feature Selection**: Relevant features were carefully selected based on their predictive power and importance.

### Model Selection and Evaluation
📊 **Training and Evaluation**:
- Models were trained on the training data and rigorously evaluated to ensure accuracy and reliability.
- Performance metrics such as accuracy, precision, recall, and F1-score were used to compare models.

| Metric       | Description                                  |
|--------------|----------------------------------------------|
| **Accuracy** | Proportion of correctly predicted instances  |
| **Precision**| Proportion of true positive instances        |
| **Recall**   | Proportion of actual positives correctly identified |
| **F1-score** | Harmonic mean of precision and recall        |

---

### Fine-tuning
🔧 **Hyperparameter Tuning**: Techniques were employed to optimize the models for better predictive performance. This step involved adjusting model parameters to enhance accuracy and generalization.

### Visualization
📈 **Data Visualizations**:
- **Histograms**: To visualize the distribution of numerical variables.
- **Countplots**: To show the count of categorical variable levels.
- **Heatmaps**: To illustrate correlation between features.
- **Pair Plots**: To explore relationships between multiple features.

---

### Conclusion
📝 **Summary**: The project concluded with a comprehensive analysis summarizing the findings, including the impact of socio-economic status, age, and gender on survival probabilities. The exploration revealed significant insights into the factors influencing passenger survival. Through meticulous modeling and hyperparameter tuning, the most accurate predictive model was identified.

### Models Used
Here are the models used in this project, along with their implementation:

```python
models = {
    'Decision Tree Classifier': DecisionTreeClassifier(),
    'Logistic Regression': LogisticRegression(),
    'Ada Boost Classifier': AdaBoostClassifier(),
    'Random Forest': RandomForestClassifier(),
    'KNN': KNeighborsClassifier()
}
```

### Dataset
The Titanic dataset used for this project is available on Kaggle:
- [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

This analysis of the Titanic dataset provided valuable insights into the factors influencing passenger survival. The project encompassed diverse aspects, including socio-economic status, age, gender, and family relationships. Through meticulous modeling and hyperparameter tuning, the most accurate predictive model was identified. The visualizations, particularly pair plots, were instrumental in illustrating the relationships between vital variables and deepening the understanding of the dataset. This project served as a significant learning experience, enriching my understanding of data analysis and modeling techniques and highlighting the pivotal roles of socio-economic status and age in shaping survival probabilities during the tragic Titanic disaster.
