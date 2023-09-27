Please use either Jupyter Notebook or Google Colab to open the Python code file "STAC_Project.ipynb".

stb4849_080321.txt is the raw dataset.

stb4849_080321edited.xlsx is the example dataset after all the preprocessing is done. 

preprocessed_dataset.csv is the output dataset after calling the function getdata1() defined in "STAC Project.ipynb" file. This preprocessed version of the raw dataset is really similar to the example edited dataset with slight variation in the number of observations for each cast number. 


In the "STAC Project.ipynb" file, there are five predefined functions:
1. getdata1(): preprocesses the raw dataset and filters out noisy observations

2. getdata2(): preprocesses the raw dataset without filtering out noisy observations

3. graph_depth(): graphs scan numbers with respect to depth for each cast 

4. graphall(): graphs each variable(column) in the supplied dataset with respect to depth colored by cast numbers

5. summary_statistics(): rounds column 'Depth' in the supplied dataset to the nearest .5 and for each unique station ID, calculates the mean for each column based on different rounded depth values

