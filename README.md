React Form with Formik and Yup<br>
This is a simple React form implementation using Formik for form handling and Yup for validation. The form allows users to submit donation details, including their name, email, amount, currency, and a message, along with agreement to the privacy policy.<br>
<br>
Features<br>
Formik for managing form state and submission.<br>
Yup for form validation with custom validation rules.<br>
Custom input components for text inputs and checkboxes.<br>
Error messages display when validation fails.<br>
Components<br>
MyTextInput: Custom input component for text fields.<br>
MyCheckBox: Custom checkbox component for terms acceptance.<br>
CustomForm: Main form component using Formik.<br>
How to Use<br>
Install dependencies:<br>
<br>

npm install formik yup<br>
Copy the code into your React component and use the CustomForm component where needed.<br>
<br>
The form includes the following fields:<br>
<br>
Name (required, min 2 characters)<br>
Email (required, valid email format)<br>
Amount (required, min 5)<br>
Currency (required)<br>
Message (optional, min 10 characters)<br>
Terms (checkbox, required)<br>
On form submission, the form data is logged in the console.<br>
<br>

Customization<br><br>
You can easily modify the validation schema to adjust rules for fields.<br>
The currency options and labels can be customized as per your requirements.<br>
