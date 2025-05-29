# Wine Quality Analysis

## Overview

This project analyzes wine quality using datasets for red and white wines. It explores how physicochemical properties such as acidity, sugar content, alcohol, and pH relate to wine quality ratings. Through data visualization and statistical exploration, the project aims to identify key factors influencing perceived wine quality.

## Datasets

The project uses two datasets:

- `winequality-red.csv`: Red wine samples with their chemical attributes.
- `winequality-white.csv`: White wine samples with similar features.

Both datasets originate from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality).

## Project Structure

```
Project-2/
├── EDA with MPL and SB SpikeEx.ipynb
├── wine_plot_selection.ipynb
├── winequality-red.csv
├── winequality-white.csv
└── .gitignore
```

- `EDA with MPL and SB SpikeEx.ipynb`: Exploratory Data Analysis using Matplotlib and Seaborn.
- `wine_plot_selection.ipynb`: Focused on selecting the most relevant visualizations for reporting.
- CSV files: Contain the datasets used in the analysis.

## Analysis and Methodology

The notebooks include:

- **Descriptive Statistics**: Means, distributions, and outliers for key variables.
- **Correlation Analysis**: Heatmaps and correlation matrices to detect feature relationships.
- **Data Visualization**: Histograms, box plots, scatterplots, and violin plots.
- **Quality Comparison**: Differences between red and white wines, highlighting features most strongly influencing wine quality.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.7 or higher
- Jupyter Notebook
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Jul-9579/Project-2.git
   cd Project-2
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` doesn't exist, generate it with:

   ```bash
   pip freeze > requirements.txt
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Then open the notebooks from the project folder.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with improvements.

## License

This project is licensed under the MIT License.
