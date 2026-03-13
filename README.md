# server-monitoring-data-pipeline
Data pipeline and Power BI dashboard for monitoring server performance.

Data trasformation steps performed:

1) Loaded the dataset using Python (Pandas).
2) Checked for missing values in the dataset.
3) Checked and removed duplicate records.
4) Converted the timestamp column into datetime format.
5) Validated CPU and memory utilization values to ensure they are within acceptable ranges.
6) Created additional analytical features such as Total Network Traffic, Availability Rate, and Server Health Score.
