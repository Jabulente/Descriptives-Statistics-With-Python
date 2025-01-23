# Descriptive Statistics With Python 


This initiative demonstrates the application of descriptive statistics in Python, focusing on the analysis of central tendency, variability, and distribution within datasets. By leveraging Python's powerful libraries, including **pandas**, **numpy**, and **matplotlib**, it highlights methodologies for effectively summarizing, interpreting, and visualizing data. These techniques provide clear and actionable insights, establishing a strong foundation for advanced data analysis and informed decision-making.

---

## **Objectives**

### **Main Objective**
To demonstrate the use of Python for performing descriptive statistics, presenting key metrics and visualizations for effective data analysis.

### **Specific Objectives**
1. **Summarizing Data:** Compute measures of central tendency (mean, median, mode) and variability (standard deviation, variance, and range) using Python libraries.
2. **Analyzing Data Distribution:** Visualize data distribution with histograms, box plots, and density plots to identify patterns and outliers.

---

## **Key Features**
- Calculation of statistical metrics (mean, median, mode, variance, standard deviation, etc.).
- Data visualization using plots to understand distributions and detect outliers.

---

## **Technologies and Tools Used**
- **Python**: Core programming language.
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations and calculations.
- **matplotlib**: For basic data visualization.
- **seaborn**: For advanced and aesthetically pleasing visualizations.

---

## **Project Workflow**
1. **Dataset Loading:** Import and clean the dataset to ensure it is ready for analysis.
2. **Statistical Computation:** Compute descriptive statistics like mean, median, mode, variance, and standard deviation.
3. **Data Visualization:** Generate visualizations such as histograms, box plots, and scatter plots to examine data patterns.
---

## **Installation and Setup**

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd descriptive-statistics-python
   ```

3. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. Run the analysis script:
   ```bash
   python descriptive_statistics.py
   ```

---

## **Sample Dataset**
This project uses a sample dataset (e.g., `data.csv`) included in the repository. You can replace it with your own dataset by ensuring the file format is compatible (CSV, Excel, etc.).

---

## **Outputs**
- Summary statistics tables.

  **Table 1.0: Overall Statistic Description of The Datasets**

|                      |   count |     mean |      std |      min |      25% |      50% |     75% |     max |
|:---------------------|--------:|---------:|---------:|---------:|---------:|---------:|--------:|--------:|
| Plant height         |     976 | 34.3736  |  6.85383 | 16.1779  | 30.4259  | 35.2419  | 39.3591 | 47.065  |
| Leaf number          |     976 |  6.71371 |  5.71252 | -9.925   |  3.15644 |  7.47847 | 10.5814 | 19.3744 |
| Fresh biomass (g)    |     976 | 53.1914  | 13.0124  | 27.014   | 45.0456  | 49.0427  | 61.3233 | 95.6688 |
| Dry biomass (g)      |     976 |  9.29878 |  7.09435 | -9.33507 |  4.76895 |  9.20062 | 13.9682 | 27.5687 |
| Yield (Tones per ha) |     976 | 11.3076  |  3.26881 |  4.77884 |  8.79962 | 11.2266  | 13.6181 | 19.3721 |

**Table 1.2: ingle-variable Statistics Descriptions**

| Fertilizer   |   N |    Mean |     SD |     SE |   95% Conf. |   Interval |
|:-------------|----:|--------:|-------:|-------:|------------:|-----------:|
| Fertilizer A | 277 | 34.4453 | 9.526  | 0.5724 |     33.3186 |    35.5721 |
| Fertilizer B | 245 | 32.435  | 5.3078 | 0.3391 |     31.767  |    33.1029 |
| Fertilizer C | 454 | 35.376  | 5.2535 | 0.2466 |     34.8915 |    35.8605 |


**Table 1.3: Distribution Statistics for Numerical Variables**

|    | Parameter            |     Mean |   Median |     Mode |   Standard Deviation |   Variance |   Range |   Skewness |   Kurtosis |
|---:|:---------------------|---------:|---------:|---------:|---------------------:|-----------:|--------:|-----------:|-----------:|
|  0 | Plant height         | 34.3736  | 35.2419  | 26.975   |              6.85383 |    46.9749 | 30.8871 | -0.586229  | -0.156049  |
|  1 | Leaf number          |  6.71371 |  7.47847 |  6.05    |              5.71252 |    32.6329 | 29.2994 | -0.459134  | -0.0895406 |
|  2 | Fresh biomass (g)    | 53.1914  | 49.0427  | 38.014   |             13.0124  |   169.323  | 68.6548 |  1.1564    |  1.2007    |
|  3 | Dry biomass (g)      |  9.29878 |  9.20062 |  6.814   |              7.09435 |    50.3298 | 36.9037 | -0.0422521 | -0.298664  |
|  4 | Yield (Tones per ha) | 11.3076  | 11.2266  |  6.51579 |              3.26881 |    10.6851 | 14.5933 |  0.19103   | -0.674191  |

**Table 1.4: Group-wise Distribution Statistics Calculation for Numerical Variables**

|    | Fertilizer   | Plant height       | Leaf number        | Fresh biomass (g)   | Dry biomass (g)     | Yield (Tones per ha)   |
|---:|:-------------|:-------------------|:-------------------|:--------------------|:--------------------|:-----------------------|
|  0 | Fertilizer A | 34.45 ± 0.57       | 5.27 ± 0.33        | 54.08 ± 0.54        | 11.04 ± 0.33        | 11.57 ± 0.09           |
|  1 | Fertilizer B | 32.43 ± 0.34       | 6.23 ± 0.41        | 54.44 ± 0.59        | 5.70 ± 0.41         | 11.61 ± 0.15           |
|  2 | Fertilizer C | 35.38 ± 0.25       | 7.86 ± 0.25        | 51.98 ± 0.77        | 10.18 ± 0.36        | 10.99 ± 0.20           |
|  3 | Grand Mean   | 34.3735            | 6.7137084971618375 | 53.191431433847924  | 9.298781315081923   | 11.30760038145973      |
|  4 | SEM          | 0.219385           | 0.1828533336169771 | 0.41651699820985405 | 0.22708455140943284 | 0.10463207744597673    |
|  5 | %CV          | 19.93922          | 85.08741124069812  | 24.46335180374966   | 76.29331130402244   | 28.908083815971736     |



**Visualizations (e.g., histograms, box plots).**

- **Email:** [Your Email Address](Visualization-Figures/Jabulente2025.png).

---

## **Contributing**
Contributions to enhance the project are welcome! Feel free to:
- Report issues.
- Submit pull requests with improvements or additional features.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## **Contact**
For questions or suggestions, feel free to reach out:
- **Name:** Jabulente
- **Email:** [Your Email Address]
- **LinkedIn:** [Your LinkedIn Profile URL]

---

## **Acknowledgments**
Special thanks to the open-source community and Python library developers for their contributions to data analysis tools.

