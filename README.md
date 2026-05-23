# Linear Regression E-Commerce Project

An end-to-end Machine Learning project utilizing Multi-Variable Linear Regression to analyze customer behavior data for an e-commerce company and provide data-driven business recommendations optimizing App vs. Website growth.

## 🚀 Key Features & Workflow
* **Exploratory Data Analysis (EDA):** Visualized correlations using Seaborn (`jointplot`, `pairplot`) to isolate primary conversion drivers.
* **Model Training:** Built and trained a Multi-Variable Linear Regression model using `scikit-learn`.
* **Feature Importance:** Evaluated coefficients to compare the financial impact of mobile application development versus website enhancements.

## 📊 Model Evaluation Metrics
After splitting the data into training and testing sets, the model achieved the following performance results:
* **Mean Absolute Error (MAE):** [8.4260]
* **Mean Squared Error (MSE):** [103.91554]
* **Root Mean Squared Error (RMSE):** [10.1938]

## 💡 Key Business Insights
* The model coefficients revealed that **Time on App** had a significantly higher impact on yearly spending compared to **Time on Website**.
* **Recommendation:** Allocate strategic resources toward enhancing the mobile application user experience to maximize ROI, while stabilizing website functionality.

## 🛠️ Tech Stack Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Environment:** Jupyter Notebook


