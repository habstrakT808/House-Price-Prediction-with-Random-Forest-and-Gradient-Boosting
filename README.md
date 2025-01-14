# House Price Prediction with Random Forest and Gradient Boosting

## 📖 Project Overview
This project focuses on predicting house prices in Tebet, Jakarta, using two powerful machine learning algorithms: **Random Forest** and **Gradient Boosting**. The goal is to build accurate predictive models and evaluate their performance using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²).

## 📂 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)

---

## 📊 Dataset
The dataset used in this project contains real estate listings, including features such as:
- **Location**
- **Size (in square meters)**
- **Number of bedrooms and bathrooms**
- **Amenities**
- **Year built**

### Source
The dataset was obtained from Kaggle's open data platform. Any sensitive information has been cleaned to ensure data privacy.

---

## 🛠️ Technologies Used
The project is built using the following tools and libraries:
- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)
Before modeling, an in-depth EDA was conducted:
- **Visualizing Distributions**: To understand the spread of data.
- **Correlation Analysis**: To identify relationships between variables.
- **Outlier Detection**: Using the Interquartile Range (IQR) method.

---

## 🧹 Data Preprocessing
Data preprocessing steps included:
1. Handling missing values.
2. Removing outliers using the IQR method.
3. Feature scaling and encoding categorical variables.
4. Splitting data into training and testing sets.

---

## 🤖 Modeling
Two machine learning algorithms were employed:
- **Random Forest Regressor**: A robust ensemble learning method.
- **Gradient Boosting Regressor**: A boosting method that optimizes predictive accuracy.

### Hyperparameter Tuning
GridSearchCV was used to optimize the hyperparameters for both models, ensuring optimal performance.

---

## 📈 Results
Here are the evaluation metrics for each model:

| Metric                | Random Forest       | Gradient Boosting    |
|-----------------------|---------------------|-----------------------|
| **MAE**              | Rp 1,026,505,867.58 | Rp 1,034,015,348.56  |
| **RMSE**             | Rp 1,452,379,881.55 | Rp 1,492,548,191.79  |
| **R²**               | 0.680               | 0.663                |

**Scatter Plot Comparison:**
The following plots visualize the relationship between actual and predicted house prices for both models:

![Gradient Boosting Scatter Plot](https://github.com/user-attachments/assets/8096223c-e92a-4920-b0c4-aebbe0541bbf)

---

## 📚 Conclusion
- **Random Forest** performed slightly better than Gradient Boosting, achieving lower MAE and RMSE and a higher R².
- Outliers in the data likely influenced the metrics despite preprocessing.
- The project highlights the importance of feature engineering and hyperparameter tuning in improving model performance.

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd house-price-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python scripts to train and evaluate the models.

---

## 📧 Contact
If you have any questions or feedback, feel free to reach out:
- **Name**: Hafiyan Al Muqaffi Umary
- **Email**: jhodywiraputra@gmail.com

Thank you for exploring this project! 🎉
