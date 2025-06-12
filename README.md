# datafun-06-eda

Objective
Perform and publish a custom EDA project to demonstrate skills with Jupyter, pandas, Seaborn and popular tools for data analytics. The notebook should tell a data story and visually present findings in a clear and engaging manner.


Packages used:
jupyterlab #: Enables Jupyter notebooks.
pandas #Handles data manipulation and analysis, focusing on structured (tabular/panel) data.
pyarrow #Required by pandas; facilitates interaction between pandas and the Arrow format.
matplotlib #Basic tools for plotting and visualizing data.
seaborn #Simplifies complex visualizations and statistical plots, built on matplotlib.


It is also recommended to use a github command streamline program, like gitquick.ps1, and to ativate a virtual environment.

Contents of gitquick.ps1:
#This is a powershell script for easily running the git commands to update your repo

param ([string]$msg = "")

if ($msg -eq "") {
    $msg = "Updated on $(Get-Date -Format 'yyyy-MM-dd')"
}

git add .
git commit -m "$msg"
git push origin main




For this project, we use the diamonds dataset built in to seaborn: https://github.com/mwaskom/seaborn-data/blob/master/diamonds.csv

The columns of this dataset are: "carat","cut","color","clarity","depth","table","price","x","y","z"
