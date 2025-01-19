
# 🏦 Bank Marketing Campaign Analysis 🏦

##  Project Overview
This project involves analyzing a bank marketing campaign dataset and using logistic regression to predict whether a client will subscribe to a term deposit. The dataset contains customer demographics, financial attributes, and previous campaign interactions.

##  Dataset Description
The dataset consists of:
- ** Train Data (`train (1).csv`)**: Used to train the logistic regression model.
- ** Test Data (`test (1).csv`)**: Used to make predictions.

###  Features
- ** Numerical Features**: `age`, `balance`, `day`, `duration`, `campaign`, `pdays`, `previous`
- ** Categorical Features**: `job`, `marital`, `education`, `default`, `housing`, `loan`, `contact`, `month`, `poutcome`
- ** Target Variable**: `y` (Binary: `yes` or `no`)

##  Implementation Details
###  Steps Involved
1. ** Load the dataset**: Train and test datasets are loaded using Pandas.
2. ** Preprocessing**:
   - Convert categorical columns to category data type.
   - Encode the target variable (`y`) into binary values (Yes -> 1, No -> 0).
   - Separate numerical and categorical features.
   - Apply feature scaling to numerical data using `StandardScaler`.
   - Handle missing values and encode categorical variables using `OneHotEncoder`.
3. ** Model Training**:
   - Implement a `LogisticRegression` model.
   - Train the model using a pipeline that includes preprocessing.
4. ** Predictions**:
   - Predict outcomes for the test dataset.
   - Convert predictions back to categorical labels (`yes` or `no`).
   - Save predictions to `predictions.csv`.

##  Project Files
- ** `train (1).csv`** – Training dataset
- ** `test (1).csv`** – Test dataset
- ** `predictions.csv`** – Model predictions
- ** `1162.csv`** – Additional data (purpose to be clarified)
- ** `EDA.ipynb`** – Jupyter notebook for Exploratory Data Analysis (EDA)
- ** `Predictions.ipynb`** – Jupyter notebook for making predictions using the trained model
- ** `README.md`** – Documentation file explaining the project
- ** `1162.pdf`** - PDF file exported from the Power BI for Dashboard to provide insights into the data

##  Performance Metrics
- ** Accuracy**: Measures the percentage of correctly predicted instances.
- ** Confusion Matrix**: Provides insights into true positives, false positives, true negatives, and false negatives.
- ** Precision & Recall**: Evaluates the model’s ability to minimize false positives and false negatives.
- ** F1 Score**: Balances precision and recall for an overall model assessment.

##  Future Enhancements
-  Improve feature engineering to enhance model accuracy.
-  Try other machine learning models like Decision Trees and Random Forest.
-  Perform hyperparameter tuning to optimize performance.
-  Conduct further EDA to uncover hidden patterns.
-  Explore deep learning techniques for better predictions.

##  Dependencies
-  Python
-  Pandas
-  NumPy
-  Scikit-learn
-  seaborn
-  matplotlib
-  Power BI

##  How to Run
1. Install dependencies using:
   ```sh
   pip install pandas numpy scikit-learn
   ```
2. Run the script:
   ```sh
   python script.py
   ```
3. The output predictions will be saved in `predictions.csv`.

##  Output File
- `📄 predictions.csv`: Contains the predicted values for the test dataset.

## Video Presentation
- Video Link - [https://drive.google.com/file/d/1AfqPT70K4Q0eWk5XsirfhAUms4sQYuDZ/view?usp=sharing](url)

## 💬 Feedback
We welcome feedback and suggestions for improving this project! Feel free to contribute by:
- Reporting issues or bugs 
- Suggesting improvements 
- Enhancing documentation 
- Sharing your thoughts 

For any feedback, please reach out via email:
- Harsh Agarwal :	[agarwal.harsh.2451513@gmail.com](url)
- Siva Maruthi  : [sivamaruthi590@gmail.com](url)
- Shivangi Rai	 : [raishivangi943@gmail.com](url)

## 👥 Authors
Developed by **Harsh Agarwal**, **Siva Maruthi** and **Shivangi Rai**. 




