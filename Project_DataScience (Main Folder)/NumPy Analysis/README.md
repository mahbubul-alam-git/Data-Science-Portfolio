# NumPy & Data Analysis Foundations 🚀

This repository contains a Jupyter Notebook (`numpy.ipynb`) demonstrating essential data manipulation, preprocessing, and linear algebra techniques using Python, NumPy, and Pandas. 

The code serves as a practical toolkit for handling structured data and image matrices, bridging the gap between raw datasets and machine learning readiness.



## 📊 Projects & Concepts Covered

### 1. MNIST Image Preprocessing
* **Normalization & Standardization:** Scaled pixel values to `[0, 1]` and applied Z-score standardization `(x - μ) / σ`.
* **Dimensionality Manipulation:** Reshaped flattened 1D arrays (784 pixels) back into 2D spatial matrices (28x28 images) for visualization.
* **Boolean Masking (Binarization):** Used vectorization and `np.where` to threshold pixel intensities, converting grayscale images into binary masks.
* **Filtering:** Applied masks to efficiently isolate specific targets (e.g., extracting all '7's from the dataset).

### 2. Feature Engineering (Ink Density Analysis)
* Integrated NumPy arrays with Pandas DataFrames.
* Calculated the L1 Norm (row-wise sum) of pixel values to represent the "ink amount" for each digit.
* Utilized the "Split-Apply-Combine" pattern (`groupby`) to identify which digits mathematically require the most ink.

### 3. Exploratory Data Analysis (EDA) - Titanic Dataset
* Extracted the `Age` and `Fare` features from the cleaned Titanic dataset.
* Calculated the **Pearson Correlation Coefficient** using `np.corrcoef` to analyze the linear relationship between passenger age and ticket price.

### 4. Linear Algebra & Array Operations
* **Matrix Multiplication:** Implemented dot products using both `np.dot()` and the modern `@` operator.
* **Array Stacking:** Combined matrices structurally using `np.hstack` (column-wise) and `np.vstack` (row-wise).
* **Vector Operations:** Calculated dot products between random image vectors to measure baseline similarity.

## 🛠️ Tech Stack
* **Python 3**
* **NumPy:** Core library for high-performance multidimensional array computing.
* **Pandas:** Used for tabular data integration and statistical aggregation.
* **Jupyter Notebook:** Interactive development environment.

## 🚀 How to Use
1. Clone the repository to your local machine.
2. Ensure you have `numpy` and `pandas` installed: `pip install numpy pandas`.
3. Download `mnist_test.csv` and `Titanic-Dataset-Cleaned.csv` into this directory.
4. Open `numpy.ipynb` in Jupyter Notebook and run the cells sequentially.
