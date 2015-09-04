# JavaScript Practice Exercise

This repository exists to be a jumping-off point, to build a functional web app
based on a rough skeleton.

The goal of the exercise is to provide a simple calculator application in a web
browser.

Provided is a Bootstrap outline of the keypad, and a space to print the answer.

Some of the buttons are missing and must be added.

At this point, the tool outputs "error" whenever a button is pressed.

To complete this exercise, make all of the buttons perform their intended goal,
and add the missing buttons.

## Existing

* All Number buttons
* Addition button
* Subtraction button
* Output box

## Missing

* Multiplication button
* Division button
* Equals button
* Other buttons

Feel free to add more buttons if you want to include them, but only add them if
you're going to make them function.

# Possible Behaviours to Build

1. When you press a number button, append the value of that button (eg- 6) to the right of the value in the output box (eg- output = 235, press '6' ==> output = 2356)
2. When you press an operation button, store in a buffer both the existing output value, and the requested operation (eg- output = 235, press '+' ==> output is cleared, storedValue = 235, operation = '+')
3. When you press the equals button, perform the stored operation on the current output value and the stored value (eg- storedValue = 4, operation = '+', output = 2, press '=' ==> storedValue is cleared, operation is cleared, output = 6)
4. Feel free to add more behaviours, like memory functions or complex mathematical functions, also consider taking input from the keyboard
