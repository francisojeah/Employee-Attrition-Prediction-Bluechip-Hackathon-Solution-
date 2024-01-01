# Employee Attrition Prediction - Bluechip Summit Hackathon Solution

This repository contains my solution for the Employee Attrition Prediction challenge presented at the Bluechip Summit hackathon. The objective of this challenge was to predict the probability of employee attrition within a given company using machine learning techniques.

## Leaderboards
### Public Leaderboard (20% Test Data)

This leaderboard represents the standings calculated with approximately 20% of the test data at the time of the hackathon. The final results, based on the remaining 80% of the test data, led to different standings.
<p align="center">
  <img src="assets/images/public leaderboard.png" width="" alt="Leaderboard-20% of test data" />
</p>

- **Position:** 85
- **Accuracy:** 0.90164

### Private Leaderboard (80% Test Data - Final Standings)

The private leaderboard reflects the final standings calculated with approximately 80% of the test data at the time of the hackathon. As the competition concluded, this leaderboard showcases the ultimate rankings in the Employee Attrition Prediction challenge. 
<p align="center">
  <img src="assets/images/private leaderboard.png" width="" alt="Final Leaderboard-80% of test data" />
</p>
- **Position:** 64
- **Accuracy:** 0.87396

### Problem Statement
Employee attrition poses a significant challenge for organizations, impacting productivity and incurring high recruitment costs. The task was to develop a predictive model that anticipates the likelihood of an employee leaving the company based on provided data.

### File Structure

```bash
Employee-Attrition-Prediction-Bluechip-Hackathon-Solution/
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
├── modeling/
│   └── models.ipynb
├── README.md
└── requirements.txt
```

### Dataset
The dataset provided for this challenge includes two main files:

- **train.csv**: Contains the training data with various features related to employees.
- **test.csv**: Holds the test data for which predictions need to be made.
- **sample_submission.csv**: A sample submission file format to follow for submitting predictions.

### Solution Overview
The solution involved several key steps:

- Exploratory Data Analysis (EDA): Understanding the data distribution, identifying patterns, and gaining insights into factors influencing attrition.
- Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
- Feature Engineering: Creating new features or transforming existing ones to improve model performance.
- Model Building: Utilizing machine learning algorithms such as XGBoost, Random Forest, and Logistic Regression to predict the probability of employee attrition.
- Evaluation: Assessing model performance using appropriate metrics like accuracy, precision, recall, and ROC-AUC.


## Getting Started

### Prerequisites
- Python 3
- Jupyter Notebook (optional for running the provided notebooks)
- Required Python libraries (listed in requirements.txt)

### Clone the Repository

```bash
git https://github.com/francisojeah/Employee-Attrition-Prediction-Bluechip-Hackathon-Solution.git
```

### Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
- Place the provided train.csv and test.csv files in the project directory.
- Run the provided notebooks or scripts to reproduce the analysis, feature engineering, model building, and predictions.
- Ensure that the submission file follows the format specified in sample_submission.csv.

## Results
The best-performing model achieved a probability prediction accuracy of 90% on the test set, demonstrating its effectiveness in predicting employee attrition.

## Contributing
Contributions to improve the solution or explore additional insights are welcome. Fork the repository, make changes, and create a pull request.

## License
This project is licensed under the MIT License.
