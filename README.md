# Iris Dataset EDA

## Project Overview
This project provides a detailed analysis of the Iris dataset using Python. The Iris dataset is a classic dataset in the field of machine learning and statistics, containing measurements of iris flowers from three different species: Iris-setosa, Iris-versicolor, and Iris-virginica.

## Dataset Description
The Iris dataset consists of 150 samples, each with the following features:
- Sepal length
- Sepal width
- Petal length
- Petal width
- Species

## Project Structure
- `Iris-Dataset-EDA-using-Python.ipynb`: Jupyter Notebook containing the analysis code.
- `Iris-Dataset-EDA-using-Python.pdf`: PDF version of the analysis.
- `README.md`: Project documentation.

## Steps Performed
### Data Extraction and Loading
- Extracted the dataset from a zip file.
- Loaded the dataset into a Pandas DataFrame.

### Data Cleaning
- Checked for missing values.
- Ensured column names are in lowercase.

### Feature Engineering
- Added new columns: `sepal_area` and `petal_area`.
- Normalized the feature values.

### Statistical Analysis
- Calculated summary statistics.
- Grouped data by species and calculated mean, median, and standard deviation.

### Data Visualization
- Created histograms to show the distribution of sepal length by species.
- Plotted scatter plots of sepal length vs. sepal width.
- Generated a heatmap to visualize the correlation matrix.
- Created a pie chart to show the proportion of each species.

### Filtering and Sorting
- Identified the top 10 rows with the highest sepal area.
- Filtered the dataset to include rows where petal length is greater than the median petal length.

## Installation
Clone the repository:
```sh
git clone https://github.com/Yashvendra09/Iris-Dataset-EDA-using-Python.git
