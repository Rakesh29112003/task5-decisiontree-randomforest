# Heart Disease Classification using Decision Trees and Random Forests

## Objective
Learn and apply tree-based machine learning models for classification using the Heart Disease dataset.

## Tools Used
- Python
- Scikit-learn
- Matplotlib & Seaborn (for visualization)

## Dataset
The dataset used is the [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci) containing features such as age, sex, chest pain type, cholesterol levels, etc. The target variable indicates the presence (1) or absence (0) of heart disease.

## Steps Performed

1. **Load and preprocess the dataset**  
   Load the data, split it into training and testing sets, and prepare for modeling.

2. **Train a Decision Tree Classifier**  
   A Decision Tree model is trained and visualized to understand the learned structure.

3. **Overfitting Analysis**  
   Accuracy is evaluated across multiple tree depths to analyze overfitting and identify the optimal depth.

4. **Train a Random Forest Classifier**  
   A Random Forest model is trained and its accuracy is compared to the Decision Tree.

5. **Feature Importance Interpretation**  
   The most important features contributing to predictions are visualized.

6. **Cross-Validation**  
   5-fold cross-validation is used to evaluate model robustness and generalization.

## How to Run

1. Install required packages:
    ```bash
    pip install pandas scikit-learn matplotlib seaborn
    ```

2. Run the script:
    ```bash
    python heart_disease_tree_models.py
    ```

## Output

- Decision Tree visualization
- Overfitting analysis report
- Random Forest accuracy
- Feature importance barplot
- Cross-validation scores

## Author
Generated as part of a machine learning assignment on tree-based models.
