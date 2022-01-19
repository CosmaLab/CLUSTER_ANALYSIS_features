# CLUSTER_ANALYSIS_features
Code to obtain a summary of the results of a batch of cluster_analysis .mat files.

Code by Alvaro Castells

README and annotation updates by Alvaro Castells.
Further annotations by Laura Martin, 18-12-2021.

Checked functionality on Matlab_R2016a

 
### GOAL: 
This code is used to quickly obtain a summary of the results of a batch of cluster_analysis .mat files. It will give you a wide variety of information from the analysis file, both about the cell in general, and about the generated cluster characteristics. The file will also contain the full path to the analized cell on the first column in order to be able to backtrack the data if necessary. It is not recommended to change the names of the files or move them from the original place, as it may complicated keeping track of the analysed data. 


### INPUT: 
.mat files obtained from the CLUSTER_ANALYSIS_main script.



### OUTPUT:
.xlsx file with the information organized in rows by cell, and columns for every parameter that we are looking at. The file name will be: "_Data_Summary".



### HOW TO USE: 

1.	Open function "CLUSTER_ANALYSIS_features.m" 

2.	In 'Root', write as a string the folder of cluster_analysis .mat files you are going to run. The output will be saved as a .xlsx file just outside this folder.

2.	Run the code

3.	Load the .mat files you want analyzed using the uipickfiles.m GUI. For it, just search in "Current Folder" for the folder in which the results are stored, select the files you want to obtain the results from and press "Add". Once finished selecting files, press "Done". On "File Filter" it is recommended to add the termination of the files we are interested in. In this case, write ".mat" there. In that way, the only files available for selection are the .mat files.

4.	Press 'Done' on the GUI

5.	Output will be generated and a .xlsx will be created just outside the folder previously defined. 

