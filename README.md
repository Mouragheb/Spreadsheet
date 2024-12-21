# Spreadsheet HTML/CSS/JS

A Pen created on CodePen.io. Original URL: [https://codepen.io/Mouragheb/pen/yyBgyQO](https://codepen.io/Mouragheb/pen/yyBgyQO).

What the Project Does:

This project is a functional programming spreadsheet application built for a web browser. It mimics the behavior of a basic spreadsheet tool like Excel or Google Sheets. Users can:
	1.	Enter formulas and perform calculations:
	•	Use basic arithmetic operators (+, -, *, /) directly in cells.
	•	Apply built-in functions like SUM, AVERAGE, MEDIAN, and more using custom formulas.
	2.	Use cell references:
	•	Users can reference other cells (e.g., =A1 + B2) to create dynamic formulas.
	3.	Handle ranges of values:
	•	It supports ranges like A1:A5 and expands them into individual cell references for calculations.
	4.	Handle edge cases:
	•	Includes features like duplicate removal, range creation, and increment operations.

Technologies and Languages Used:

1. HTML:
	•	Purpose: Defines the structure of the webpage.
	•	Usage:
	•	The HTML file sets up the basic container for the spreadsheet.
	•	Includes references to external CSS (styles.css) and JavaScript (script.js).

2. CSS:
	•	Purpose: Provides the styling for the spreadsheet.
	•	Usage:
	•	The #container div uses CSS Grid to arrange labels and input cells in a spreadsheet-like grid layout.
	•	Labels (.label) are styled for headers (A-J for columns and numbers for rows).

3. JavaScript:
	•	Purpose: Implements the functionality of the spreadsheet.
	•	Usage:
	•	Core Features:
	•	Custom mathematical operations with infix evaluation.
	•	Built-in spreadsheet functions like SUM, AVERAGE, and MEDIAN.
	•	Recursive formula evaluation (handles nested formulas and dependencies).
	•	Event Handling:
	•	Uses the onchange event on input fields to trigger formula evaluation.
	•	Functional Programming Principles:
	•	Many functions are pure (no side effects), making the logic easy to understand and test.
	•	DOM Manipulation:
	•	Dynamically creates the grid layout, labels, and input fields.
	•	Updates cell values based on user input or formula changes.

4. Modern JavaScript Techniques:
	•	Arrow Functions: Used throughout for concise syntax.
	•	Spread Operator (...): Used for handling arrays (e.g., removing duplicates).
	•	Higher-Order Functions:
	•	map, filter, reduce, etc., for efficient data manipulation.
	•	Destructuring: Simplifies access to array or object elements.
	•	Template Literals: Used for cleaner string interpolation.

Project Features:
	•	Grid Layout: A grid-based structure for the spreadsheet with dynamically created labels (A-J) and input fields (1-99).
	•	Formulas and Functions:
	•	Arithmetic operations: +, -, *, /.
	•	Built-in spreadsheet functions: SUM, AVERAGE, MEDIAN, etc.
	•	Support for cell references (A1, B2) and ranges (A1:A5).
	•	Recursive Formula Evaluation: Handles nested and dependent formulas dynamically.
	•	Range Handling: Converts ranges like A1:A5 into individual cell values for calculations.
	•	Edge Case Handling: Includes features for deduplication, empty strings, and fallback scenarios.

Summary:

This project combines HTML, CSS, and JavaScript to create a lightweight, functional spreadsheet application. It uses modern JavaScript techniques and functional programming principles to provide dynamic and efficient handling of user inputs, formulas, and spreadsheet-like behaviors.
