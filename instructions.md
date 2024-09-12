
# String & Numeric Input in Python

## Getting Started

- Complete the stations for this lesson
- Create a **public** GitHub repo named: **string-numeric-input-practice**
- Add a `main.py` file to your repository
- Write the code for this station in your `main.py` file 
- Submit the URL that points to your repo on Google Classroom

## General Specifications

- Add a comment block to the top of your Python script, like so:
```python
# Abraham Lincoln
# 24 MAR 20XX
# String & Numeric Input
```
- Use short, descriptive variable names
- Write your variable names in lowercase

## Programming Practice

In your `main.py` file, write the following code:

### Task 1
- Use the `input( )` function to prompt the user to enter his/her first name and the name of the program they attend at Career Tech.
- Assign the user's responses to variables
- Use **concatenation** to build an output string that displays the user's answers
- Please use correct capitalization, spelling, and punctuation in your code

### Task 2
- On one line, prompt the user to enter their current age
- Assign their response to a variable `age`
- On the next line of code, use the `int( )` function to convert the user's response to an **integer** (a number that doesn't have a decimal point)
- Display a sentence that contains the user's current age
- Challenge: Have Python add 10 years to the user's current age; then display a sentence that says what the user's age will be ten years from now

### Task 3
- Using the `input( )` and `int ( )` functions in a single line of code, prompt the user to enter the number of people in his/her family
- Use **concatenation** to display a sentence that says how many people are in the user's immediate family
    - HINT: The Python `str(  )` function might come in handy here!
- On the next line of code, use an f-string to display a sentence that says how many people are in the user's immediate family

### Task 4

- Use the `input( )` function to prompt the user to enter two different toppings for a large pizza they ordered from Jet's Pizza
- Next, use the `input( )` function to get the price of the large pizza
- On the next line of code, use the `float( )` function to convert the price to a float (a number with a decimal point)
- Use f-strings to display:
    - the two toppings the user requested for his/her pizza
    - the price of the large pizza
- Finally, thank the user for placing an order with Jet's Pizza

### Task 5

- Prompt the user for his/her first name
- Prompt the user to enter his/her height in inches
- Make sure you use the `float( )` function to convert the user's input into a float (a number with a decimal point)
- Then define a constant called CONVERSION_FACTOR and assign it the value 2.54
- Use the multiplication operator to multiply the user's height in inches by the CONVERSION_FACTOR constant
- Use either concatenation OR f-strings to display:
    - a message that says how tall the user is in inches
    - a message that says how tall the user is in centimeters
- Customize each message by including the user's first name and the correct unit of measure in the message
