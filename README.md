# Oil Extraction Prediction Model

## Overview
This project presents a data-driven approach to predicting oil extraction volumes from different geographic regions, including the subsequent impact on revenue. Using real-world geological and production data, the notebook guides you through data exploration, preprocessing, model development, and evaluation to support decision-making in oil field development and investment. This project has been implemented using OOP and even though this approach is not generally recommended for ipynb files still works and simplifies the final invocation of methods and procedures. A version using pipelines will be implemented in the future.

## Features
- **Data Exploration:** In-depth analysis of geological features and oil production data from multiple regions.
- **Data Preprocessing:** Handling missing values, outliers, and feature engineering for optimal model performance.
- **Evaluation:** Use of metrics such as RMSE and confidence intervals to assess model accuracy and reliability. Revenue as bussiness metric is used to determine the impact of the model implementation
- **Business Insights:** Recommendations for selecting the most promising oil fields and minimizing investment risks.

## How to Use
1. Clone this repository or download the notebook.
2. Ensure you have the required dependencies (see below).
3. Open `sprint_10.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells sequentially to reproduce the analysis and results.

## Requirements
- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies with:
```bash
pip install -r requirements.txt
```

## Data
The analysis uses the following datasets:
- `geo_data_0.csv`
- `geo_data_1.csv`
- `geo_data_2.csv`

All data files are located in the `data/` directory.

## Project Structure
```
oil_extraction_prediction_model/
├── sprint_10.ipynb
├── data/
│   ├── geo_data_0.csv
│   ├── geo_data_1.csv
│   └── geo_data_2.csv
└── README.md
```

## Results
- Built regression models to predict oil extraction volumes for different regions.
- Identified the most promising oil fields for investment based on model predictions and risk analysis.
- Provided actionable recommendations to maximize returns and minimize risks in oil extraction projects.

## License
This project is for educational and demonstration purposes.

---

