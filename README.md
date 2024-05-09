# Diabetes Prediction and Analysis

This project aims to analyze and predict the presence of diabetes using various machine learning techniques on the Diabetes dataset. The analysis includes exploratory data analysis (EDA), data preprocessing, and model training and evaluation.

## Dataset

The dataset used in this project is the Pima Indians Diabetes Dataset from the National Institute of Diabetes and Digestive and Kidney Diseases. It consists of several medical predictor variables and one target variable, Outcome, which indicates whether a person has diabetes or not.

## Project Structure

The project is structured as follows:

```
├── data/
│   └── diabetes.csv      # Dataset file
├── notebooks/
│   └── Diabetes_Analysis.ipynb  # Jupyter Notebook containing the analysis
├── README.md
```

## Requirements

The following Python libraries are required to run the code:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Feature Engine

## Analysis

The analysis includes the following steps:

1. **Data Loading and Exploration**: The dataset is loaded into a Pandas DataFrame, and basic information about the data, such as shape, data types, and summary statistics, is displayed.

2. **Exploratory Data Analysis (EDA)**: Various visualization techniques, including histograms, scatter plots, pair plots, joint plots, hexbin plots, violin plots, and box plots, are used to explore the relationships between variables and identify potential patterns or outliers.

3. **Data Preprocessing**: The dataset is checked for duplicates and missing values. Outliers are identified and treated using the Winsorizer technique from the Feature Engine library. Cube root transformations are applied to skewed numerical variables.

4. **Feature Scaling**: The numerical features are scaled using the MinMaxScaler from Scikit-learn.

5. **Model Training and Evaluation**: The dataset is split into training and testing sets. Several regression models (Linear Regression, Ridge Regression, and Lasso Regression) and classification models (Decision Tree, Random Forest, and Gradient Boosting) are trained and evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared, accuracy, and confusion matrix.

## Usage

To run the analysis, follow these steps:

1. Clone the repository to your local machine.
2. Install the required Python libraries.
3. Navigate to the `notebooks/` directory.
4. Open the `Diabetes_Analysis.ipynb` notebook in Jupyter Notebook or JupyterLab.
5. Run the notebook cells sequentially to execute the analysis.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The Pima Indians Diabetes Dataset was obtained from the National Institute of Diabetes and Digestive and Kidney Diseases.
- The analysis and code were inspired by various online resources and tutorials.
