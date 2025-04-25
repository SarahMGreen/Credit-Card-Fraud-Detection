# Credit-Card-Fraud-Detection
Using machine learning algorithms to analyze which is more efficient in catching credit card fraud.

## Techniques Used
- Random Forest (my focus)
- Support Vector Machine (SVM)
- Logistic Regression

## Datasets
- Credit Card Transactions Dataset
- Credit Card Fraud
- IEEE-CIS Fraud Detection dataset
- Credit Card Fraud Detection
- All datasets are from Kaggle

## Tools & Technologies
- Python
- Jupyter Notebook
- pandas, scikit-learn, matplotlib, seaborn
- imbalanced-learn (SMOTE)
- Excel (for basic data cleaning/comparison)

## Goal
To compare models based on:
- Accuracy
- Recall
- Precision
- F1 Score

## My Role
- Focused on Random Forest
- Evaluated model performance and visualized results
- Helped determine the most effective ML technique for fraud detection

## What I Learned
- Real-world data isn’t always clean or labeled clearly
- Random Forest was strong with imbalanced data
- Visualization helped explain complex results
- Fraud detection datasets are very imbalanced

---

🗂️ See the notebook/code files for full implementation.

## Dataset Licensing and Attribution

### 1. **Credit Card Transactions Dataset**
- **License**: Apache 2.0 License
- **Description**: This dataset contains transaction data that is used for analyzing fraud detection in credit card transactions.
- **License Details**: You are free to use, modify, and distribute the dataset. You must provide a copy of this license along with any distribution and give proper attribution.
- **Dataset Link**: [Credit Card Transactions Dataset on Kaggle](https://www.kaggle.com/datasets/priyamchoksi/credit-card-transactions-dataset)
- **Attribution**: This dataset is provided by [Priyam Choksi](https://www.kaggle.com/priyamchoksi) and is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

### 2. **Credit Card Fraud**
- **License**: CC0 (Public Domain)
- **Description**: This dataset contains credit card fraud data, and it is freely available for use without any restrictions.
- **License Details**: You are free to use, modify, and distribute this dataset without any obligation to attribute.
- **Dataset Link**: [Credit Card Fraud Dataset on Kaggle](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud)
- **Attribution**: This dataset is provided by [Dhanush Narayanan R](https://www.kaggle.com/dhanushnarayananr) and is licensed under the [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) license.

### 3. **IEEE-CIS Fraud Detection**
- **License**: Use for non-commercial purposes only (as per competition rules)
- **Description**: This dataset was used in the IEEE Fraud Detection Challenge. It contains information for detecting fraudulent credit card transactions.
- **License Details**: You may use this dataset for academic and non-commercial purposes, including research, but cannot use it commercially unless authorized by the competition rules. For compliance, only **100 rows** of the dataset are shared here to serve as a sample.
- **Dataset Link**: [IEEE-CIS Fraud Detection on Kaggle](https://www.kaggle.com/c/ieee-fraud-detection/data)
- **Attribution**: This dataset is provided by [IEEE Computational Intelligence Society](https://www.kaggle.com/competitions/ieee-fraud-detection/rules#7-competition-data) with an Open-Source License for competition participants.

### 4. **Credit Card Fraud Detection (Open Database)**
- **License**: Database Contents License (DbCL) v1.0
- **Description**: This dataset is open for commercial use and is licensed under the Database Contents License (DbCL).
- **License Details**: You are allowed to use this data for commercial purposes, but you must comply with the **Open Database License (ODbL)**, including attribution and maintaining the integrity of the dataset.
- **Dataset Link**: [Credit Card Fraud Detection Database on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Attribution**: This dataset is provided by [Machine Learning Group - ULB](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) under the [DbCL v1.0 License](https://opendatacommons.org/licenses/dbcl/1-0/).

---
## :arrow_forward: How to Run the Code

1. **Install Requirements**
   ```bash
   pip install pandas scikit-learn seaborn matplotlib imbalanced-learn
   
2. **Download Datasets**
- The datasets I've given are samples (first 100 rows) of the full datasets I used
- If using the samples make sure you change the name of the dataset in the code to match that of the sample you downloaded (e.g. change creditcard.csv to sample_creditcard.csv)

3. **Run the Code**
   
---   
### Compliance Guidelines

To comply with the respective licenses of these datasets, the following modifications have been made:
- **Sample data**: Only **100 rows** of each dataset have been uploaded to ensure compliance with usage restrictions.
- **Attribution**: Proper credit and license information has been included for each dataset as required by their licenses.

For more detailed license information, please refer to the individual dataset descriptions on Kaggle.
