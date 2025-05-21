# The Digital Shift: Analyzing Trends in Book Publishing and Library Visits

### Authors:
- Harsh Chavva
- Nandini Gunda
- Anusha Pogaku

## 📄 Project Summary

This research investigates the evolving relationship between public libraries and the rise of digital publishing platforms like Kindle. Focusing on Texas public libraries from 2018 to 2023, the study analyzes circulation trends, visit patterns, and eBook usage, combining machine learning and time series forecasting techniques to understand and predict future behavior.

Key findings show:
- A steady increase in digital borrowing (eBooks & audiobooks)
- Slight decline in in-person library visits
- Importance of hybrid models (physical + digital)

Machine learning and statistical models used include:
- Prophet (Time Series Forecasting)
- Random Forest and XGBoost (Classification)
- OLS Regression (Quantitative Impact Analysis)

## 🎯 Objectives

- Analyze trends in physical and digital book circulation.
- Classify libraries by digital engagement level.
- Forecast library visit and circulation trends through 2026.
- Assess the impact of Kindle sales on library engagement.

## 📊 Data Sources

- Texas State Library and Archives Commission (2018–2023)
- Kindle Books Dataset from Kaggle (2023)

> [Texas Library Statistics](https://www.tsl.texas.gov/ldn/statistics)  
> [Kindle Books Dataset](https://www.kaggle.com/datasets/asaniczka/amazon-kindle-books-dataset2023-130k-books)

## 🤖 Methodology

### 🔹 Exploratory Data Analysis
- Time series trends
- Outlier detection and treatment
- Distribution analysis by region and year

### 🔹 Machine Learning Models
- **Prophet**: Forecasts library visits, eBook and print circulation
- **Random Forest & XGBoost**: Classify libraries (Low, Medium, High digital engagement)
- **OLS Regression**: Quantifies Kindle and eBook impact on library usage

### 📈 Evaluation Metrics
- MAE, RMSE, MAPE (Forecasting)
- Accuracy, Confusion Matrix (Classification)
- R², p-value, F-statistic (Regression)

## 📊 Interactive Dashboard

Visualize Texas library data using the Tableau dashboard:  
> [📍 Tableau Dashboard Link](#) *(Insert the real link here)*

Includes:
- Library Visits Over Time
- Circulation Comparison: Digital vs Physical
- Geographic and City-Level Analysis

## ✅ Key Results

- **Forecasting Accuracy**
  - eBooks MAE: 1.22M | RMSE: 1.50M | MAPE: 14.5%
  - Physical Books MAE: 1.56M | RMSE: 1.97M | MAPE: 14.3%
  - Library Visits MAE: 2.93M | RMSE: 3.81M | MAPE: 25.0%

- **Classification**
  - Random Forest Accuracy: 86.6%
  - XGBoost Accuracy: 87.6%

- **Regression**
  - Circulation Model R²: 0.937
  - Visits Model R²: 0.727

## 📁 Folder Structure

```
RESEARCHPROJECT/
│
├── data/                 # Sample datasets
├── code                  # Google Collab
├── outputs/              # Visual results (graphs, plots)
├── README.md             # Project description
├── requirements.txt      # Python packages
├── .gitignore            # Excluded files

## ⚠️ Limitations

- Study limited to Texas; not representative of all regions
- PCA removes interpretability in some model outputs
- Classifier performance depends on well-labeled, balanced datasets
- Gaps from missing data affect model generalizability

## 🔭 Future Scope

- Expand to other U.S. states or regions
- Include demographic attributes (age, income, etc.)
- Study AI tools' impact on library traffic
- Find ideal balance between digital and physical services

## ▶️ Run Instructions

1. Clone this repo:
   ```
   git clone https://github.com/ANUSHA960279/RESEARCHPROJECT.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run notebooks or scripts in:
   - `notebooks/`
   - `scripts/`

## 📄 License

This project is licensed under the MIT License.
