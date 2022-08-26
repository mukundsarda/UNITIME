# UNITIME
UNITIME - University Timetable Decoder

# ABSTRACT OF PROJECT
We all know it’s really difficult to keep a track of your classes and schedules in university with all the ongoing vivas, practical exams, fests. So, we came up with a Project called UniTime to help you to keep track of your classes so you don’t need to always lookup for a whole timetable for every class.
UniTime is a Timetable decoder program developed using C language with the help of structures, functions and file handling. In Universities, we have a long timetable which contains the schedule for the whole week and it becomes really difficult to look for each class with all the different abbreviations you need to remember when you are running late for the class. According to a study by wired, an average student spends around 5 mins to look for a class on the timetable. So, with UniTime, we are also saving those 5 mins from your busy university schedule.
UniTime is focused on saving time using this project so whenever you run this program, it will sync with your device time and display a minimal output that tells you about which class you are having with which teacher and at what location. We also added one functionality in which if the user wants to manually check the class, he/she can enter the time and the program will display the class information.

# PROJECT DESIGN
So In this project, we ask user for input, if he/she wants to enter the time manually or wants to check the schedule for the current class.
-If the user wants to check the current class
We have added a date-time structure through which it extracts the date and time from the user’s device. Using switch case we are able to print the day and the timetable as per the variables ‘day’ & ‘hours’ which contains the text file of different classes according to the day and hour. We have created different functions for printing timetables for different days and in switch statements, we call those functions to print the timetable for that day according to the input provided.
-If the user manually wants to enter time and check class
In this the user needs to input the day and time to check the class . In this we also use switch case to call those functions to print the timetable for that day and time.
