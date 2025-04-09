## Functional Requirements
1. User Registration
2. User Login
3. User Logout
4. Create Recipe
5. Edit Recipe
6. requirement
7. requirement
8. requirement
9. requirement
10. requirement
11. requirement
12. requirement
13. requirement
14. requirement

<using the syntax [](images/ui1.png) add images in a folder called images/ and place sketches of your webpages>

## Non-functional Requirements
1. non-functional
2. non-functional

## Use Cases <Add name of who will write (this specific requirement) and implement (in subsequent milestones) the use case below>

1. Use Case Name: User Registration (Written and will be implemented by Eric)

Pre-condition:
Visitor is not logged in and has a valid email address.

Trigger:
Visitor clicks “Sign Up” on the website.

Primary Sequence:
	1.Visitor accesses the registration page and fills in username, email, and password.
	2.Visitor submits the registration form.
	3.System validates the data and creates a new user account.
	4.System logs the user in or redirects them to the login page.

Primary Postconditions:
	A new user account is created and stored in the system.

Alternate Sequence:
	1.Email already exists: System notifies user and suggests logging in.
	2.Weak password: System asks for a stronger password.
	3.Missing fields: System prompts user to complete all required inputs.
	4.Server error: System shows failure message and retry option.

2. Use Case Name: User Logins (Written and will be implemented by Eric)

Pre-condition:
User has an existing account with valid email and password.

Trigger:
User clicks the “Login” button from the homepage or any restricted page.

Primary Sequence:
1.User enters their email and password on the login form.
2.User submits the form.
3.System verifies the credentials.
4.If valid, system logs the user in and redirects to the dashboard.

Primary Postconditions:
	User is authenticated and has access to protected features.

Alternate Sequence:
	1.Invalid email or password: System displays an error message.
	2.Empty fields: System prompts user to fill in required inputs.
	3.Account inactive: System informs user and provides help link.
	4.Technical issue: System suggests retrying later.

3. Use Case Name: User Logout (Written and will be implemented by Eric)

Pre-condition:
User is currently logged in.

Trigger:
User clicks the “Logout” button from the navigation bar or menu.

Primary Sequence:
	1.User clicks the logout action.
	2.System processes the logout request.
	3.System destroys the user session.
	4.System redirects user to the homepage or login screen.

Primary Postconditions:
User is logged out and no longer has access to protected resources.

Alternate Sequence:
	1.Session already expired: User is redirected to the login page.
	2.Logout fails: System displays an error message and retry option.

4. Use Case Name: Create Recipe (Written and will be implemented by Eric)

Pre-condition:
User must be logged in.

Trigger:
User clicks the “Create Recipe” button or menu item.

Primary Sequence:
	1.User accesses the create recipe form.
	2.User fills in title, description, ingredients, and instructions.
	3.User submits the form.
	4.System saves the recipe and redirects to the recipe detail page.

Primary Postconditions:
A new recipe is stored and visible under the user’s account.

Alternate Sequence:
	1.Missing fields: System prompts user to complete the form.
	2.Invalid input: System highlights errors.
	3.Session expired: User is redirected to login page.
	4.System error: Recipe not saved, and user is asked to retry.

5. Use Case Name: Edit Recipe (Written and will be implemented by Eric)

Pre-condition:
User is logged in and owns the recipe they want to edit.

Trigger:
User clicks the “Edit” button on one of their recipes.

Primary Sequence:
	1.User views their recipe and clicks “Edit.”
	2.System shows a form pre-filled with the recipe’s details.
	3.User updates fields and submits the form.
	4.System validates and saves the changes, then redirects to updated recipe.

Primary Postconditions:
The recipe is updated in the system with the new details.

Alternate Sequence:
	1.User tries to edit a recipe they don’t own: Access is denied.
	2.Invalid input: System highlights errors for correction.
	3.Recipe deleted before submission: System shows error.
	4.System issue: Changes not saved, and user is notified.
