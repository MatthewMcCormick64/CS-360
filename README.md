# CS-360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

  The application option that I chose was Option 3. This application was to be a weight tracking application. The first requirement was to have a user login screen that allowed a user to register for the application and to also login. Once the user
  was logged in, there was a new screen so the user could add in daily weight tracking and a goal weight. The goal weight was then saved so if the user achieved the weight they would be notified. The notification had to be accepted be allowing permission to the app to send out a sms message. 
  A database was created to store the users log in, weight and goal weight information. 

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

  The screens that were necessary to support the users needs was a login screen, daily weight entry screen and a screen to allow the user to accept notifications. Features that were included in all the screens were textviews and plain text widgets to allow a user input to be implemented into the code. 
  Buttons were also necessary to allow the user inputs to be confirmed. Different application layouts were also implemented to allow a clean visual for a user to use the application. In my opinion the designs were succesful as testing the application everything seemed to run correctly. 


How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

  The process I took to coding the application was to have one main activity file that based the code from one screen to the next. I used the intent add-on to allow a call back in each class to the main activity file so the app would then launch which activity screen was needed. I also applied OOP principles 
  with having multiple classes to control the code and not just one main file. I also had a seperate database file so that was used in both the log in code and weight entry code. OOP should always be used in coding and gaining a deeper knowledge will help in the future. 


How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

  To ensure my code was functional, I ran the Andriod Emulator multiple times. I set the entries up to fail to make sure the code handled the failed test correctly. This is important to make sure your code is debugged before launch. 


Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

  When laying out the UI design and trying to determine how the code was going to work, I thought this would be more simple than what it was. I struggled to figure out how to get the code to go from screen to screen. After some research I was able to find the Intent add-on. I also had to innovate when setting up how to   keep the code efficient. I looked over some of the andriod project examples to see how a project with multiple activies could do this. 

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
  The specific component of the mobile app that I was successful in demostrating was the database. The database is the main driver off the application and keeping all the data stored. I was able to successfully store entries and login information. I was also able to create invalid responses so if the user didn't meet required criteria for a password, the applicaiton would send a message. 
