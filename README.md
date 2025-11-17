# Android-App-Project
Android app project outline for COM-437

Project Description
-------------------------
The objective of this project is to design and develop an app that works for its intended function. The fucntion of the app should be useful and beneficial to the user. The app that I have chosen to design is an alarm app. This alarm app will function as expected with it including the capability to set one or more alarms and then some kind of audible alert going off. This app will also include features to prevent the user from "sleeping through" the alarms which will be described in more detail below. It will have the option to incldue the completion of a puzzle to cause the alarm to turn off. Without the completion of this puzzle the alarm will continue ringing with the intention of waking the user completely up. The goal is that by the time the user has completed the puzzle, they will be awake enough to not want to return to sleep otherwise known as "sleeping through" the alarm. Achieveing this goal can depend on many varibale such as the level of sleep of the user and their responsivness to audiotry cues. I hope to combat this by offering many options for customization to fit the app to the user.

Problem Addressing
------------------------
As mentioned above, the problem this app aims to solve is that of people "sleeping through" their alarms. This phenomemon has likely happened to everyone at least once and can have varying levels of consequences from missing a job interview to just missing breakfast. The demand for an app that can solve this problem is existent as this problem still occurs with modern alarms. With this app, users would be able to go to sleep knowing that they will wake up in time to start their day. 

Platform
------------------------
Operating System: Android\n
Target Versions: Android 11+\n
Devices: Mobile phones, Tablets
Dependencies: Alarm managers, Notification systems, Device timekeeping

Frontend/Backend
------------------------
Frontend: Built on Android XML Layout System
Includes:
Alarm List
Add/Remove Alarm options
Add/Remove Puzzles options
Alarm Time Selection

Backend: 
Written in Java
Utilizes local storage and resources
Alarm trigger logic
Puzzle logic
Push notification logic

Functionality
-------------------------
Create new alarms
Add puzzles to select alarms
Choose between puzzle types
Remove puzzles from alarms
Remove alarms
Change alarm notification sound
Alarm shceduling
Recurring Alarms
Toggle Alarms
