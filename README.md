#Logistic Regression for Hotel Booking Cancellations

This Jupyter Notebook contains a Python script for analyzing and predicting hotel booking cancellations using logistic regression. It explores a dataset related to hotel bookings and provides a step-by-step guide on data preprocessing, model building, and evaluation.

## Dataset

The dataset used in this analysis is the "hotel_bookings.csv" file, which contains information about hotel bookings, including various features such as lead time, customer demographics, booking channels, and reservation details. The main objective is to predict hotel booking cancellations.

### Data Preprocessing

- Handling Missing Values: The notebook addresses missing values in columns like "children," "country," and "agent" using appropriate strategies such as mean, median, and mode imputation.
- Encoding Categorical Variables: Categorical variables are encoded using one-hot encoding to make them suitable for modeling.
- Exploratory Data Analysis (EDA): Basic EDA is performed, including box plots to visualize relationships between the number of adults and booking cancellations.

### Model Building

- Logistic Regression Model: A logistic regression model is built to predict hotel booking cancellations.
- Train-Test Split: The dataset is split into training and testing sets to evaluate model performance.
- Model Evaluation: The notebook calculates and displays the accuracy score of the logistic regression model on the training and testing data.

## Usage

You can run this Jupyter Notebook in a Python environment (e.g., Jupyter Notebook or JupyterLab) to analyze the dataset, preprocess the data, and build the logistic regression model. Ensure you have the required libraries installed, as mentioned in the notebook.

## Dependencies

This notebook relies on the following Python libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```


---
