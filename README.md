# EDA on Taxi Trip Data

This project performs Exploratory Data Analysis (EDA) on a dataset containing taxi trip data. The analysis involves data cleaning, handling missing values, and encoding categorical data.

## Project Overview

The project follows these main steps:
1. **Data Collection and Analysis**:
    - Load the dataset.
    - Perform exploratory data analysis to understand the data distribution.
2. **Data Preprocessing**:
    - Handle missing values.
    - Encode categorical variables.
3. **Model Training** (if applicable):
    - Train machine learning models if required for further analysis.

## Dependencies

The project requires the following dependencies:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/DarkLord-13/Machine-Learning-01.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Machine-Learning-01
    ```

3. Install the required packages:
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

4. Open the Jupyter Notebook `EDA(taxi_trip_data)_.ipynb` and run the cells to execute the project steps:
    ```sh
    jupyter notebook EDA(taxi_trip_data)_.ipynb
    ```

## Usage

1. **Data Collection and Analysis**:
    - Load the dataset using Pandas.
    - Perform exploratory data analysis to understand the data distribution.

2. **Data Preprocessing**:
    - Handle missing values in the `congestion_surcharge` column.
    - Encode the `store_and_fwd_flag` column from categorical to numerical values.

3. **Model Training** (if applicable):
    - Train machine learning models using Scikit-learn if required for further analysis.

## Results

The analysis provides insights into the taxi trip data, including handling of missing values and encoding of categorical data. Visualization and statistical summaries are used to understand the data better.

## License

This project is licensed under the MIT License.
