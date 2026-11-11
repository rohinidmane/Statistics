# 📊 Percentiles and Four-Number Summary – Statistics

This project explains percentiles, quartiles, interpolation, and the four-number summary using Python and NumPy. It also demonstrates how to create boxplots and detect outliers using the Interquartile Range (IQR) method.

## 📊 What This Project Does

- Understands percentiles and quartiles (Q1, Q2, Q3).
- Calculates percentiles for even and odd datasets.
- Performs percentile calculations using NumPy.
- Understands linear interpolation.
- Explores the four-number summary.
- Creates boxplots using Matplotlib.
- Detects outliers using the IQR method.

## 🔄 Project Workflow

Understand Percentiles → Sort Data → Calculate Quartiles → Apply NumPy Percentile → Understand Interpolation → Calculate IQR → Detect Outliers → Visualize Using Boxplot

## 📊 Dataset Information

**Example Dataset:**

```python
data = [3, 5, 7, 8, 9, 10, 13, 15, 16, 18]
```

**Key Percentiles:**

- P25 = Q1 (First Quartile)
- P50 = Q2 (Median)
- P75 = Q3 (Third Quartile)

**Four-Number Summary:**

- Q1 – 25th Percentile
- Q2 – Median (50th Percentile)
- Q3 – 75th Percentile
- IQR – Q3 - Q1

## 🧠 Key Concepts Covered

- Percentiles
- Quartiles
- Median
- Even and Odd Datasets
- Linear Interpolation
- NumPy Percentile
- Four-Number Summary
- Interquartile Range (IQR)
- Boxplot Visualization
- Outlier Detection
- 1.5 × IQR Rule
- Extreme Outliers (3 × IQR)

## 🛠️ Tech Stack

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## 📈 Statistical Operations Performed

| Concept              | Purpose                                                          |
|----------------------|------------------------------------------------------------------|
| Percentiles          | Finds values below which a given percentage of observations fall |
| Q1                   | Calculates the 25th percentile                                   |
| Q2                   | Calculates the median                                            |
| Q3                   | Calculates the 75th percentile                                   |
| np.percentile()      | Calculates percentiles using NumPy                               |
| Linear Interpolation | Estimates values between two data points                         |
| IQR                  | Calculates the difference between Q3 and Q1                      |
| Boxplot              | Visualizes data distribution and outliers                        |
| Lower Bound          | Q1 - 1.5 × IQR                                                   |
| Upper Bound          | Q3 + 1.5 × IQR                                                   |

## 💡 Key Learnings

1. Learned how to calculate percentiles and quartiles for even and odd datasets.
2. Understood the importance of sorting data before manual quartile calculations.
3. Practiced calculating percentiles using NumPy.
4. Understood how linear interpolation works in percentile calculations.
5. Learned how to calculate the Interquartile Range (IQR).
6. Created boxplots using Matplotlib to understand data distribution.
7. Learned how to identify lower and upper outliers using the 1.5 × IQR rule.
8. Understood the difference between mild and extreme outliers.

## 📁 Project Structure


Percentiles-and-IQR
│
└── Percentiles.ipynb
```

## 🚀 Future Improvements

- Practice percentile calculations on real-world datasets.
- Compare different NumPy percentile methods.
- Explore outlier detection using other statistical techniques.
- Apply IQR analysis during Exploratory Data Analysis (EDA).