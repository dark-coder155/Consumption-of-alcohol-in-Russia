# Alcohol Consumption Analysis in Russia (2017-2023)

This repository contains data and models for analyzing the consumption of alcoholic beverages in Russia from 2017 to 2023.

## Repository Structure

- **Consumption of alcoholic beverages 2017-2023 (Pivot table).csv**: Pivot table data of alcohol consumption.
- **Consumption of alcoholic beverages in Russia 2017-2023.csv**: Raw data of alcohol consumption.
- **main.ipynb**: Jupyter notebook for data analysis and visualization.
- **models/**: Directory containing the trained machine learning model.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/alcohol-consumption-analysis.git
    cd alcohol-consumption-analysis
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook main.ipynb
    ```

2. Run the cells in the notebook to perform data analysis and visualization.

## Data

The dataset `Consumption of alcoholic beverages in Russia 2017-2023.csv` contains the following columns:

- `Region`: The region in Russia.
- `Year`: The year of data collection.
- `Wine`: Consumption of wine (liters per capita).
- `Beer`: Consumption of beer (liters per capita).
- `Vodka`: Consumption of vodka (liters per capita).
- `Sparkling wine`: Consumption of sparkling wine (liters per capita).
- `Brandy`: Consumption of brandy (liters per capita).
- `Сider`: Consumption of cider (liters per capita).
- `Liqueurs`: Consumption of liqueurs (liters per capita).
- `Total alcohol consumption (in liters of pure alcohol per capita)`: Total alcohol consumption in liters of pure alcohol per capita.

## Analysis

The analysis is performed in the [main.ipynb](http://_vscodecontentref_/3) notebook and includes the following steps:

1. **Import Required Libraries**: Import necessary libraries such as pandas, numpy, matplotlib, and seaborn.
2. **Load the Dataset**: Load the dataset from the CSV file into a pandas DataFrame.
3. **Data Cleaning**: Handle missing values, correct data types, and clean any inconsistencies in the dataset.
4. **Data Overview**: Display the first few rows of the dataset, check the shape, and get an overview of the columns.
5. **Descriptive Statistics**: Generate descriptive statistics for the dataset, including mean, median, standard deviation, etc.
6. **Data Visualization**: Create visualizations such as histograms, box plots, and bar charts to understand the distribution of data.
7. **Correlation Analysis**: Analyze the correlation between different variables using a heatmap.
8. **Regional Analysis**: Perform a detailed analysis of alcohol consumption by region and visualize the findings.
9. **Machine Learning**: Train and evaluate machine learning models to predict alcohol consumption trends.

## Model

The logistic regression model for predicting alcohol consumption trends is stored in the [models](http://_vscodecontentref_/4) directory. The model was trained and tuned using the data provided in the CSV files.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.