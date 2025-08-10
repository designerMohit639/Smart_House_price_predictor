# House Price Prediction Model

This project uses **Linear Regression** to predict house prices based on various features such as average area income, house age, number of rooms, and population.

## 📂 Dataset
The dataset should contain the following columns:
- `Avg. Area Income`
- `Avg. Area House Age`
- `Avg. Area Number of Rooms`
- `Avg. Area Number of Bedrooms`
- `Area Population`
- `Price` (Target variable)
- `Address` (Not used for prediction)

Example:
| Avg. Area Income | Avg. Area House Age | Avg. Area Number of Rooms | Avg. Area Number of Bedrooms | Area Population | Price       | Address |
|------------------|---------------------|---------------------------|------------------------------|-----------------|-------------|---------|
| 79545.45         | 5.68                | 7.00                      | 4.09                         | 23086.80        | 1.05e+06    | ...     |

## ⚙️ Installation
Make sure you have Python installed.  
Install required libraries using:
```bash
pip install pandas numpy scikit-learn
