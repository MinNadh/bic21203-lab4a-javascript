# Lab 4a – Client-Side Scripting (JavaScript)

**Name:** Yasmin Nadhirah binti Zainal  
**Student ID:** AI240084  
**Course:** BIC21203 Web Development  
**University:** Universiti Tun Hussein Onn Malaysia (UTHM)

## 1. Introduction

This lab focuses on developing interactive webpages using HTML and JavaScript. The activities cover JavaScript functions, event handling, input validation, conditions, loops, and DOM manipulation.

## 2. Question 1 – Interactive Text Changer

**Description:**

This webpage changes a paragraph when the user clicks the "Change Message" button.

**How It Works:**

- The webpage initially displays "Welcome to my website!".
- When the button is clicked, the `changeMessage()` function is executed.
- The paragraph changes to "Hello there!" using `textContent`.

**Expected Output:**

Before: Welcome to my website!

After: Hello there!

## 3. Question 2 – Smart Number Validator

**Description:**

This webpage checks whether a number is lower than, higher than, or equal to 10. It also validates invalid inputs.

**How It Works:**

- The user enters a number and clicks "Check".
- The `checkInput()` function checks the input using `if...else if...else`.
- The result is displayed using `textContent`.

**Test Results:**

| Input | Expected Output |
|---|---|
| 5 | The number is lower than 10 |
| 10 | The number is equal to 10 |
| 15 | The number is higher than 10 |
| abc | Please enter a valid number! |
| Empty input | Please enter a valid number! |
| 10.5 | The number is higher than 10 |

## 4. Question 3 – Dynamic Number Generator

**Description:**

This webpage generates a numbered list from 1 to 5 when the user clicks the "Generate" button.

**How It Works:**

- The user clicks the "Generate" button.
- The `generateNumbers()` function uses a `for` loop to generate numbers from 1 to 5.
- Each number is added to the list using `createElement()` and `appendChild()`.
- The existing list is cleared before generating again to prevent duplicates.

**Expected Output:**

1. The number is 1
2. The number is 2
3. The number is 3
4. The number is 4
5. The number is 5

## 5. How to Run

1. Download or clone this GitHub repository.
2. Open the project folder.
3. Navigate to the `Q1`, `Q2`, or `Q3` folder.
4. Open `index.html` in a web browser.
5. Click the buttons to test the JavaScript functions.

## 6. Screenshots

Screenshots of the webpage outputs and test cases have been uploaded to the `screenshots` folder in this repository.

The screenshots include:

- **Question 1:** Before and after clicking the button.
- **Question 2:** Validation results for 5, 10, 15, abc, empty input, and 10.5.
- **Question 3:** Before and after generating the numbered list.

## 7. Reflection

Through this lab, I learned how to use JavaScript to make webpages
