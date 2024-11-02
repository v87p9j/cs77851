java c
MSDS 490: Healthcare Analytics and Decision Making
Project 2
Due Date: 11/01/2024 (Friday Midnight)
Submission Instructions: zip all your files (R code, data, Word document, figures, etc.) into one, following the file naming convention Last Name First Name Project#.zip Use online submission tools in Canvas to submit this project.
Total Score: 100.
You have developed a forecasting system that estimates patient volume for each hour of the day for a week. File “WeeklyDataForShiftScheduling.csv” provides the forecasted patient volume data. Your goal is to develop a one-week plan to determine the number of full time nurses you would want to employ to ensure that patient volume is covered by these nurses under the conditions specified below.
• A four to one ratio is assumed to determine the number of nurses required to properly care for patients.
• The shifts can only start at 8AM, 10AM, and 8PM.
• You have the option of having either a 8HR, or a 12HR shift starting at these times. A 12HR shift is considered more convenient and is preferred by the nurses, compared to 8HR shifts. With this in mind, th代 写MSDS 490: Healthcare Analytics and Decision Making Project 2R
代做程序编程语言e hourly cost of working a 12-hour shift is $20, and the hourly cost of working an eight hour shift is $25.
(i) Develop a coverage matrix for any given day for each of the shift type and duration;
(ii) Compute the nurse demand for each hour (a fraction demand is acceptable) in this determination.
(iii) A nurse either works an 8-hour shift or a 12-hour shift. The work week does not exceed 40 hours, and must be at least 36 hours.
(iv) Develop an optimization model that minimizes the total cost of scheduling the shifts, while ensuring that the nurse shortfall in any hour is less than 2. In developing your model, you can start with assuming that you have a large number of nurses that can generate a feasible solution, and subsequently decrease the nurse count by 1, till the model becomes infeasible.
(v) Change the value of maximum nurse shortfall from 0, 1, 2, 3, 4 and provide the cost of generating the schedule.
(vi) You want to explore using either an eight hour or a 12 hour shift starting at 6PM. Is there any value in adding any of these shifts?





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
