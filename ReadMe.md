# PySpark Sales Analysis

## Overview
This project is designed to perform sales data analysis using Apache Spark and PySpark. The data includes various sales metrics such as the location of sales, product categories, and order sources (e.g., Swiggy, Zomato). The analysis involves data cleaning, transformation, and visualization to uncover insights and trends.

## Features
- **Data Loading**: Load sales data from CSV files.
- **Data Cleaning**: Handle null values, cast data types, and filter data.
- **Data Transformation**: Aggregate data by various dimensions (e.g., country, product, category).
- **Visualization**: Generate bar plots to visualize sales metrics.
- **Top Sales Analysis**: Identify top-selling countries, products, and order sources.

## Project Structure
```
├── data/
│   └── sales_data.csv.txt       # Example sales data file
│   └── menu.csv.txt       # Example sales data file
├── pyspark project sales analysis.ipynb # Jupyter notebook for the analysis
│  
└── README.md                # Project documentation
```

## Requirements
- Python 3.8 or higher
- Apache Spark 3.5.1
- PySpark
- Pandas
- Matplotlib
- jdk-17

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Isam-tfares/pyspark-sales-analysis.git
   cd pyspark-sales-analysis
   ```

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required Python packages:
   ```bash
   pip install pyspark
   pip install pandas
   ```

4. Ensure that Apache Spark is installed and added to your system's PATH.

## Usage
1. Open the Jupyter notebook `notebook.ipynb` 
2. Follow the steps in the notebook to load, clean, transform, and analyze the sales data.
3. Modify the notebook as needed to perform additional analysis or visualization.

## Data
- The project includes a sample CSV file with sales data in the `data/` directory.
- Replace this file with your own dataset to analyze different sales data.

## Contributions
Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
