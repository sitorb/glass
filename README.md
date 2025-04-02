# Glass Classification using Decision Tree

## Project Overview

This project demonstrates the use of a Decision Tree classifier to predict the type of glass based on its chemical composition. The dataset used is the "Glass Identification Database" which contains information about the percentage of various elements present in different types of glass.

## Project Goals

- Build a machine learning model to classify glass types accurately.
- Explore and visualize the decision-making process of the model.
- Evaluate the model's performance using relevant metrics.

## Code Structure and Logic

1. **Data Loading and Preprocessing:**
   - The code starts by loading the dataset using pandas.
   - Missing values are checked and handled.
   - The target variable ('Type') is converted to a categorical type.
   - The dataset is split into training and testing sets using `train_test_split`.
   - Features are scaled using `StandardScaler` to improve model performance.

2. **Model Training and Hyperparameter Tuning:**
   - A Decision Tree classifier is instantiated.
   - `GridSearchCV` is used to find the best hyperparameters for the model, optimizing for accuracy.
   - The model is trained on the training data using the best hyperparameters.

3. **Prediction and Evaluation:**
   - Predictions are made on the test data.
   - Model performance is evaluated using accuracy score and classification report.

4. **Visualization:**
   - The decision tree is visualized using `plot_tree` to understand the decision-making process.
   - Feature importance is plotted to identify the most influential features.
   - A confusion matrix is generated to visualize the model's performance across different classes.
  
  ![image](https://github.com/user-attachments/assets/819df16d-6e88-4be5-a446-de3b21eb3fc6)

![image](https://github.com/user-attachments/assets/61327d23-186c-4601-a3aa-79f721ea2877)

![image](https://github.com/user-attachments/assets/958db17c-cf0a-4776-9584-1da2cf5020a0)


## Technology and Algorithms

- **Programming Language:** Python
- **Libraries:** pandas, scikit-learn (sklearn), matplotlib, seaborn
- **Algorithm:** Decision Tree Classifier
- **Hyperparameter Tuning:** GridSearchCV
- **Evaluation Metrics:** Accuracy, Classification Report, Confusion Matrix



## Conclusion

This project successfully demonstrates the application of a Decision Tree classifier for glass classification. The model achieves a good accuracy and provides insights into the factors influencing glass type prediction.

## Usage

1. Clone the repository.
2. Install the necessary libraries: `pip install pandas scikit-learn matplotlib seaborn`.
3. Run the Jupyter Notebook to execute the code and view the results.
