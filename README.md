# my-first-ml-project
A beginner-friendly Machine Learning project that explores medical insurance data, performs data cleaning and preprocessing, and uses Linear Regression to predict insurance charges based on factors such as age, BMI, smoking habits, and other personal characteristics.
# Medical Insurance Cost Prediction 💰

## About the Project

Ever wondered why medical insurance costs differ from person to person? This project explores that question using data analysis and machine learning.

The goal of this project is to understand how factors such as age, BMI, smoking habits, number of children, gender, and geographical region relate to medical insurance charges. I worked with an insurance dataset, cleaned and prepared the data, explored patterns through visualizations, and built a Linear Regression model to predict insurance costs.

This project helped me practise the essential steps involved in a typical machine learning workflow, from understanding raw data to training and evaluating a predictive model.

## What I Did

- **Data Exploration:** Examined the dataset to understand its structure, columns, and statistical summaries.
- **Data Visualization:** Used histograms, count plots, box plots, and a correlation heatmap to explore the data and identify patterns.
- **Data Cleaning:** Checked for missing values and removed duplicate records.
- **Data Preprocessing:** Converted categorical variables into numerical representations and applied one-hot encoding to the region column.
- **Feature Engineering:** Created BMI categories to represent different BMI ranges.
- **Feature Scaling:** Standardized selected numerical features using StandardScaler.
- **Statistical Analysis:** Used Pearson correlation and chi-square tests to investigate relationships between features and insurance charges.
- **Model Building:** Used Linear Regression to predict medical insurance charges.
- **Model Evaluation:** Used the R² score and adjusted R² score to evaluate the model.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook / Google Colab

## Dataset

The project uses an `insurance.csv` dataset containing information about individuals and their medical insurance charges.

The dataset includes features such as:
- Age
- Gender
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Geographical region
- Medical insurance charges

## Machine Learning Algorithm

**Linear Regression** is used to estimate medical insurance charges based on selected input features.

The dataset is divided into training and testing sets, with 80% used for training and 20% reserved for testing.

The model's performance is evaluated using the R² score and adjusted R² score.

## What I Learned

Through this project, I gained practical experience in data cleaning, exploratory data analysis, feature engineering, statistical feature analysis, data preprocessing, and building a machine learning model.

It also helped me understand how raw data can be transformed into a format suitable for machine learning and how statistical techniques can help investigate relationships between different variables.

## Future Improvements

- Compare Linear Regression with other regression algorithms.
- Experiment with different feature-selection techniques.
- Improve model performance through further experimentation.
- Build a simple web application where users can enter their details and receive an estimated insurance charge.

---

**Note:** This project is intended for educational purposes. Its predictions should not be treated as actual insurance quotes or medical or financial advice.
