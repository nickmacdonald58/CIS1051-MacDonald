# CIS1051-MacDonald
Optimization Results Cleanser

Video: https://temple.zoom.us/rec/play/sFQqX4WU0YQJOrmDkrwT-pcnHXBgTXFgFKUx9ZgSNx_nY8CTfa3dFgc5vAinYD-hpQ8PJteCUUix6Ey0.gyRftZVbyw-3O-Fr?startTime=1650913728000

Nick MacDonald, Senior, CIS1051, nicholas.macdonald@temple.edu

FORGOT TO MENTION IN MY VIDEO THAT MY PYTHON FILE LEVERAGES THE openpyxl LIBRARY. This was an important aspect of what it took to make my project. While openpyxl is an excellent tool to read and write excel files, getting used to the notation was difficult at times but can be learned through the internet. Having this understanding now is a great asset for my Python toolkit moving forward. 

This code will process the data from the 'Optimization w Results.xlsm' and write the data into the 'Results.xlsx' file. The 'Results.xlsx' is just an empty file to write into, as one of the largest obstacles was saving the 'Optimization w Results.xlsm' file. Initially I tried to add sheets to the model file to clean the results, but I believe a problem with openpyxl saving macro-enabled workbooks. The first time I attempted this my file was corrupted and I had to find a previous version and then redo any lost data from the file's corruption. The separate file containing results was the best approach, as this also allowed me to keep the model file open while running my code since only the results file was getting written on. 

Another problem I had was trying to use the values sheet, which is the sheet that solver was ran on. Considering this had formulas though, the sheet had to be copied and pasted using values only. This problem and similar problems slowed my progress throughout the project, which reduced how much I was able to accomplish. The features which were included are the most important for interpretation and the most tedious to do in excel. The most rewarding features to make are the first two functions, as manually deleting the 0 selections and using the count feature in excel was very time consuming, and this had to be done many times just a few weeks ago. This combined with learning excel was very rewarding especially since I will be using excel in my career.
