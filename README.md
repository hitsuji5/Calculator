# Simple Calculator
This is a simple calculator app for android phones.
The code is based on "Android Programming Guide" chapter 20.

* activity_main.xml: A TextView will be created by this code for the necessary buttons and the number screen of the calculator. For preventing the manual user input with the android a default keypad, we will use the TextView in place of the EditText.

* button.xml: For decorating the calculator buttons, this drawable resource will be used. In this code, two gradient shapes are given. One gradient shape is used for the normal state of the button and the second gradient shape is used for the button pressed state.

* MainActivity.java: onCreate method sets OnClickListener to numeric buttons, operator buttons, equal button and decimal point button. When Equal button is pressed, onEqual method is called to calculate the solution.

* The library exp4J is used to evaluate the arithmetic expressions in this project. From the Gradle scripts, select the file “build.gradle (Module: app)”. A dependency ‘net.objecthunter:exp4j:0.4.4’ will now be added to the project.
