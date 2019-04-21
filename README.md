This is a Registration form build with react using only functional components with React Hooks.
-This form is validated the Name field requires at least first and last name, the initial of each name is capitalized even if the user enter all lower case the form change the initial for a capital letter.
-The Email field is validated with a regular expression to check that is a valid email, if is a valid email format, the forms makes a request to the back end to check if the email address is already in use, if the address is in use the form shows an error.
-The password uses regular expressions to make sure that all the minimum requirements  are met for a more secure password, then compares if the password confirmation matches.
-Finally if all the fields are valid (no errors), the button is enabled, else the button is disabled to prevent sending incorrect data.

