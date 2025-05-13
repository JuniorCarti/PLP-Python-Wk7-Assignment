# PLP-Python-Wk7-Assignment

Here’s a professional and well-structured README for your **Wine Quality Analysis Script**. The content is organized with bullet points and sections for easy reading and comprehension.

---

# 📊 Wine Quality Analysis Script

## 📑 **Project Overview**

This script performs a comprehensive analysis of **wine quality data** from the UCI repository. It analyzes both red and white wine datasets to extract key insights, visualize patterns, and compare features.
The analysis covers:

* 📂 Data Exploration
* 📊 Statistical Analysis
* 📈 Visualization of Key Insights

---

## 🛠️ **Requirements**

To run this script, you need the following:

* **Python** (version 3.6+)
* Libraries:

  * `pandas`
  * `matplotlib`
* Wine quality datasets (CSV files) in your working directory:

  * `winequality-red.csv`
  * `winequality-white.csv`

---

## 🚀 **Script Structure**

The script is divided into three main functions:

### 1. **Data Loading (`load_wine_data`)**

* Loads the red and white wine datasets from local CSV files.
* Adds a `type` column to differentiate red and white wines.
* Combines both datasets into a single DataFrame.
* Handles missing file errors gracefully.

### 2. **Data Analysis (`analyze_wine_data`)**

The analysis pipeline includes:

* **Data Exploration:**

  * Prints dataset shape, sample data, data types, and checks for missing values.
* **Statistical Analysis:**

  * Provides basic statistics (mean, median, standard deviation).
  * Compares wine quality by type.
  * Displays top correlations with wine quality.
* **Visualization:**

  * Generates plots to visualize relationships and patterns:

    * Alcohol content by quality
    * Quality score distribution
    * Average alcohol content by wine type
    * Alcohol vs. density (scatter plot)
  * Saves the visualizations as `wine_analysis.png`.

### 3. **Main Execution (`main`)**

* Calls the data loading function.
* Runs the analysis if the data is successfully loaded.

---

## 📊 **Visualizations**

The script generates the following plots for deeper insight:

* **Alcohol Content by Quality:** Line plot showing how alcohol percentage varies by quality score.
* **Quality Score Distribution:** Bar plot illustrating the frequency of each quality rating.
* **Average Alcohol by Wine Type:** Bar plot comparing alcohol content between red and white wines.
* **Alcohol vs. Density:** Scatter plot to observe the correlation between alcohol content and density, colored by wine type.

---

## 📝 **Usage Instructions**

1. Ensure you have the required CSV files in your working directory.
2. Install necessary libraries:

   ```
   pip install pandas matplotlib
   ```
3. Run the script:

   ```
   python wine_quality_analysis.py
   ```
4. View the output in the console and visualizations saved as `wine_analysis.png`.

---

## ✅ **Expected Output**

* Console outputs include dataset statistics, correlation data, and insights.
* The image file `wine_analysis.png` with all generated visualizations.

---

## 💡 **Notes**

* The script handles file loading errors gracefully, prompting you to place the CSV files in the correct location if not found.
* Adjustments can be made to visualization parameters directly within the script.

---

Here’s the updated **Project Files** section including the output file as well:

---

## 📂 **Project Files**

* `wine_quality_analysis.py` — Python script for data loading, analysis, and visualization
* `data/` — Directory containing wine quality datasets:

  * `winequality-red.csv` — Red wine data
  * `winequality-white.csv` — White wine data
  * `winequality.names` — Metadata for wine quality datasets
* `output/` — Directory containing generated outputs:

  * `wine_output_analysis.png` — Generated plot from data analysis

---

---

## 📝 **License**

This project is open-source and available under the MIT License.

---

