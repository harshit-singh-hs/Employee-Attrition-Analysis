# Employee Attrition Analysis

This repository contains a Jupyter Notebook for analyzing employee attrition data. The analysis includes data preprocessing, exploratory data analysis (EDA), and visualization to identify key factors influencing employee turnover.

## Dataset
The dataset (`ATTRITION.csv`) contains employee-related attributes such as demographics, job roles, and attrition status.

## Data Checks Performed
- Checking for missing values (No missing values found)
- Checking unique values in each column
- Identifying duplicate rows
- Statistical summary of numerical columns
- Exploring different categories in categorical columns

## Dependencies
The analysis requires the following Python libraries:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
sns.set_theme()
import warnings
warnings.filterwarnings('ignore')
```

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the project folder:
   ```sh
   cd your-repo
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook attrition.ipynb
   ```

## Visualization
The notebook includes various visualizations to better understand attrition trends, including:
- Histograms and distribution plots
- Correlation heatmaps
- Categorical analysis through bar plots

## Contributing
Feel free to fork this repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License.

