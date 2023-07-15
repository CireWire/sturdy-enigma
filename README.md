# Manga Data Analysis

This Jupyter Notebook contains Python code for analyzing data related to best-selling manga. The analysis includes identifying the top 10 longest-running manga series, visualizing manga volumes over the years, and applying K-means clustering to categorize manga series based on the number of collected volumes.

## Dataset

The dataset used for this analysis is stored in a CSV file named `best-selling-manga.csv`. The dataset contains the following columns:

- `Manga series`: Name of the manga series.
- `Approximate sales in million(s)`: Approximate sales of the manga series in millions.
- `Serialized`: Range of years when the manga series was serialized, including start and end years.
- `No. of collected volumes`: Number of volumes collected for each manga series.

## Requirements

To run the code, you need the following libraries installed:

- pandas
- matplotlib
- scikit-learn

You can install the required libraries using the following command:

```python
pip install pandas matplotlib scikit-learn
```

## How to Use

1. Clone this repository to your local machine or download the ZIP file.
2. Upload the `best-selling-manga.csv` file to the same directory as this Jupyter Notebook.
3. Ensure you have Python installed on your machine or use a cloud-based Jupyter environment.
4. Install the required libraries using the command mentioned in the "Requirements" section.
5. Execute the code cells to perform the manga data analysis.

## Code Overview

This Jupyter Notebook contains the following code sections:

1. Data Loading and Preprocessing: Load the manga data from the CSV file, preprocess the data to handle missing values, and convert data types.
2. Top 10 Longest-Running Manga Series: Identify and display the top 10 longest-running manga series and their durations in years.
3. Time Series Analysis: Create a time series plot of manga volumes over the years and visualize the trends.
4. K-means Clustering Analysis: Apply K-means clustering to manga volumes and visualize the clusters based on the number of collected volumes.

## Results

The analysis results, insights, and interpretations are presented within this Jupyter Notebook. The outputs of visualizations, such as time series plots and bar charts, are displayed inline.

## Conclusion

This Jupyter Notebook provides valuable insights into the top 10 longest-running manga series, manga volumes' progression over the years, and manga clustering based on the number of collected volumes. The analysis can benefit manga publishers, distributors, and enthusiasts in making informed decisions related to marketing, inventory management, and manga series exploration.

## License

This code is released under the MIT License. Feel free to use and modify the code according to your needs.

## Author

This code was created by CireWire.
