# PHONENOW--CALLCENTRE

### PROJECT OVERVIEW
The project is on the analysis of data gotten from a Call Centre. The customers’ satisfaction, with respect to the call agents, was analysed for quality improvement and recommendation.

### DATA SOURCE
The dataset used for this project is labelled as ’01 Call-Center-dataset.xlsx’.

### TOOLS
-	Microsoft Excel
-	Microsoft power BI

### DATA CLEANING/PREPARATION
Using Microsoft Excel, the data was cleaned by ensuring that there were no duplicates. Spelling checks were also performed on the fields for consistency. Blank-value check was done to ensure that there was no inappropriate blank cell.

### EXPLORATORY DATA ANALYSIS
The following were the KPIs asked during this project:
•	Overall customer satisfaction
•	Overall calls answered/abandoned
•	Average speed of answer
•	Agent’s performance quadrant

### DATA ANALYSIS

Using Microsoft Power BI, a measure was developed to created a condition that identified if a call was answered and resolved, answered and not resolved, and not answered and not resolved. 
```Power BI
Answered and Resolved = IF(Sheet1[Answered (Y/N)] == "N", "Not Answered Not Resolved", IF(Sheet1[Answered (Y/N)] == Sheet1[Resolved], "Answered And Resolved", "Answered Not Resolved"))
```
Other measures were developed including: sum, average and count.

### RESULTS/FINDING
It was observed that:
-	Total number of calls made is 5000.
-	The overall average customers’ satisfaction is 2.76.
-	The average calls answered is 67.52.
-	The percentage customers’ satisfaction rating is 45.45% for the answered and resolved calls, 45.45% for the answered and not resolved calls and, 9.09% for the not answered and not resolved calls.

### RECOMMENDATION
One of the agents, Martha, has the highest customer satisfaction of others. She should train the others on how to improve their ratings.

### LIMITATION
No noticeable limitations for this project.

### REFERENCE
[Forage](www.theforage.com)

