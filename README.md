# CS360
SNHU Mobile Architect & Programming 22EW4

Shaun Ryan

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address? 

The goal of this project was to develop a weight tracking app. The functions of the app were to allow the user to log in, allow the user to enter a daily weight reading, display previous weight readings from a database, and send an alert to the user when a goal weight is reached.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful? 

The screens were designed to be minimalist and in keeping with Android design guidelines. The log in screen has options to log into an existing account or creating a new account. The weight entry screen has options to enter a date and weight or cancel, which returns back to the logbook. The logbook screen has options to delete or modify individual entries. All screens except for the log in screen have a button to open the options menu on the app bar. I believe the design on the UI was successful.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future? 

When coding the app, I started with the log in screen. This feature shared a lot of functionality with the weight entry and logbook features, but in a more simplistic manner. Once I created a user database and code supporting it, I was able to use portions of that code to create the weight database and respective interface integration. I believe that establishing a working core functionality and expanding upon that with features is the best method for developing an app like this.

## How did you test to ensure your code was functional? Why is this process important and what did it reveal? 

Testing for functionality was achieved through Android Studio’s built-in emulator feature. This was a time consuming but important process for testing functionality and identifying bugs. One issues I ran in to was shifting development on to an older laptop which had issues running the emulation properly. In hindsight, tracking down a more capable computer or using actual Android hardware for testing would have been beneficial.

## Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge? 

Each step of the process came with challenges and required some amount of revision to the plan. Working with layouts in Android Studio is an area where I need to become more proficient. While creating the initial UI, I laid out the logbook page as a grid layout mock-up. After creating a functioning database, I scrapped the grid layout completely and shifted to a linear layout with fragments. Creating the UI before the underlying programming can be beneficial in many ways, but it can also lead to wasted effort.

## In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience? 

Of all the components of my app, the log-in screen was particularly successful. It checks the data base and prevents a user from creating a new account with an existing user name. There are improvements to be made, such as hashing the passwords and creating tokens for users to stay logged in, but the foundation is sound.
