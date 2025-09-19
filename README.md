# 📊 Bank Marketing Campaign Prediction

📌 Overview

This project focuses on analyzing and predicting the success of **bank marketing campaigns** using machine learning. The dataset contains information about customers and their responses to marketing efforts, with the goal of predicting whether a customer will subscribe to a term deposit.

The project demonstrates **data preprocessing**, **exploratory data analysis (EDA)**, and **predictive modeling** using **machine learning algorithms**. It serves as a reference for beginners and intermediate learners in **Data Science** and **Machine Learning**.

📂 Project Structure

├── bank.csv # Dataset

├── bank-marketing-campaigns.ipynb  # Jupyter Notebook (main project code)

├── README.md                       # Documentation file

📑 Dataset Information

The dataset used is the Bank Marketing dataset from a Portuguese banking institution.
Each row represents a client contacted during a marketing campaign.

## 🔑 Key Features:

**age** → Age of the client

**job** → Type of job (admin, technician, entrepreneur, etc.)

**marital** → Marital status

**education** → Education level

**balance** → Bank account balance

**housing** → Housing loan (yes/no)

**loan** → Personal loan (yes/no)

**contact** → Communication type (cellular, telephone, etc.)

**month, day** → Campaign contact month and day

**duration** → Last contact duration (in seconds)

**campaign** → Number of contacts performed during this campaign

**previous** → Number of contacts before this campaign

**poutcome** → Outcome of the previous marketing campaign

**y** → Target variable → Did the client subscribe to a term deposit? (yes/no)

⚙️ Installation & Requirements

To run this project, install the required libraries:

pip install numpy pandas matplotlib seaborn scikit-learn,lightboost

🚀 How to Run

Navigate to the project folder:

cd bank-marketing-campaigns


Open Jupyter Notebook:

jupyter notebook bank-marketing-campaigns.ipynb


Run all cells to execute the analysis and predictions.

📊 Project Workflow

Data Loading & Cleaning → Handling missing values, encoding categorical variables.

Exploratory Data Analysis (EDA) → Visualizing customer demographics, campaign results, and patterns.

Feature Engineering → Preparing dataset for ML models.

Model Training & Evaluation → Implementing classification models like Logistic Regression, Decision Trees, Random Forest,lightboost, etc.

Performance Metrics → Accuracy, classification_report.

🔮 Results

We applied multiple classification algorithms and compared their performance.

📈 Model Comparison (example scores)
Algorithm         	Accuracy	
Logistic Regression	91%
Decision Tree	88%	
Random Forest	92%	
lightboost	91%	
knn    91%

✅ Random Forest performed the best, giving the highest accuracy and balanced scores across all metrics.

This indicates that Random Forest is the most reliable classifier for predicting term deposit subscriptions in this dataset.

📌 Use Cases

Helps banks optimize marketing campaigns.

Reduces cost by targeting potential customers.

Serves as a learning project for data science & ML concepts.

🤝 Contributing

Contributions are welcome!
If you’d like to improve this project, feel free to fork the repo, create a branch, and submit a pull request.

📜 License

This project is licensed under the MIT License - see the LICENSE
 file for details.

🙌 Acknowledgements

Dataset: UCI Machine Learning Repository – Bank Marketing Dataset

Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn,lightboost
