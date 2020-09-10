"Covid-19 Risk Score Trend- Updated"

This script analyze Risk-Score calculated by USC-ANRG team to determine if the Risk-Score of different regions in LA county is trending up or down.

Instructions for running the following code:
=================================================================================
Note: These files are developed and tested in Python 3.7.6.

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
- "rs_trend_recent.csv": A list of regions ranked by recent Risk-Score trend. Only includes most recent Risk-Score data.
            - Time Stamp: The date which the trend was calculated from
            - Region: The name of the region within LA county
            - Risk-Score: Risk-Score calculated by USC team
            - Daily New Cases: Daily new Covid-19 confirmed cases in each region
            - Rolling Risk-Score: 18 day rolling average Risk-Score
            - RS Diff: Daily rolling average Risk-Score Difference of most recent data
            - Trend: Risk-Score Trend categorized from RS Diff
- "rs_trend_combined.csv": This data includes Risk-Score trend for all past data.

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


