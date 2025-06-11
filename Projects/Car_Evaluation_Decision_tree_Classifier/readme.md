# Car Evaluation Decision Tree Classifier

This project builds and evaluates Decision Tree classifiers on the Car Evaluation dataset, which contains categorical features describing cars and a target label indicating whether a car is "purchased" or not.

---

## 📋 Dataset

The dataset contains the following features, all categorical:

| Feature   | Description                 |
|-----------|-----------------------------|
| buying    | Buying price (vhigh, high, med, low) |
| maint     | Maintenance price (vhigh, high, med, low) |
| doors     | Number of doors (2, 3, 4, 5more) |
| persons   | Capacity in terms of persons to carry (2, 4, more) |
| lug_boot  | Size of luggage boot (small, med, big) |
| safety    | Estimated safety of the car (low, med, high) |
| Purchased | Target variable (car acceptability) |

---

## 🛠️ Tools & Libraries

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- category_encoders
- graphviz
- joblib

---

### 1. Clone the repository:

```bash
git clone https://github.com/sujalxverma/ML.git
cd Projects/Cancer_Logistic_Regression

## 🚀 Installation

Install required packages with pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn category_encoders graphviz joblib
!pip install category_encoders graphviz joblib