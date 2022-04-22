# Kickstarter-Analysis
Louise’s play Fever came close to its fundraising goal in a short amount of time. In this exercise I help her to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, I visualized campaign outcomes based on their launch dates and their funding goals. Then submitted a written report based on the analysis and the visualizations I created.

This new assignment consists of two technical analysis deliverables and a written report to deliver my results.

## Deliverable 1: Outcomes Based on Launch Date Chart
#### Using my knowledge of pivot tables and graphing in Excel to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date.
- A "Years" column is created based on the "Date Created Conversion" column in the Kickstarter spreadsheet
- A pivot table is created in a new worksheet labeled "Theater Outcomes by Launch Date"
- The pivot table filters on "Parent Category" and "Years"
- The columns, rows, and values in the pivot table fields are correctly populated
- The "Parent Category" is filtered on "theater"
- The row labels are changed to display the months of the year, and the campaign outcomes are sorted in descending order
- A line chart is created showing the number of successful, failed, or canceled projects by month, it has a title, and it is saved as Theater_Outcomes_vs_Launch.png

## Deliverable 2: Outcomes Based on Goals Chart
#### Using my Excel skills to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. I use COUNTIFS(), to collect the outcome and goal data for the “plays” subcategory.
- A new sheet is created with eight columns and twelve rows, according to the instructions (3 pt).
- The COUNTIFS() function is used to populate the "Number Successful," "Number Failed," and "Number Canceled" columns, based on the project "outcome," the "goal" amount using the goal ranges in Step 3, and the Subcategory "plays" (15 pt).
- The SUM() function is used on each row to add the "Number Successful," "Number Failed," and "Number Canceled" columns to populate the "Total Projects" column (3 pt).
- The percentages of successful, failed, and canceled projects are calculated based on the data from the "Total Projects," "Number Successful," "Number Failed," and "Number Canceled" columns (3 pt).
- A line chart is created and saved as Outcomes_vs_Goals.png with the goal-amount ranges on the x-axis, the percentage of successful, failed, or canceled projects on the y-axis, and an appropriate title (6 pt).

## Deliverable 3: A written analysis of the results
#### Overview of Project
- The purpose and background are well defined (2 pt).
#### Analysis and Challenges
- The overview of the analysis is well described with screenshots (2 pt).
- Challenges or difficulties that were encountered, and how they were overcome, are well explained. If there were no difficulties, describe any possible challenges or difficulties that could be encountered (2 pt).
#### Results
- Two conclusions are made about the Theater Outcomes by Launch Date (2 pt).
- One conclusion is made about the Outcomes based on Goals (2 pt).
- There is a summary of the limitations of the dataset, and there is a recommendation for additional tables or graphs (2 pt).
