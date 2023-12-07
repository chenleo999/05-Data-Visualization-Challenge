# DataVisulationChallenge

______________________________________________________________________
Pymaceuticals

code: Pymaceuticals\Pymaceuticals.ipynb

source file 1: Pymaceuticals\data\Mouse_metadata.csv
source file 2: Pymaceuticals\data\Study_results.csv

Analysis results buried in the code file.

Description:

read data from source file, merge by mouse id

remove duplicate/erroneous entries of same mouse at same time point

summarize clean data:
    compare statistics by different drug treaments
        mean, median, varience, standard deviation, standard error of tumor sizes over entire study

    plot mouse count against each drug as bar chart

    plot mouse count over sex as pie chart

    plot tumor size at last timepoint against the 4 selected drugs as box chart
        identify potential outliers by using quantile and 1.5*iqr method

    track tumor size change over time on single select mouse as line chart

    dig a bit more into Capomulin treatment:    
        scatter plot mouse weight over average tumor size 
        apply liner regression, calculate correlation coefficient

   
Conclusion:
1. Capomulin and Ramicane appeared to be more effective than other drugs
2. Body weight and average tumor size are positively correlated (coeff: 0.84).

______________________________________________________________________

