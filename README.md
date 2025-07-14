Titanic Exploratory Data Analysis (EDA) Project
Project Overview
This project performs an Exploratory Data Analysis (EDA) on the classic Titanic dataset to uncover patterns and insights related to passenger survival. The goal is to understand factors that influenced who survived the disaster.

Dataset
The dataset used is the "Titanic: Machine Learning from Disaster" dataset from Kaggle. It contains information about passengers, including age, gender, passenger class, and survival status.

Tools & Libraries Used
Python

Pandas (for data manipulation and analysis)

Matplotlib (for basic plotting)

Seaborn (for advanced statistical visualizations)

Jupyter Notebook / Visual Studio Code (for interactive development)

Google Colab (alternative environment for execution)

Key Steps Performed
Data Loading & Initial Inspection: Loaded the train.csv dataset and examined its structure, data types, and initial rows.

Data Cleaning: Handled missing values in 'Age' (imputed with median), 'Embarked' (imputed with mode), and 'Cabin' (created a 'Has_Cabin' feature and then dropped the original column).

Feature Engineering: Created new features like 'FamilySize' and 'IsAlone' to gain richer insights.

Exploratory Data Analysis (EDA): Calculated summary statistics and explored survival rates based on various features like gender, passenger class, age, and family size.

Data Visualization: Created a variety of plots (bar plots, histograms, heatmaps) to visualize patterns and correlations, making the insights easily digestible.

Key Insights
Gender Disparity: Women had a significantly higher survival rate than men, demonstrating the 'women and children first' protocol during the disaster.

Class Influence: Passengers in higher (1st) classes had considerably better survival chances compared to those in 2nd or 3rd class.

Age Matters: Children showed a relatively higher survival rate than adults, suggesting a priority for younger lives.

Family Impact: Passengers traveling in small to medium-sized groups (2-4 people) had better survival rates than those traveling alone or in very large families.

Fare & Survival: There was a positive correlation between the fare paid and survival, likely due to higher fares correlating with better passenger class and potentially better access to lifeboats.

How to View/Run the Project
Download the Dataset: Obtain the train.csv file from the Titanic: Machine Learning from Disaster Kaggle competition page.

Set up your Environment:

Option A (Local - Recommended): Ensure you have Python installed, along with the Pandas, Matplotlib, and Seaborn libraries (pip install pandas matplotlib seaborn). Use Visual Studio Code with the Python and Jupyter extensions, and open your project folder containing train.csv and your Jupyter Notebook.

Option B (Cloud - Google Colab): Go to https://colab.research.google.com/ and create a new notebook. You will need to upload the train.csv file using from google.colab import files; uploaded = files.upload().

Clone this Repository (if viewing from GitHub): git clone [Your GitHub Repo URL] (Replace [Your GitHub Repo URL] with the actual URL of your repository once you upload it).

Open the Notebook: Open the titanic_eda.ipynb file in your chosen environment (VS Code, JupyterLab, or Google Colab).

Run All Cells: Execute all cells in the notebook sequentially to see the full analysis, outputs, and visualizations. In Jupyter/Colab, you can typically do this via Cell -> Run All. In VS Code, look for a "Run All" button at the top of the notebook interface.
