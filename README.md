# Understanding the Factors Influencing English Premier League Match Outcomes

## Introduction

This project involves data processing, scraping football datasets from [football-data.co.uk](http://football-data.co.uk), and performing data analysis and visualization. The goal is to understand the factors influencing the English Premier League match outcomes.

## Prerequisites

Ensure you have Python installed (preferably version 3.8 or later).

## Setup Instructions

### 1. Create a virtual environment:

```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

### 2. Install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook:

```bash
jupyter notebook
```

## Files Included

* `premier-league-eda.ipynb`: The Jupyter Notebook containing the analysis.
* `requirements.txt`: A file listing the required packages.
* `premier-league.csv`: A sample of the dataset used in the analysis.
* `README.md`: This file with instructions.
* `premier-league-dataset-notes.txt`: Description of the variables of the dataset.

## Data

The dataset used in this project is sourced from football-data.co.uk. It includes various statistics and results from football matches.

## Running the Analysis

1. Open `premier-league-eda.ipynb` in Jupyter Notebook.
2. Follow the steps in the notebook to replicate the analysis. Note that you can use the scraper in the notebook to get the data from football-data.co.uk, or you can uncomment and load the attached CSV via pandas. By default, `premier-league-eda.ipynb` utilizes the scraper to get the dataset.
3. Review the results and conclusions in the final sections of the notebook.

## License

© 2024 Goldsmiths, University of London. This document is part of an academic coursework project and is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0). You may share this work, but please provide appropriate credit, and do not use it for commercial purposes or create derivative works.
