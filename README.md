# Clustering_economic_indicators
Code is part of GA work. The goal of “Clustering1.ipynb” and “Clustering2.ipynb” was to look at economic indicators to see if there was any patterns or splits in the data that could be helpful for the model we were trying to create. 

 “Clustering1.ipynb” started out with trying to cluster all economic indicators by percent change and then raw numbers. No real patterns or splits in the data were seen. Next, only one indicator “GDP” was clustered and patterns and splits in the data were seen. 

“Clustering2.ipynb” is just clustering other economic indicators by themselves. Examples of indicators were ”Non Farm Payroll” and “university of Michigan Confidence”. Results showed patterns and splits in the data that were useful for the project. 

“rus_model.ipynb” is code for Markov Regression models used for gaining more information on economic indicators. Using the coefficients in conjunction with the recession dataset showed a great deal of information about the economic indicators. Only a few of the indicators where used in Markov Regressions. Others were tested to see if the data was stationary, which they failed to reject the null which pointed to them being non-stationary. Methods were used to make the data stationary, but results didn’t give an useful information. Only useful results are shown in the notebook

“rules_and_clustering.ipynb” is code that adds on to the code in “Clustering2.ipynb”.  The first part of the notebook is the same as “Clustering2.ipynb”, but the second part shows how the rules were created and how the rules were tested to see how accurate they were. 

“Index_eda.ipynb” is code that looks at all of the indices and how the reacted in times of recession. 


