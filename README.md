# Graphs-Generation
Created a graph function that takes any dataset and create a boxplot and a histogram for numerical variables and a barplot for categorical variables and save them as PNG files in a specified repository. If no repository is specified then by default the graphs get stored in the working directory. The functions also give an additional argument to the user to choose a list of columns. If no list of columns is given the default setting must choose all the columns of the dataset.

Function Structure:

graphs(data, cols, directory)

data: the data frame of interest

cols: the columns of interest (default: the list of all the columns)

directory: a link to a location in the system (default: the current working directory)
