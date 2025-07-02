# Social Ads Logistic Regression Model

This project builds a **Logistic Regression model** on the popular **Social Network Ads dataset** to predict whether a user will purchase a product based on their **Age** and **Estimated Salary**.

---

## 📌 Project Overview

- **Goal:** Predict if a user will purchase based on Age and Salary.
- **Algorithm:** Logistic Regression (Binary Classification)
- **Dataset:** Social_Network_Ads.csv
- **Tools Used:** Python, scikit-learn, Matplotlib, Seaborn, Pandas, Numpy

---

## 📂 Dataset Description

- **Source:** Social Network Ads Dataset (commonly used in ML tutorials)
- **Features:**
  - `Age` (Numeric)
  - `EstimatedSalary` (Numeric)
- **Target:**
  - `Purchased` (Binary: 0 = Not Purchased, 1 = Purchased)

---

## ⚙️ Workflow

1. **Data Loading and Exploration**
2. **Data Preprocessing**
   - Train-Test Split
   - Feature Scaling
3. **Model Training**
   - Logistic Regression using scikit-learn
4. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
5. **Visualization**
   - Scatter Plot
   - Logistic Regression Curve
   - Decision Boundary

---

## 📈 Results

- Achieved good accuracy on the test set.
- Visualized the logistic curve showing purchase probability with respect to age.
- Plotted decision boundaries to show classification regions.

---

## ✅ Requirements

- Python 3.x
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

### Installation:

`Here’s the **clean, corrected, and complete Markdown block** for your **"How to Run" + Requirements + Visualizations + Tags + Author + License** section:

---

````markdown
## ✅ Requirements

Make sure you have Python installed.

Install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
````

---

## 🚀 How to Run

1. **Clone this repository:**

```bash
git clone https://github.com/yourusername/social-ads-logistic-regression-model.git
```

2. **Navigate to the project folder:**

```bash
cd social-ads-logistic-regression-model
```

3. **Run the Python script or Jupyter Notebook:**

If you are using a Python script:

```bash
python logistic_regression_social_ads.py
```

Or, if using Jupyter Notebook:

* Open the `.ipynb` file in Jupyter Notebook or JupyterLab.

4. **Make sure the dataset file is present:**

Place the file **`Social_Network_Ads.csv`** inside the project directory (same folder as your Python or notebook file).

---

## 📊 Visualizations Included

* Scatter Plot (Age vs Purchased)
* Logistic Regression Curve
* Decision Boundary Visualization

---

## 🏷️ Topics / Tags

* machine-learning
* logistic-regression
* classification
* social-network-ads
* purchase-prediction
* scikit-learn
* data-visualization
* binary-classification
* python
* data-science

---

## 📌 Author

**Alok Bhateshwar**

---

## ✅ License

This project is open-source and free to use for educational and learning purposes.
