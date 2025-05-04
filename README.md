# Seaborn Visualization Examples with Titanic, Iris, and Tips Datasets

This repository contains a collection of example plots created using the **Seaborn** library in Python. It demonstrates how to visualize and explore classic datasets such as **Iris**, **Titanic**, and **Tips** using different types of plots.

## 📚 Datasets Used

- `tips`: Dataset containing restaurant bill and tipping data.
- `titanic`: Passenger data from the Titanic ship.
- `iris`: Measurements of different species of iris flowers.

These datasets are either built-in with Seaborn or available through `sns.load_dataset()`.

## 📊 Visualizations Included

A variety of plot types are included to showcase Seaborn’s capabilities, such as:

- **Box plots**: Show distribution and outliers.
```python
sns.boxplot(x="day", y="total_bill", data=tips, palette="YlGnBu", hue="sex")

seaborn_examples/
│
├── iris_plots.py
├── titanic_plots.py
├── tips_plots.py
└── README.md
