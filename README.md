Please use either Jupyter Notebook or Google Colab to open the Python code file "STAC_Project.ipynb".

stb4849_080321.txt is the raw dataset.

stb4849_080321edited.xlsx is the example dataset after all the preprocessing is done. 

preprocessed_dataset.csv is the output dataset after calling the function getdata1() defined in "STAC Project.ipynb" file. This preprocessed version of the raw dataset is similar to the example edited dataset with slight variation in the number of observations for each cast number. 


In the "STAC Project.ipynb" file, there are five predefined functions:
1. getdata1(): preprocesses the raw dataset and filters out noisy observations

2. getdata2(): preprocesses the raw dataset without filtering out noisy observations

3. graph_depth(): graphs scan numbers with respect to depth for each cast 

4. graphall(): graphs each variable(column) in the supplied dataset with respect to depth colored by cast numbers

5. summary_statistics(): rounds column 'Depth' in the supplied dataset to the nearest .5 and for each unique station ID, calculates the mean for each column based on different rounded depth values


Example Outputs:

![Salinity vs  Depth Plot for Each Cast](https://github.com/ZhiruiLi1/Oceanographic_Data_Analysis/assets/90368869/dce7b982-4880-4ca8-90b1-92c3e1fa7163)

![Temperature vs  Depth Plot for Each Cast](https://github.com/ZhiruiLi1/Oceanographic_Data_Analysis/assets/90368869/47a4e514-443a-42ad-a87e-a0fbe12ab620)

![O2 % Saturation vs  Depth Plot for Each Cast](https://github.com/ZhiruiLi1/Oceanographic_Data_Analysis/assets/90368869/ce062eab-77f7-48cf-8665-1096c0ccd4a5)

![Turbidity (SCUFA) vs  Depth Plot for Each Cast](https://github.com/ZhiruiLi1/Oceanographic_Data_Analysis/assets/90368869/8d2fccde-e9ff-43bd-81c9-8e9698d8ad8a)
