# Matplotlib Data Visualization Portfolio 📊

This repository contains a comprehensive collection of data visualization techniques using **Matplotlib** and **NumPy**. The goal of this project was to master everything from basic plotting to advanced multi-plot layouts and data distribution analysis.

## 🚀 Overview
The project is structured as a single Jupyter Notebook (`matplotlib.ipynb`) that demonstrates:
* **Custom Plot Styling:** Working with colors, markers, and line styles.
* **Mathematical Plotting:** Visualizing functions like $y = x^2$ and sinusoidal modulations.
* **Statistical Visualizations:** Using Histograms and Scatter plots to analyze data distributions.
* **Categorical Data:** Using Bar charts to compare different groups.
* **Advanced Layouts:** Implementing the Object-Oriented (OO) interface with `plt.subplots`.
* **Matrix Visualization:** Displaying images (MNIST style) and Correlation Heatmaps.

---

## 🛠️ Visualizations Included

### 1. Basic & Modulated Line Plots
* **Standard Line:** Customizing markers (`o`, `<`), colors, and grid lines.
* **Oscillation Plot:** Visualizing 15% sinusoidal modulation over a quadratic curve to show fluctuations.

### 2. Multi-Plot Layouts (Subplots)
* Demonstrates the use of `plt.subplots(nrows=1, ncols=2)` to compare different chart types (Line vs. Scatter) side-by-side.
* Uses `tight_layout()` to ensure clean, non-overlapping labels.

### 3. Statistical Analysis
* **Histograms:** Visualizing the frequency distribution of 891 random "Age" samples using a Normal Distribution.
* **Scatter Plots:** Identifying the relationship between "Age" and "Fare" while handling overplotting with `alpha` transparency.

### 4. Categorical & Heatmaps
* **Bar Charts:** Comparing survival counts between genders.
* **Heatmaps:** Creating a Feature Correlation Matrix using the `coolwarm` colormap.
* **Image Display:** Rendering 2D arrays as grayscale images with colorbars and hidden axes.

---

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** * `Matplotlib`: Primary library for 2D visualizations.
    * `NumPy`: Used for data generation and matrix manipulations.

---

## 📈 Key Concepts Learned
* Controlling figure resolution and size using `dpi` and `figsize`.
* Managing axes and ticks using `plt.xticks` and `plt.yticks`.
* Handling "Object-Oriented" vs "Pyplot" interfaces.
* Data normalization and random noise generation for realistic testing.

---

## 📂 How to use
1. Clone the repository.
2. Ensure you have `matplotlib` and `numpy` installed:
   ```bash```
   pip install matplotlib numpy