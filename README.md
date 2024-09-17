# Data Visualization with Iris Dataset using Matplotlib and Seaborn

This repository provides several visualizations of the famous **Iris Dataset**, using **Matplotlib** and **Seaborn** libraries in Python. The goal is to demonstrate statistical summaries and relationships between features using various plotting techniques.

## Visualizations Included

1. **General Statistical Summary**:
   - Displays pairwise relationships between variables such as sepal length, sepal width, petal length, and petal width using Seaborn’s `pairplot`.
   - Shows summary statistics using Pandas' `describe()` method.

2. **Species Frequency Pie Chart**:
   - A pie chart representing the proportion of each species (Setosa, Versicolor, Virginica) in the dataset.

3. **Sepal Length vs Sepal Width**:
   - A scatter plot to analyze the relationship between sepal length and sepal width.

4. **Distribution of Sepal and Petal Features**:
   - Histograms and KDE plots to visualize the distribution of sepal and petal lengths and widths.

5. **Jointplot of Sepal Length vs Sepal Width**:
   - Combines a scatter plot with histograms showing the distribution of sepal length and width.

6. **KDE Plot for Setosa Species**:
   - Kernel Density Estimate plots for sepal and petal features of the Setosa species.

## Installation

To run the code, you'll need the following dependencies:

```bash
pip install matplotlib seaborn pandas
