# SpaceX Landing Outcome Predictor

This is the applied data science capstone project for the IBM Data Science Professional Certificate program.

### Background
SpaceX is widely known as a leader in the commercial space industry. A hypothetical rival company would like the compete with SpaceX. SpaceX advertises Falcon 9 rocket launches on its website with a cost of $62 million; other competing providers cost upwards of $165 million. The savings can be primarily attributed to SpaceX’s reuse of the first stage; the first stage can be reclaimed after a successful landing. Therefore, if we can predict whether the first stage will land, we can determine the cost of the launch.

This project aims to answer the following questions:

- Which factors are useful in determining if the rocket with land successfully?
- Can we predict landing outcomes?
- What machine learning model is the most effective for predicting landing outcomes?

### Prerequisites
To run the files, you should have the following installed on your machine:

- Jupyter Notebook
- Python 3

### Running Project Files
All files other than ```spacex_dash_app.py``` are Jupyter Notebook files (.ipynb). After launching Jupyter Notebook, ensure that a Python 3 kernel is being used. Then, these Jupyter Notebook files can be opened and run. The files include:

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

