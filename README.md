Iris Dataset Analysis
This project provides a detailed analysis of the Iris dataset using Python. The Iris dataset is a classic dataset in the field of machine learning and statistics, containing measurements of iris flowers from three different species: Iris-setosa, Iris-versicolor, and Iris-virginica.

Dataset Description
The Iris dataset consists of 150 samples, each with the following features:

Sepal length
Sepal width
Petal length
Petal width
Species
Project Structure
bezdekIris.data: Original dataset file
Index: Index file
iris.data: Processed dataset file
iris.names: File containing descriptions of the dataset features
Steps Performed
Data Extraction and Loading:

Extracted the dataset from a zip file.
Loaded the dataset into a Pandas DataFrame.
Data Cleaning:

Checked for missing values.
Ensured column names are in lowercase.
Feature Engineering:

Added new columns: sepal_area and petal_area.
Normalized the feature values.
Statistical Analysis:

Calculated summary statistics.
Grouped data by species and calculated mean, median, and standard deviation.
Data Visualization:

Created histograms to show the distribution of sepal length by species.
Plotted scatter plots of sepal length vs. sepal width.
Generated a heatmap to visualize the correlation matrix.
Created a pie chart to show the proportion of each species.
Filtering and Sorting:

Identified the top 10 rows with the highest sepal area.
Filtered the dataset to include rows where petal length is greater than the median petal length.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/Yashvendra09/Iris-Dataset-EDA-using-Python.git
Navigate to the project directory:
bash
Copy code
cd iris-dataset-analysis
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
Run the Jupyter Notebook to perform the analysis:
bash
Copy code
jupyter notebook Iris-Dataset-EDA-using-Python.ipynb
Visualizations
Distribution of Sepal Length by Species: A histogram showing the distribution of sepal length for each species.
Sepal Length vs. Sepal Width: A scatter plot illustrating the relationship between sepal length and sepal width, colored by species.
Correlation Matrix: A heatmap showing the correlation between different numerical features.
Species Proportion: A pie chart depicting the proportion of each species in the dataset.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

License
This project is licensed under the MIT License.
