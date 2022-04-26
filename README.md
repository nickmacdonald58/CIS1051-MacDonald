# CIS1051-MacDonald
#Optimization Results Cleanser
#Nick MacDonald, Senior, CIS1051, nicholas.macdonald@temple.edu
#FORGOT TO MENTION IN MY VIDEO THAT MY PYTHON FILE LEVERAGES THE openpyxl LIBRARY

This code will process the data from the 'Optimization w Results.xlsm' and write the data into the 'Results.xlsx' file. The 'Results.xlsx' is just an empty file to write into, as one of the largest obstacles was saving the 'Optimization w Results.xlsm' file. Initially I tried to add sheets to the model file to clean the results, but I believe a problem with openpyxl saving macro-enabled workbooks. The first time I attempted this my file was corrupted and I had to find a previous version and then redo any lost data from the file's corruption. The separate file containing results was the best approach, as this also allowed me to keep the model file open while running my code since only the results file was getting written on. 
