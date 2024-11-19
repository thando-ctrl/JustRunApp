# JustRunApp
St10463346
Thandolwethu Masondo

App Required: Task is an app that tracks average running time and allow user to comment/take notes on their performance 
Reason for the app? : This App Helps people looking to find a fun way to reflect on their daily running routines by allowing them to track their daily running routine time and also calculates the average time they ran every week, many people fail to keep their New Year’s Resolution but this app is designed to ensure that people stay motivated and willing to put in the work. 
Name of the App ideas:
1.	RunBuddy
2.	What’sMyScore
3.	JustRun

Selected was the JustRun ( third option ) Reason being that it come with the analogy that when you just do something you become much happier with the result since you did not overthink and end not doing or running in this case.
App properties: 
•	A splash screen with a logo and short welcome message to encourage the user
•	A MainScreen with the functionality to allow users to input the date, their running time, and to a comment on their current run.
•	A DetailsScreen this screen will display the data inserted. Namely:
	The date
	The time recorded
	The comment
	And the average time

Pseudocode

Start
OUTPUT “Name of developer, St number”
OUTPUT “Welcome to you Running Companion click on next to proceed”
Mainscreen()
STOP

VOID Mainscreen()
STRING date [6]
NUM time [6]
STRING comment [6]


OUTPUT “Enter the date”
INPUT date
OUTPUT “Enter the time”
INPUT time
OUTPUT “How was today’s run?”
INPUT comment
DetailsScreen (date, time, comment)
RETURN

VOID DetailsScreen (day, hour, note)
OUTPUT “On day1:” day
OUTPUT “You ran:” hour
OUTPUT note
WHILE x < 6
NUM sum = hour [x] = hour [x-1]
x = x + 1
ENDWHILE	
NUM totalItems = 7
NUM avg = sum/totalItems
OUTPUT “Your Average for the week:” avg
RETURN


Conclusion
The JustRun App is a groundbreaking app that is targeted at millions of people across the globe looking to keep fit and also keep their New Year’s Resolution.

![Screenshot (7)](https://github.com/user-attachments/assets/9fa0ce48-5a2a-4def-86b9-337e38238bad)

![Screenshot (8)](https://github.com/user-attachments/assets/c8d1f91b-e7aa-43e0-9106-5d1978b0be32)

![Screenshot (9)](https://github.com/user-attachments/assets/c54d508c-3f73-465e-a6e4-4af5c8215de6)



