# <span style="color:#4CAF50">Bank Marketing Campaign Analysis</span>

### <span style="color:#2196F3">Project Overview</span>
This project involves analyzing a bank marketing campaign dataset and using logistic regression to predict whether a client will subscribe to a term deposit. The dataset contains customer demographics, financial attributes, and previous campaign interactions.

### <span style="color:#2196F3">Dataset Description</span>
The dataset consists of:
- **Train Data (`train (1).csv`)**: Used to train the logistic regression model.
- **Test Data (`test (1).csv`)**: Used to make predictions.
- **Predictions (`predictions.csv`)**: The final output containing predicted labels for the test dataset.
- **Additional Data (`1162.csv`)**: Purpose to be clarified.

#### <span style="color:#2196F3">Features</span>
- **Numerical Features**: `age`, `balance`, `day`, `duration`, `campaign`, `pdays`, `previous`
- **Categorical Features**: `job`, `marital`, `education`, `default`, `housing`, `loan`, `contact`, `month`, `poutcome`
- **Target Variable**: `y` (Binary: `yes` or `no`)

### <span style="color:#2196F3">Implementation Details</span>
#### <span style="color:#2196F3">Steps Involved</span>
1. **Load the dataset**: Train and test datasets are loaded using Pandas.
2. **Preprocessing**:
   - Convert categorical columns to category data type.
   - Encode the target variable (`y`) into binary values (Yes -> 1, No -> 0).
   - Separate numerical and categorical features.
   - Apply feature scaling to numerical data using `StandardScaler`.
   - Handle missing values and encode categorical variables using `OneHotEncoder`.
3. **Model Training**:
   - Implement a `LogisticRegression` model.
   - Train the model using a pipeline that includes preprocessing.
4. **Predictions**:
   - Predict outcomes for the test dataset.
   - Convert predictions back to categorical labels (`yes` or `no`).
   - Save predictions to `predictions.csv`.

### <span style="color:#2196F3">Project Files</span>
- **Train Data (`train (1).csv`)** – Training dataset
- **Test Data (`test (1).csv`)** – Test dataset
- **Predictions (`predictions.csv`)** – Model predictions
- **Additional Data (`1162.csv`)** – Purpose to be clarified
- **EDA (`EDA.ipynb`)** – Jupyter notebook for Exploratory Data Analysis (EDA)
- **Predictions (`Predictions.ipynb`)** – Jupyter notebook for making predictions using the trained model
- **Documentation (`README.md`)** – Documentation file explaining the project

### <span style="color:#2196F3">Performance Metrics</span>
- **Accuracy**: Measures the percentage of correctly predicted instances.
- **Confusion Matrix**: Provides insights into true positives, false positives, true negatives, and false negatives.
- **Precision & Recall**: Evaluates the model’s ability to minimize false positives and false negatives.
- **F1 Score**: Balances precision and recall for an overall model assessment.

### <span style="color:#2196F3">Future Enhancements</span>
- Improve feature engineering to enhance model accuracy.
- Try other machine learning models like Decision Trees and Random Forest.
- Perform hyperparameter tuning to optimize performance.
- Conduct further EDA to uncover hidden patterns.
- Explore deep learning techniques for better predictions.

### <span style="color:#2196F3">Dependencies</span>
- Python 3.x
- Pandas
- NumPy
- Scikit-learn

### <span style="color:#2196F3">How to Run</span>
1. Install dependencies using:
   ```sh
   pip install pandas numpy scikit-learn
2.Run the script:
python script.py
3. The output predictions will be saved in predictions.csv.
<span style="color:#2196F3">Output File</span>
predictions.csv: Contains the predicted values for the test dataset.
<span style="color:#2196F3">Feedback</span>
We welcome feedback and suggestions for improving this project! Feel free to contribute by:

- Reporting issues or bugs
- Suggesting improvements
- Enhancing documentation
- Sharing your thoughts
For any feedback, please reach out via email:

Name	Email Address
Harsh Agarwal	agarwal.harsh.2451513@gmail.com
Siva Maruthi	sivamaruthi590@gmail.com
Shivangi Rai	raishivangi943@gmail.com
<span style="color:#2196F3">Project Creators</span>
- Harsh Agarwal
- Siva Maruthi
- Shivangi Rai



