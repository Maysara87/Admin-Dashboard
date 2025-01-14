
![Administrations](https://github.com/user-attachments/assets/d9ca133d-8a24-4edb-b1fc-7efbaf26a92f)


Purpose: 
Design an excel sheet and dashboard to: 
•	Follow up the progress of the projects and tasks within each project.
•	Follow up the performance of the employees within the company.

Data Sheet:
The excel sheet allow you to add the project name and ten tasks within the project, after adding the name of the task:
•	the due date will automatically appear to be the last day of the month if no other date added to modified due date.
•	You can choose the priority of the task from dropdown list
o	1  Normal
o	2  Important
o	3  Highly Important
•	After choose priority score the description of the score will appear in priority.
•	You can choose the responsible for the tasks from dropdown list of responsible.
•	You can choose the percent of completion of the task from the dropdown list:
o	0%
o	25%
o	50%
o	75%
o	100%
•	Automatically completion status will be updated based on the completion percent:
o	0%  Not started
o	25%, 50%  On Going
o	75%  Almost Completed
o	100%  Completed
•	Automatically the status will be updated based on the completion percent and due date:
o	If percent 100%  Completed
o	If percent less than 100% and within due date  Within Time
o	If Percent less than 100% and due date passed  Over Due
•	For the project row:
o	The priority will be the highest score of all tasks.
o	The due date will be the lowest due date of all tasks.
o	The completion percent will be the average completion percent of all task.
Dashboard:
•	Total number of projects is calculated based on cells has project name.
•	Bi chart of projects based on status; number of projects completed, number of projects within time and number of projects overdue.
•	Total number of tasks is calculated based on cells has task name.
•	Bi chart of tasks based on status; number of tasks completed, number of tasks within time and number of tasks overdue.
•	Progress percent: the average completion percent of all tasks.
•	Column chart display the average completion percent of each priority of the projects.
•	Employee performance bar chart shows the number of tasks and average completion percent of each employee.
•	The other column chart is displaying the number of tasks based on priority and status for example, the number of high important projects and completed for each employee.
•	Filter for employees, status and priority are on the side of graphs allow to filter the data .
•	The default due date and today date is appearing for guidance.
•	Below the graphs, a table summarize all the active projects with the relevant data.
•	Each project is linked to another dashboard summarize the tasks within the project.











