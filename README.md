# **This repository contains basically all of my tests and activities from college, using Kotlin in Android Studio.**
## ***"But what do these programs do? what problems do they solve?"***
## **Here's a quick resume about what each file on this repository do : ** 

##**Exercise 1**
### ***IN RESUME: Create a mobile app with register & login funcionalities.

"Create a mobile application for Android using the Kotlin language, with the functionalities of registration and login,
 where each of these functionalities should have a screen for each (login screen, registration screen). 
It should also be implemented using the static database I demonstrated in the last class (it is in the example below).
When registering, the information should be stored in this static class, so that when returning to the login screen, it is possible to authenticate the newly registered user."

## **Exercise 2**
### ***IN RESUME: Gets the project above, and implements a list of those who registered on the system, after the login/register. ***

"Using the app from the first submission (Login, Registration, and Authenticated screen), implement the functionality to display a list of users already registered in the system on the screen after the login is completed.
This list should reflect the registrations made in the app.
The list should display the user's name, and there should also be a logout button on the screen so that the user is redirected back to the login screen."

## **Test 1**
### ***IN RESUME: Given the layout sketch, build an app that allows the conversion of values between BRL, USD and EUR, with a defined conversion-base.***

"Build an app that allows currency conversion (Real, Dollar, and Euro).
The user should enter a value in one of the 3 fields, and upon clicking the button to perform the conversion, the calculation should be done for the other fields, considering the exchange rates below:

Real: R$ 1.00
Dollar: $ 0.18
Euro: € 0.16

Use the prototype below to design the layout of your app.
The app should strictly follow the prototype, respecting all margins, spacings, sizes, and styles.
The color scheme is up to the student.
The choice of colors and styles should support the correct use of the app.

a) (2 points) Screen layout.
b) (1 point) All fields should accept only decimal numbers.
c) (2 points) Conversion calculation from Real to Dollar and Euro, Dollar to Real and Euro, and Euro to Dollar and Real."

|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
### **Middle Test**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
**"Build a utility app that contains two functions: one to calculate the best fuel option and another to calculate a person's BMI (Body Mass Index).
The app should have a main screen with an option to navigate to the desired function, as shown in the example picture.**
**The program fluxogram was given, and the BMI picture was also given**

*Best Fuel Option*
When filling up, the price of ethanol (per liter) should be divided by the price of gasoline.
If the result is less than or equal to 0.70 (or 70%), ethanol is the better option; if it's higher, gasoline is the better choice.
The app should receive as input from the user the price of a liter of gasoline and ethanol.
The app should calculate and display to the user which fuel option is more suitable for refueling.

*BMI Calculation*
Calculate the BMI (Body Mass Index).
The simple formula is as follows: WEIGHT / (HEIGHT * HEIGHT) (Weight in kilograms and height in meters).
The app should receive as input from the user the height and weight values.
The app should perform the calculation and display the user's BMI classification according to the chart in the picture."
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|

### **Class Activity 3**
*"Implement the functionalities of registering, editing, and deleting in the project below using the API provided:
Address for the mock API of animals:
https://672162e498bbb4d93ca84641.mockapi.io/animal"*
Note: the mockapi was already taken down.

### **Second Test**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
"Develop an application that contains a screen listing the users registered in the API above.
The main screen of the application should display a list of users, which should be downloaded from the API, as shown in the example image.

Evaluation Criteria:

Configuration
1 pt - Configure internet permission in the manifest.xml.
<uses-permission android:name="android.permission.INTERNET" />

Main Screen:
3 pts - Create the main screen (Title, logout button, listview/recyclerview).
2 pts - Create the layout for the list item.
2 pts - Implement the Interface to create the Retrofit instance.
2 pts - Implement the GET method to display the list of users on the screen in case of success, or show an informative message in case of failure."
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
### **Final Test**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
**"Develop an application that contains two screens. On the first screen, it should display a list of Pokémon that should come from the API described above. 
On the second screen, it should show a Pokémon detail screen with its descriptions (the second screen is already ready, you just need to bind the API values to the fields on the screen).**

*Activities:*

*Configuration*
2 pts - Configure the internet permission in the manifest.xml.
<uses-permission android:name="android.permission.INTERNET" />

*Main Screen*
6 pts - Create a Pokémon listing screen using RecyclerView.
3 pts - Display Pokémon in a 2-column grid (this only works with RecyclerView).
2 pts - Navigate to the Pokémon detail screen when clicking on a Pokémon.
4 pts - Implement the API call to list the Pokémon.

*Detail Screen*
4 pts - Bind the values (name, image, height, weight, and ability) received from the API to the screen.
2 pts - Implement the functionality of the back button (<) to return to the listing screen.
3 pts - Load the Pokémon images using Glide.
4 pts - Implement the API call to display the Pokémon details.

Code to display the list in columns in RecyclerView:
recyclerView.layoutManager = GridLayoutManager(context, 2)"
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
***Final note:***
*This semester in specific was so rushed(all was learnt within 4 months) that some little, but relevant mistakes were done by me.
Take this, and the fact that each test was done in less than two(2) hours, in consideration.
It does not represent the best results I can give, but are honest samples of the progression of someone who just learned Kotlin.*
