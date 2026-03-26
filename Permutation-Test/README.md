# Permutation Test

This project applies statistical inference using permutation testing to evaluate whether beer consumption affects mosquito attraction.

##  Files
- PermutationTest.ipynb → Jupyter Notebook with full analysis and simulation
- PermutationTest.pdf → Final report with visualizations and results

## Problem Overview

The goal of this study is to determine whether there is a statistically significant difference in the number of mosquitoes attracted to individuals who consumed beer versus water.

##  Key Analysis

### 1. Descriptive Statistics
- Beer group mean ≈ 23.6
- Water group mean ≈ 19.2
- Observed difference ≈ 4.38 mosquitoes

### 2. Data Visualization
- Boxplots show higher mosquito attraction in the beer group
- Minimal overlap between distributions

### 3. Permutation Test
- 50,000 simulations performed
- Random shuffling used to simulate null hypothesis

### 4. Hypothesis Testing
- p-value ≈ 0.0005
- Result: Reject the null hypothesis

##  Conclusion

The probability of observing such a difference by chance is extremely low (< 0.1%), indicating a statistically significant association between beer consumption and increased mosquito attraction.

##  Tools Used
- Python
- Pandas
- NumPy
- Matplotlib

---
**Author:** Darrah Borinaga
