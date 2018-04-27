# basicvalidationmess
Project Instructions: 
For this project, you will use HTML, CSS, and JavaScript in order to create a dynamic webpage that meets specific requirements. Specifically, you are to create a JavaScript file (validate.js) that will successfully validate the input fields without altering the html file (except to test). The goal of this exercise is to get you more familiar with events and working under specific requirements. Sometimes clients want things handled a specific way. In this case, we are providing validation that applies to input elements based on their classes. This means the JavaScript file can be used on multiple pages and still work as long as proper convention is followed.
You will be provided with a basicvalidation.html file that you will use to create this project. This HTML file should not be modified – your code should work with this file. Make sure to name your JavaScript file appropriately in order for it to work with the HTML file. 
Upload your JS file (and CSS file if you create one) to a new Git repository in the cycle group named <your_name>_form_validation. Do not upload the HTML file - your code should work with the default HTML file provided, which the instructors will use to verify your work.
Requirements:
Validation will be determined by the element's class.
Required: Must have a value that is not empty or whitespaces (" ").
Numeric: If a value is provided, it must be a series of numbers.
Required_Size: If a value is provided, it must be X characters long. X is determined by the maxlength attribute for the element. If there is no maxlength attribute, the field can be considered invalid immediately.
No validation libraries are used.
Class names used are; required, numeric, required_size.
Tests:
If validation fails, display a status message at the top of the form stating which elements are invalid, and prevent the form from submitting. If the validation passes, allow the page to submit (You will know the page submits when the URL in the address bar changes).
Add additional inputs with any combination of classes and verify they validate without altering the JavaScript file.
Add an additional form with inputs and verify that submitting it only validates that form's inputs.
Verify that the functionality works on the latest versions of Chrome and Firefox.
Class names grouped together in html tags should provide chained validation.
