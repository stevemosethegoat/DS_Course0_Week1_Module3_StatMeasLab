# Data Analysis: Central Tendency & Dispersion

## 📖 Overview
This repository documents my learning on how to calculate and visualize **central tendency** and **dispersion** in Python using libraries like **NumPy**, **Pandas**, and **Matplotlib**.

---

## 🔢 Central Tendency
Central tendency describes the "center" of a dataset.

### 1. Calculate Central Tendency
```python
import numpy as np
import pandas as pd

data = [10, 20, 30, 40, 50]
series = pd.Series(data)

mean = series.mean()      # Average
median = series.median()  # Middle value
mode = series.mode()[0]   # Most frequent value
