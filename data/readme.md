This `data` folder contains the raw and processed data files along with the csv project codebook file.

`raw_data`: User can specify which variables they want to retain in their personal NHIS profile. After specifying the variables, NHIS provides .xml and .dat file while extracting the data from website and the file provided by NHIS was converted into rds and csv files. The created csv file was very large (153 MB) and GitKraken didn't like it so only rds file has been added to the raw_data subfolder.

`processed_cleaned_data`: This subfolder contains the cleaned rds and csv file created after processing the data and the codes used during cleaning process has been provided along with the project.

`Project Codebook.csv`: This file contains the variable names, their meanings, and the codes used in the project.