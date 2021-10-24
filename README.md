# SocialMediaViz_notebooks
Python Notebooks containing work related to the CyberGIS Center Social Media and Viz team.
Notebooks: 
Count_Visits_Demo_Notebook.ipynb - By Ben Liebersohn
Takes in an existing dataset (such as Twitter data found on Keeling) and runs through each user, counting how many times they visit a place. The output is how many visits each place gets. This is now depricated and should not be run on large datasets, because it is compute intensive. The current version is using Spark, and is much faster. It is maintained by Furqan Baig. 
Interactive_Laborforce_participation.ipynb - By Ben Liebersohn
This copies data from the US Census Bureau website, modifies the data to get a laborforce participation rate in 2018 in the US by counties. 
The data is copied from the Census bureau using the Python library censusdata.
Details on how this can be used are in the notebook.
