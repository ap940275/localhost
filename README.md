# Quiz Taker



#Added features: 

1. Added Timer support.
2. Added control to "Enable" and "Disable" the quiz on the Admin panel
3. Added control so that user can start the quiz at any time and continue the quiz even if some error or session timeout occurs.
4. Improved GUI of the quiz panel.


#How to Use

1. Use the Admin Panel to set up quiz. Quiz won't be enabled unless you click the "Enable" button. Click on the same to enable an added quiz.
2. Scores are updated realtime on the server, however the leaderboard will be updated only when the user finishes the quiz, or there is a time out or the admin ends the quiz by clicking on "Disable" button.
3. Once the admin clicks on the disable button, the quiz ends for all the users taking that quiz, irrespective of their active or inactive state (whether logged in or left the quiz in the middle only). The leaderboard will be updated either when a user "Finishes" his /her quiz and when the admin "disables" the quiz. 
4. Once the quiz is disabled, the quiz becomes inaccessible. If the quiz is enabled again later, only those user who have not already taken the quiz can take the quiz.
5. It is recommended that you Enable the quiz when all the users are ready and disable the quiz when all the users have completed the quiz or time limit of taking the quiz has exceeded.
