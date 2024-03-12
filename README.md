This is a simple responsive BMI calculator using react  I am learning a lot from this small project. We used use state hook to manage the state of the application. let’s start to Build A BMI Calculator in React JS.

It is a measurement of a person’s leanness or obesity based on their height and weight. There are many tools which helps to identify the your body bmi b. we can build our own bmi calculator.


Step 1:
Create Project Using Commend:
=========>   npx create-react-app bmicalculator

step 2:
Set the Path  Of Project using Commend Cd
=========>   cd bmicalculator


step 3:
App.js

1)Imports:imports necessary CSS files and the required modules from React including the useState hook.

2)Four state variables are defined: weight, height, bmi,and message

3)BMI Calculation: The calcBmi function calculates the BMI based on the weight and height entered by the user. It prevents the default form submission behavior, checks if the weight and height are valid, calculates the BMI using the formula, and sets the BMI state variable. It also sets the message state variable based on the calculated BMI.

4)Reload Function: The reload function reloads the webpage when the "Reload" button is clicked.

5)The form is submitted when the user clicks the "Submit" button. It calls the calcBmi function

6)User Interface: The UI consists of input fields for weight and height, a submit button, and a reload button. The calculated BMI and the corresponding message are displayed below the form.




OutPut Of Project:
![Screenshot (285)](https://github.com/arunak7887/BMI-Project/assets/85956491/2637d568-d638-4979-915f-eb9a2354fbb9)


