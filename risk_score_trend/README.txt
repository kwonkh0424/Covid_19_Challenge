"Covid-19 Risk Score Trend- Updated"

This script analyze Risk-Score calculated by USC-ANRG team to determine if the Risk-Score of different regions in LA county is trending up or down.

Instructions for running the following code:
=================================================================================
Note: These files are developed and tested in Python3.6.

The following packages are required to run the codes:
-jupyter noteboook
-numpy
-scipy
-pandas
-sklearn
-datetime
-matplotlib
-re
-timeit

=================================================================================
"Covid-19 Risk Score Trend - Updated"

Required input files:
“Covid-19-R.csv" (automatically imported from github), "Covid-19.csv" (automatically imported from github), "county_storage.csv"
Output:
- Risk Trend Time Series Plot for target region
- A list of regions ranked by trend of Risk-Score. The table categorizes region into one of the three categories: trending up, neutral, trending down.


=================================================================================
=============================     Results      ==================================
csv file: contains Time stamp, Region, Risk-Score Difference, Trend Level, risk level (which is a quantized version of risk score into 4 levels 0-3)
=================================================================================


=================================================================================
================================= GitHub Repository =============================
We will also make the raw python scripts available via our GitHub repository: 
https://github.com/kwonkh0424/Covid_19_Challenge
=================================================================================


=================================================================================
================================= Contact Info ==================================
Kooha Kwon: kwonkh0424@gmail.com
=================================================================================


