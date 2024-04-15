# Tax-Calculator

This is a simple tax calculator implemented in JavaScript. It calculates the overall income after considering gross income, extra income, age group, and deductions. Additionally, it provides validation for input fields.

## Assumptions
Input Validation:
Input values are validated on focus, change, and when the submit button is clicked.
Errors are displayed to the user under the following conditions:
Typing a number less than zero results in an error message "Please type non-negative numbers".
Clicking on an input field and not typing anything or leaving any field empty and clicking the submit button results in an error message "This input field is mandatory".
Typing anything other than a number results in an error message "Please type numbers only".
Overall Income Calculation:
If the sum of gross income, extra income, and deductions is less than or equal to 8 lakhs, the overall income is displayed as the sum of gross income and extra income.

## Usage
To use the tax calculator:

Input the gross income, extra income, age group, and total deductions.
Click the submit button to calculate the overall income and display the result.
If any input is invalid, error messages will be shown to guide the user on how to correct the inputs.

## Test Cases
Case 1: Tooltip is shown when hovering over the question mark icons.

![image](https://github.com/SheWe786/Tax-calculator/assets/116451611/122749db-be54-4310-bd55-130975248696)

## Case 2: 
Display error icons if the user clicks the submit button without entering input. The error message states "This input field is mandatory" and it will be highlighted in red color.

![image](https://github.com/SheWe786/Tax-calculator/assets/116451611/5691b743-7983-45cd-bf55-a30d48bc1c29)

## Case 3: 
Error icons will appear if a negative value is entered in the Number fields. These fields only accept 0 or positive numbers. An error message states "Please enter non-negative numbers only".

![image](https://github.com/SheWe786/Tax-calculator/assets/116451611/7aad3baa-4310-43bf-b3a9-4ca6913aaa55)

## Case 4: 
If Gross Income + Extra Income - Total Deductions is ≤ 8 lakhs then no income tax is applicable. So overall income will be Gross Income + Extra Income.

![image](https://github.com/SheWe786/Tax-calculator/assets/116451611/0d4104ed-eb58-4d0e-b79b-f35299a9124c)






