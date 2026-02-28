# 📊 Mini Data Analysis & Visualization System

A lightweight Python project that loads sales data, performs basic cleaning, generates statistical summaries, and creates simple visualizations.

If `sales_data.csv` is not found, the program automatically generates a sample dataset — making it instantly runnable for demos, learning, or experimentation. 🚀

📌 **This project was built during the *Python Programming Virtual Internship* at Cryptonic Area.**

---

## 🚀 Features

* ✅ Auto-generates `sales_data.csv` if missing
* 🧹 Removes duplicate records
* 📊 Fills missing numeric values using column mean
* 📈 Displays statistical summary using `df.describe()`
* 📊 Bar Chart: Total Sales by Category
* 📉 Histogram: Profit Distribution
* 🎯 Beginner-friendly and easily extendable

---

## 🛠 Tech Stack

* Python 3.8+
* pandas
* matplotlib

Install dependencies:

```bash
pip install pandas matplotlib
```

Or create a `requirements.txt`:

```
pandas
matplotlib
```

Then install:

```bash
pip install -r requirements.txt
```

---

## 📂 Project Structure

```
mini-data-analysis/
│
├── main.py                # Main script
├── sales_data.csv         # Auto-created if not present
├── plots/                 # Optional folder for saved visualizations
└── README.md
```

---

## 📌 How It Works

### 1️⃣ Auto Dataset Creation

If `sales_data.csv` does not exist, a sample dataset is generated automatically.

### 2️⃣ Data Cleaning

* Removes duplicate rows
* Fills missing numeric values with column mean

### 3️⃣ Statistical Summary

Displays:

* Count
* Mean
* Standard deviation
* Min / Max values

### 4️⃣ Visualizations

* **Bar Plot** → Total Sales grouped by Category
* **Histogram** → Profit distribution

---

## 📄 Expected CSV Format

| Column   | Type    | Description           |
| -------- | ------- | --------------------- |
| Category | String  | Product category name |
| Sales    | Numeric | Sales amount          |
| Profit   | Numeric | Profit amount         |

Example:

```
Category,Sales,Profit
Electronics,50000,5000
Clothing,20000,2000
Furniture,30000,3000
```

---

## ▶️ How to Run

```bash
python main.py
```

The program will:

* Create dataset (if missing)
* Clean data
* Print summary
* Display visualizations

---

## 🐞 Troubleshooting

**ModuleNotFoundError**

```
pip install package_name
```

**Plots not showing?**
If using a remote/non-GUI environment, replace `plt.show()` with:

```python
plt.savefig("plot_name.png")
```

---

## 🎯 Learning Outcomes

Through this internship project, key skills practiced include:

* Data handling using pandas
* Data cleaning techniques
* Exploratory Data Analysis (EDA)
* Data visualization using matplotlib
* Writing structured and modular Python scripts

---

