# Heart Disease Prediction using Logistic Regression

This project demonstrates the prediction of heart disease using a Logistic Regression model in Python.

## Dataset

The project utilizes the `heart_disease_data.csv` dataset, which contains various features related to heart health. The 'target' column indicates the presence (1) or absence (0) of heart disease.

## Libraries Used

- pandas
- numpy
- scikit-learn (sklearn)

## Steps

1. **Data Loading and Preprocessing:**
   - The dataset is loaded using pandas.
   - The dataset is explored for shape, descriptive statistics, and missing values.

2. **Feature and Target Separation:**
   - The 'target' column is separated as the target variable (Y).
   - The remaining columns are used as features (X).

3. **Train-Test Split:**
   - The data is split into training and testing sets using `train_test_split`.

4. **Model Training:**
   - A Logistic Regression model is trained using the training data.

5. **Model Evaluation:**
   - The model is evaluated using accuracy score on both training and testing sets.

6. **Prediction:**
   - A sample input is used to demonstrate the prediction process.

## Usage

1. **Install Libraries:** Install the required libraries.
2. **Dataset:** Place the `heart_disease_data.csv` file in the project directory.
3. **Run:** Execute the Jupyter Notebook or Python script to train the model and make predictions.

## Results

The model's accuracy score on the training and testing sets is printed.

## Note

This project is for demonstration purposes and may need adjustments for different datasets or scenarios.
