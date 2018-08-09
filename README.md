# AB-Test-Analysis

### PURPOSE OF THE SCRIPT 
- Automate part of the repitive work done every time analysing Tests
- Allowing analysts to use RPV as a Success Metric (watching for Revenue outliers and using WIlcoxon Rank Sum Test to deteremine statistical significance)

### WHAT IS THIS SCRIPT DOING ?
- Reading the Session Datasets of the Experiment (exported from the Adobe DataWarehouse or other analytics tool)
- Generating all the necessary Calculated Metrics, especially the KPI that are consistenly looked at across most Experiments on a typical Retailer Website
- Visualising the Cumulative Trends for every KPI to help Analysts determine the validity of the Results
- Determining is the observed metric lifts are statistically Significant to help Analysts determine the validity of the Results (using t-test and wilcoxon Rank Sum Test)
- Visualising Revenue Distribution to see if the RPV data can be used or if Outliers needs specific treatment
