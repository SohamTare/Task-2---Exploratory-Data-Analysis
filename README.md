# Task-2---Exploratory-Data-Analysis
Exploratory Data Analysis of Dataset

## 📊 Exploratory Data Analysis (Day 2) [27-05-2025]

Today’s goal was to understand the dataset in-depth using statistical analysis and data visualization. This included identifying trends, distributions, outliers, and relationships between features.

### ✅ Tasks Performed

1. **Generated Summary Statistics**
   - Used `describe()` and `median()` to get mean, median, standard deviation, min, max, etc.
   - Verified data types and null value counts.

2. **Visualized Distributions**
   - Created **histograms** to analyze value distributions of numerical features.
   - Used **boxplots** to detect and visualize outliers.

3. **Analyzed Feature Relationships**
   - Plotted **pairplots** for first few numerical features.
   - Generated a **correlation heatmap** using Seaborn.

4. **Detected Patterns & Trends**
   - Identified highly correlated features.
   - Checked skewness to spot non-Gaussian distributions.
   - Visualized remaining outliers after preprocessing.

5. **Inferences Drawn**
   - Most numerical features are not normally distributed (skewed).
   - Several features exhibit strong correlation, useful for feature selection.
   - Presence of right-skewed variables suggests a log-transform might help.
   - Outliers were mostly cleaned but some residuals were visualized again.

### 🧠 Key Libraries Used
- `pandas`, `numpy` for data analysis
- `matplotlib.pyplot`, `seaborn` for visualization

---



