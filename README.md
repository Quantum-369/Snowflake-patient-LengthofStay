# End-to-End Healthcare Analytics using Snowflake and AWS 🏥

[![Snowflake](https://img.shields.io/badge/Snowflake-v-blue)](https://www.snowflake.com/)
[![AWS](https://img.shields.io/badge/AWS-Sagemaker-orange)](https://aws.amazon.com/sagemaker/)
[![Python](https://img.shields.io/badge/Python-v3.8-blue)](https://www.python.org/)

## 📖 Project Overview

This project demonstrates an end-to-end healthcare analytics solution using Snowflake and AWS services. The primary focus is on analyzing patient length of stay (LOS) data, which is a critical metric in healthcare. By leveraging Snowflake's data warehousing capabilities and AWS Sagemaker for machine learning, the solution aims to:

1. Perform exploratory data analysis (EDA) and feature engineering in Snowflake.
2. Build a machine learning model to predict patient LOS using various regression techniques.
3. Deploy the model for live scoring and update the predictions back to Snowflake.
4. Schedule the model execution and send status emails.

## 🛠️ Tech Stack

- **Data Warehouse:** Snowflake
- **Cloud Platform:** AWS
- **Machine Learning:** AWS Sagemaker
- **Programming Language:** Python
- **Libraries:** `snowflake-connector-python`, `snowflake-sqlalchemy`, `xgboost`, `pandas`, `numpy`, `scikit-learn`

## 📂 Project Structure

```
healthcare-analytics/
├── Data/
│   ├── health_data.csv
│   └── simulation_data.csv
├── Python Files/
│   ├── data_preprocessing.ipynb
│   ├── feature_engineering.ipynb
│   ├── model_training.ipynb
│   └── model_deployment.ipynb
└── SQL Queries/
    ├── eda.sql
    └── feature_engineering.sql
```

## 🚀 Getting Started

### Prerequisites

- Snowflake Account
- AWS Account
- Understanding of basic SQL queries

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/healthcare-analytics.git
cd healthcare-analytics
```

2. Set up Snowflake and AWS Sagemaker:
   - Create a Snowflake account and a real-time data warehouse project.
   - Set up an AWS Sagemaker instance.

3. Load the data into Snowflake:
   - Upload the `health_data.csv` and `simulation_data.csv` files to the Snowflake table.

4. Run the SQL queries:
   - Execute the SQL queries in the `SQL Queries` folder to perform EDA and feature engineering in Snowflake.

5. Run the Python notebooks:
   - Open the Jupyter notebooks in the `Python Files` folder and follow the step-by-step instructions.
   - Make sure to configure the necessary Snowflake and AWS Sagemaker connections.

## 📚 Project Takeaways

1. Understand the Snowflake UI and data analysis using Snowflake Worksheet.
2. Learn about Common Table Expressions (CTEs) in SQL.
3. Perform feature engineering in Snowflake.
4. Fetch data from Snowflake to Python using the Snowflake connector.
5. Set up Jupyter on AWS Sagemaker and select the appropriate machine.
6. Preprocess data, select important features, and build machine learning models.
7. Deploy the model for live scoring and update predictions in Snowflake.
8. Schedule the model execution and send status emails.

## 🤝 Contributing

Contributions to this project are welcome. To contribute, please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
Made with ❤️ by HARSHA VARDHAN SAI MACHINENI
</div>
