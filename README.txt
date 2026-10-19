RESEARCH IN COMPUTING - R PROGRAMS (Practicals 1 to 9)
=======================================================
All programs are .txt files. To run one:
  1. Copy the program text into R / RStudio (or rename the file to .R).
  2. Put the files from the sample_data folder in the R working directory
     (setwd("folder") ; getwd() shows the current one).
  3. One-time installs:  install.packages(c("plotrix", "rjson", "readxl"))

sample_data/ holds stand-in data files (sales.csv, PRAC3.csv, RDATA2.csv, RDATA.xlsx,
Employee.csv, prac5.json, covid_state.csv, covid19_countries.csv). Replace the covid files
with your real data - the column names must stay the same.

Tested with R 4.3.3: every program runs with no errors or warnings.
Fixes made to the journal code are marked with "# FIX:" comments.
