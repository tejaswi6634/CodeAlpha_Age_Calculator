This project is a web-based Age Calculator application designed to collect a user's name and date of birth, calculate their age, and display the result on the screen. Here's a brief explanation of its components and functionality:

HTML Structure
DOCTYPE and Head Section: Defines the document type and sets up meta information, title, and internal CSS for styling.
Body Section: Contains a centered container with a form and a result display area.
CSS Styling
Body Styling: Sets a background color, font properties, and uses Flexbox to center the container.
Container Styling: Adds a white background, padding, rounded corners, and a shadow for a card-like appearance.
Form Elements: Styles labels, text inputs, and the submit button for better user experience and aesthetics. The submit button changes color when hovered over.
JavaScript Functionality
Calculate_Age Function: This function is triggered when the form is submitted.
Date Objects: Captures the current date (ptime) and the date of birth input by the user (time).
Age Calculation: Computes the difference in years between the current year and the birth year.
Month and Day Adjustments: Adjusts the age if the current date is before the birth date in the current year.
Display Result: Updates the HTML element with id demo to show the calculated age.
Prevent Default Form Submission: Ensures the form does not reload the page upon submission.
User Interaction
Name Input: User enters their name.
Date of Birth Input: User selects their date of birth using a date picker.
Submit Button: User clicks the "Calculate" button.
Age Display: The calculated age is displayed below the form.
This application provides a simple yet effective way for users to determine their age based on their date of birth.
