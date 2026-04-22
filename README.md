# Brazil to Canada Immigration Analysis

## Overview

This project performs an exploratory data analysis (EDA) on immigration data to Canada, with a specific focus on building clear and effective data visualizations using Python.

The main goal is not only to analyze the dataset, but to develop strong skills in visual storytelling — transforming raw data into meaningful insights through well-constructed graphs.

The analysis is conducted in a Jupyter Notebook, where data is cleaned, explored, and visualized step by step.

---

## Objectives

- Practice data visualization using Python plotting libraries
- Understand patterns and trends in immigration data
- Apply data cleaning and preprocessing techniques
- Develop the ability to communicate insights through visual means
- Explore different types of charts and when to use each one

---

## Dataset

The dataset used in this project is:

```
data/imigrantes_canada.csv
```

It contains historical data about immigration to Canada, including:

- Country of origin
- Number of immigrants per year
- Temporal evolution of immigration flows

This dataset allows for time series analysis and comparisons between countries.

---

## Technologies and Libraries

The project was developed using the following technologies:

- Python 3.x
- Pandas → data manipulation and analysis
- Matplotlib → core plotting library
- Seaborn → statistical data visualization and enhanced graph aesthetics

All dependencies are listed in:

```
requirements.txt
```

---

## Project Structure

```
├── data/
│ └── imigrantes_canada.csv
├── notebook/
│ └── 01_main_notebook.ipynb
├── requirements.txt
├── LICENSE
└── README.md
```

- `data/`: Contains the dataset used for analysis
- `notebook/`: Contains the Jupyter Notebook with the full analysis and visualizations
- `requirements.txt`: List of required Python libraries
- `LICENSE`: Project license information
- `README.md`: Project documentation

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/brazil_to_canada_imigration_analisys.git
cd brazil_to_canada_imigration_analisys
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

```bash
jupyter notebook
```

Then open:

```
notebook/01_main_notebook.ipynb
```

---

## Analysis Workflow

The notebook follows a structured data analysis process:

### 1. Data Loading

- Importing the dataset using Pandas
- Initial inspection of structure and columns

### 2. Data Preparation

- Preparing data for visualization

### 3. Data Visualization

Different types of visualizations are used to represent the data, such as:

- Line plots → to show trends over time
- Bar charts → to compare categories
- Boxplot → to analisy the data distribuction

---

## Key Learning Outcomes

- How to transform raw datasets into structured data
- How to choose the appropriate type of chart for each scenario
- How to build readable and informative visualizations
- How to extract insights from visual analysis
- How to structure an end-to-end data analysis workflow

## Where This Project Can Be Applied

The concepts demonstrated here can be applied to:

- Data analysis projects
- Business intelligence dashboards
- Machine learning preprocessing stages
- Academic research
- Data-driven decision making scenarios

## License

This project is licensed under the terms defined in the LICENSE file.
