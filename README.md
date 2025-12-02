# Global Education Systems Analysis

This project is a complete solution for educational data analysis, including the collection, processing, visualization, and presentation of education-related data from around the world.
## Project Objectives

-Collect and standardize educational data from various sources (UNESCO, World Bank, GeoNames)
-Analyze the impact of free education policies on the duration of studies
-Evaluate school retention rates across different regions
-Create interactive visualizations for data exploration
## Project Structure

```
.
├── data_collectors/          # Data collection scripts
│   ├── unesco_collector.py   # UNESCO UIS data
│   ├── worldbank_collector.py # World Bank data
├── data_processing/          # Data processing
│   ├── data_cleaner.py       # Data cleaning
│   └── data_merger.py        # Data merging
├── data/                     # Data storage
├── EDA.ipynb                 # Exploratory data analysis notebook
├── dashboard.py              # Interactive Streamlit interface
├── main.py                   # Main entry point
├── config.py                 # Project configuration
└── requirements.txt          # Python dependencies
```

## Prerequisites

Python 3.8 or higher
pip (Python package manager)
## Installation

1-Clone the repository:

Bash
git clone [REPO_URL]
cd Projet-DAjuc

2- Create and activate a virtual environment:

Bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On Unix/MacOS
source venv/bin/activate

3-Install the dependencies:

Bash
pip install -r requirements.txt

## Usage
1. Data Collection and Processing
To run the full data collection and processing pipeline:
Bash
python main.py
2. Data Exploration
For exploratory data analysis, open the Jupyter notebook:
Bash
jupyter notebook EDA.ipynb
4. Interactive Dashboard
To launch the interactive dashboard:
Bash
streamlit run dashboard.py


## Main Features

-**Data Collection:** Automated extraction from UNESCO, World Bank, and GeoNames
-**Processing:** Cleaning, normalization, and merging of data
-**Visualization:** Interactive dashboard built with Streamlit
-**Analysis:** Jupyter notebook for in-depth exploration



