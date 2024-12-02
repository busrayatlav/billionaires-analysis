# Billionaires Analysis with Python

## Overview
This project analyzes data on global billionaires from Forbes' 2021 dataset. It explores patterns in their wealth, industries, countries, and sources of income. The analysis provides insights into the business environment and economic trends globally.

---

## Dataset
The dataset contains information about billionaires, including:
- **Name**: Name of the billionaire.
- **NetWorth**: Net worth in billions of USD.
- **Country**: Country of origin.
- **Source**: Source of wealth.
- **Rank**: Global ranking of wealth.
- **Age**: Age of the billionaire.
- **Industry**: Industry associated with wealth creation.

### Source
The dataset is sourced from [Forbes](https://www.forbes.com/) and is available on [Kaggle](https://www.kaggle.com/).

---

## Installation

### Step 1: Clone the Repository
```
git clone https://github.com/yourusername/billionaires-analysis.git
cd billionaires-analysis
```
### Step 2: Install Dependencies
Install the required Python libraries:
```
pip install -r requirements.txt
```

---

## Project Workflow

### 1. Data Preprocessing
- The dataset is loaded and checked for missing values.
- Rows with missing data are removed.
- The `NetWorth` column is cleaned by removing unnecessary symbols (`$`, `B`) and converting it to a numerical format.

### 2. Exploratory Data Analysis (EDA)
- Visualized the top 10 billionaires by their net worth.
- Analyzed the top domains, industries, and countries with the most billionaires.

### 3. Insights
- Found key trends in industries, countries, and wealth sources, highlighting factors that contribute to a strong business environment.

---

## Usage

### Running the Project
1. Open the terminal in the project directory.
2. Run the following script:
   ```
   python billionaires_analysis.py
   ```
3. The script will generate visualizations of the following:
- Top 10 billionaires by net worth.
- Top 5 domains with the most billionaires.
- Top 5 industries with the most billionaires.
- Top 5 countries with the most billionaires.

---

## Results

### Key Findings:
- The **United States** and **China** have the highest number of billionaires, indicating strong business environments.
- The **Technology** and **Fashion & Retail** industries dominate wealth creation.
- Major wealth sources include **Amazon**, **Tesla/SpaceX**, and **LVMH**.

### Example Output:
#### Top 5 Countries with the Most Billionaires:
1. United States
2. China
3. India
4. Germany
5. Russia

---

## Dependencies

- Python 3.7+
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## Future Improvements

- Include time-series data to analyze trends over multiple years.
- Add GDP and economic indicators for richer insights.
- Deploy the project as an interactive dashboard using Streamlit.

---

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions or improvements.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements

- **Dataset**: Sourced from Forbes 2021 data available on Kaggle.
- **Inspiration**: Inspired by Aman Kharwal's article on billionaires analysis.
- **Libraries and Tools**: Built using Python, Pandas, Matplotlib, and Seaborn.

---

## Repository Structure

```
billionaires-analysis/

│

├── billionaires_analysis.py   # Main Python script for the project

├── requirements.txt           # List of required libraries

├── README.md                  # Project documentation

└── LICENSE                    # License file

```







