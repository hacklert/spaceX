# SpaceX Landing Outcome Predictor

This is the applied data science capstone project for the IBM Data Science Professional Certificate program.

### Background
SpaceX is widely known as a leader in the commercial space industry. A hypothetical rival company would like the compete with SpaceX. SpaceX advertises Falcon 9 rocket launches on its website with a cost of $62 million; other competing providers cost upwards of $165 million. The savings can be primarily attributed to SpaceX’s reuse of the first stage; the first stage can be reclaimed after a successful landing. Therefore, if we can predict whether the first stage will land, we can determine the cost of the launch. This scenario is treated as a binary classification problem where the goal is to classify a rocket's landing outcome as success or failure based on the other features of the launch.

This project aims to answer the following questions:

- Which factors are useful in determining if the rocket with land successfully?
- Can we predict landing outcomes?
- What machine learning model is the most effective for predicting landing outcomes?

A presentation-style report is provided for this project that details methodologies, insights gained through exploratory data analysis (EDA), and results of predictive analysis. This report can be found in the file named ```spacex-report.pdf```.

### Prerequisites
To run the files, you should have the following installed on your machine:

- Jupyter Notebook
- Python 3

### Running Project Files
All files other than ```spacex_dash_app.py``` are Jupyter Notebook files (.ipynb). After launching Jupyter Notebook, ensure that a Python 3 kernel is being used. Then, these Jupyter Notebook files can be opened and run.

To launch the interactive dashboard, perform the following steps:

1. Install required Python libraries by running the command:
   ```
   pip install pandas dash
   ```
2. Run the Python file with the command:
   ```
   python spacex_dash_app.py
   ```
3. Open a browser and access the dashboard at http://127.0.0.1:8050

### Overview of Methodologies

#### Data Collection
Data is collected directly from SpaceX via the SpaceX REST API (data-collection-api.ipynb) and from the SpaceX Falcon9 Launches Wikipedia page via web scraping (data-collection-webscraping.ipynb).

#### Data Wrangling
Data is cleaned and shaped to perform exploratory data analysis and predictive analysis (data-wrangling.ipynb).

#### Exploratory Data Analysis
EDA is performed on data using SQL (eda-sql.ipynb), visualizations (eda-visualizations.ipynb), and interactive maps (interactive-maps-folium.ipynb) to gain insights about the features of the dataset, relationships between the features, and which features are correlated with the target landing outcome variable.

#### Interactive Dashboard
An interactive dashboard was created with Plotly Dash to further visualize relationships between various features in the dataset and landing outcomes with customizable parameters (spacex_dash_app.py).

#### Predictive Analysis
Predictive analysis was applied to the classification problem to see if landing outcomes can be accurately predicted based on other features. Four different machine learning models were trained and the performance of the models was evaluated and compared (classification-predictive-analysis.ipynb).
