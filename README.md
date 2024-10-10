# Note:

1. PrimeNG (https://primeng.org/) and Prime FLex (https://primeflex.org/) is already installed. You can utilize these libraries for convenience.
2. You can also choose to not use it or choose own UI library for testing purposes.

# Test 1

As a user, I want to have a parent and child component interaction where:

1. Child Component: The child component contains a form with fields for username, email, and mobile number, along with a submit button to submit the form.
2. Parent Component: In the parent component, I can toggle the visibility of the email field in the child form by clicking a button.
3. Component Display: The child component is displayed within the parent component, with clear visual separation between the two through basic styling.

# Test 2

As a user, I want the following validation rules applied to the child component’s form:

1. Field Requirements: All visible fields in the child component should be required.
2. Email Validation: The email field must have a valid email format.
3. Mobile Number Validation: The mobile number field must have exactly 10 digits.
4. Submit Button State: The submit button should be disabled if any validation fails.

# Test 3

As a user, I want to trigger form submission with the following behaviors:

1. Mock API Error: When “test” is entered as the username, it should trigger a mock API error.
2. Form Submission: Use the submitForm method to submit the form data.
3. Parameter Update: Ensure the parameter type for the submitForm method is correctly updated.
4. Button State: The submit button should be disabled after it’s clicked to prevent multiple submissions.
5. Feedback Display: Show a success or failure message based on the form submission result.
6. Emit on Success: If the submission is successful, emit the username to the parent component.
