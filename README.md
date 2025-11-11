# A.D.A.P.T
This ML project predicts diabetes progression using scikit-learn's load_diabetes dataset. It compares ensemble techniques with a Decision Tree. The model predicts quantitative disease progression, evaluated by MSE and R-squared. RandomizedSearchCV and cross-validation are used for hyperparameter tuning and robust evaluation.
Features
Implementation of multiple ensemble techniques:
Random Forest
Decision Tree
Gradient Boosting
Cross-validation using RandomizedSearchCV.
Performance metrics such as:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
Dataset
The model uses the load_diabetes dataset from scikit-learn, which contains:

Features: Age, Sex, BMI, Blood Pressure, and 6 blood serum measurements.
Target: A quantitative measure of disease progression one year after baseline.
Requirements
Install the required libraries using:

pip install -r requirements.txt
Libraries Used:
Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn
Model Development Workflow
Data Loading and Preprocessing:

Load the load_diabetes dataset using scikit-learn.
Feature scaling and splitting the dataset into training and test sets.
Model Training:

Train individual models (Random Forest, Decision Tree, Gradient Boosting).
Tune hyperparameters using RandomizedSearchCV.
Evaluation:

Compute metrics for each model (MAE, MSE, RMSE, R² Score).
Perform cross-validation to ensure generalization.
Comparison:

Analyze and compare the performance of models.
Results
Model	RMSE	MAE	R² Score
Random Forest	42.5877	36.0873	0.9168
Adaboost	49.16	43.0607	0.608
Gradient Boosting	55.291	44.5637	0.4337
How to Run
Clone the repository:
git clone https://github.com/your-username/diabetes-prediction.git
Navigate to the project directory:
cd diabetes-prediction
Run the main script:
python main.py
Future Work
Expand the model to handle additional datasets.
Integrate a web-based interface using React.js for the frontend and Django/Flask for the backend.
Deploy the model as a REST API.
Contributing
Contributions are welcome! Please submit a pull request or open an issue to get started.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The load_diabetes dataset from scikit-learn.
Inspiration from various ensemble techniques and machine learning resources.
