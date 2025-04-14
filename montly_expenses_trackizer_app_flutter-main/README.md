Building a Basic Expense Tracking Application 
Objective: 
The objective of this assignment is to assess your ability to design, implement, and 
develop a scalable frontend using Flutter and Firebase. 
Tasks: 
Task 1: Develop a basic personal expense tracker app interface. The app should allow 
users to track their expenses, and visualize their financial data over time. 
Requirements: 
User Interface: 
● A clean and intuitive UI. 
● Ability to add expense and income entries. 
● Use Material Design components for consistency and familiarity. 
Features: 
● Ability to delete expenses by swiping gestures. 
● Categorization of expenses (e.g. food, travel, subscriptions and shopping). 
● Display of income, and expenses. 
The data created should be stored in local databases such as SQFlite or Hive and 
should be fetched from there to display. 
Task 2: Google Authentication 
Implement Google authentication feature for login/signup. In case of successful signup 
store the document with name and email in cloud firestore, and name of document 
should be the firebase user id , then store user id in local storage like shared preference 
to get the login the user after the session is terminated. Implement a logout functionality 
to logout the user. 
(If the user has signed in the previous session and is not logged out then the details 
should be fetched from Cloud Firestore). 
