# form_checking
Password Validation Script
This project is a simple password validation checker that provides real-time feedback on password strength by checking if it meets specific criteria. It uses HTML, CSS, and JavaScript to validate the input as users type in the password field. The validation criteria include:

At least one lowercase letter
At least one uppercase letter
At least one number
A minimum length of 8 characters
Features
Real-Time Validation: As users type in the password field, validation checks are performed in real time, highlighting criteria met with a "valid" status and unmet criteria with an "invalid" status.
Dynamic Feedback: Feedback on the requirements is shown or hidden based on whether the password input is focused or blurred.
Usage
To integrate this functionality:

HTML Structure: Ensure your HTML includes a password input field with an ID of "password" and criteria elements with IDs "letter", "capital", "number", and "length". A container with ID "message" will show or hide validation feedback.

JavaScript: Add the JavaScript code provided in your script file or in a <script> tag within your HTML. The script listens for focus, blur, and keyup events on the password input to dynamically update the criteria's validation state.

CSS: Style the .valid and .invalid classes in your CSS to visually indicate valid and invalid criteria.
