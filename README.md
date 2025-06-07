# 🏡 House Price Prediction and Analysis

This project uses Python to predict house prices using different regression techniques (linear, polynomial, and multiple regression). It also includes exploratory data analysis (EDA) using measures such as mean, median, mode, percentiles, and standard deviation.

---

## 📊 Tools Used

- Python
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- scikit-learn

---

## 📂 Project Files

- `house_price_analysis.ipynb`: The main Jupyter Notebook with code and analysis.
- `images/.png`: Sample plot.
- `requirements.txt`: (Optional) List of dependencies.

---

## 🖼️ Sample Visualization

Here’s a Sample Visualization of house prices:

![House Price Distribution](images/hpd.png)
![Polynomial Regression](images/pr.png)
![Simple Linear Regression](images/lr.png)

---

## 🚀 What I Did
- Explored the data: calculated mean, median, mode, percentiles, and standard deviation.
- Visualized data distributions using histograms, box plots, and scatter plots.
- Built models using linear, polynomial, and multiple regression.
- Evaluated models using R² score.

---

## 📈 Results
                                   ## Model Performance Summary:
| Model                 | R² Score | MAE (Mean Absolute Error) | RMSE (Root Mean Squared Error) |
| --------------------- | -------: | ------------------------: | -----------------------------: |
| Simple Linear         |    0.273 |                 1,474,748 |                      1,917,104 |
| Polynomial (Degree 2) |    0.295 |                 1,435,043 |                      1,887,327 |
| Multiple Linear       |    0.653 |                   970,043 |                      1,324,507 |

Mean Price: 4,766,729.25
Median Price: 4,340,000.00
Mode Price: 3,500,000.00
Standard Deviation of Price: 1,870,439.62

Price Percentiles:
0.25    3430000.0
0.50    4340000.0
0.75    5740000.0

Simple Linear Regression:
R² Score: 0.27
MAE: 1474748.13
RMSE: 1917103.70

Polynomial Regression (Degree 2):
R² Score: 0.30
MAE: 1435042.81
RMSE: 1887327.30

Linear Regression Coefficients: [425.72984194]
Linear Regression Intercept: 2512254.2639593435

Multiple Regression:
R² Score: 0.65
MAE: 970043.40
RMSE: 1324506.96

Multiple Linear Regression Coefficients:
                            Feature    Coefficient
2                         bathrooms  521879.027748
0                              area  519552.416340
9               airconditioning_yes  365157.393851
3                           stories  349251.438906
10                     prefarea_yes  266656.351993
12     furnishingstatus_unfurnished -192015.917982
4                           parking  192005.953667
7                      basement_yes  187067.803214
8               hotwaterheating_yes  149862.702991
5                      mainroad_yes  128498.628215
6                     guestroom_yes   88768.667686
11  furnishingstatus_semi-furnished  -62837.321865
1                          bedrooms   57349.559419

---

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Tony-Magabush28/House-Price-Prediction-and-Analysis

