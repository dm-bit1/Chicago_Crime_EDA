This projects contains an Exploratory Data Analysis of the Chicago Crime Database, Chicago Sex Offenders Database.
The Jupyter Notebook file (main.ipynb) shows the outputs of every visualization and codes ran.
The file shows numerous visualizations which are used to gain insights from the data.
The next step is to use machine learning for a regression task to predict the number of crimes in Chicago's wards in PyTorch 2.5.1 (with TorchInductor). 
No GPU acceleration will be used due to the small nature of the project.
This will be done using a neural network or a more simple model.
The technical requirements are below.

The version of Python used is 3.12.8.

The Jupyter Notebook version is below: 
Selected Jupyter core packages...
IPython          : 8.12.3
ipykernel        : 6.29.5
ipywidgets       : 7.8.1
jupyter_client   : 8.6.0
jupyter_core     : 5.7.2
jupyter_server   : 2.14.1
jupyterlab       : 4.2.5
nbclient         : 0.8.0
nbconvert        : 7.16.4
nbformat         : 5.10.4
notebook         : 7.2.2
qtconsole        : 5.6.0
traitlets        : 5.14.3

The libraries used so far can be downloaded from requirements.txt by running the command
"pip install -r requirements.txt" in a shell.

Exploratory Data Analysis And Methodology Notes

Data Source
The Jupyter Notebook file contains an exploratory data analysis (ERD) on Chicago's crime databases. There are two main data sources: 1. City of Chicago's Crime Database which is a qualitive dataset. 2. The Chicago Sex Offender Database which is a qualitative dataset.
The API endpoints for the 2 data sources are explicitly shown in the notebook.

Data Cleaning
The method of cleaning, i.e. imputation, I used is described in the notebook. It clearly states what column was null and how it was replaced.

Univariate Data Analysis
There are numerous plots included in the notebook. For example, one bar plot shows the 10 blocks in Chicago with the most sex offenders. There is also a pie chart which displays the sex offenders by gender (male or female).
Another shows a box plot of sex offenders by age. It shows the interquartile range, median value, whisker values, and outliers.
There is a bar plot with red bars that shows the crimes in each of Chicago's wards within a specified time interval.
There is a red bar plot with redbars that shows the distribution of crimes across all of Chicago's wards.
There's a multi-color pie plot that shows the distribution of crimes in Chicago for all of it's wards.

Bivariate Data Analysis
The notebook contains a box plot that shows ages of sex offenders by gender. It shows the interquartile range, median value, whisker values, outliers for the genders.

Descriptive Statistics
Shown in line 96 and included the ages of sex offenders.
The mean age in years is 49.8, the standard deviation is 12.71, minimum is 20, maximum is 95.
This is described in a cell with more detail.

Machine Learning
One way to accomplish a regression task is to use PyTorch 2.5 (with TorchInductor) to do machine learning in order to predict crimes in a particular ward. The model can be trained on historical data and tested against data in 2024 to check performance (model accuracy).

Insights

Note
In reality, the notebook creates more visualizations and explored the data more than the above parameters mentioned. The point of the exploration, e.g. print statements, visualizations, was to see what data I found meaningful.

Summary