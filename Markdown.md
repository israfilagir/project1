# User Management Screen Specification

## Requirements:
•	Display a table of users with their relevant information.
•	Allow adding a new user with the specified fields.
•	Provide the ability to enable or disable a user.
•	Allow hiding disabled users.
•	Provide options for selecting user roles.
•	Save user data after modifications.

## UI Components and Behavior:
### 1.	Table:
•	The table should have the following columns: ID, User Name, Email, and Enabled.
•	Each row represents a user and displays their corresponding data.
•	The table should be populated with existing user data from the backend.
•	Disabled users should be hidden if the "Hide disabled user" option is selected.
### 2.	New User Section:
•	Provide input fields for the following user information: Username, Display Name, Phone, and Email.
•	Use a dropdown or checkbox group to select user roles (Guest, Admin, SuperAdmin).
•	Initially, all fields in this section should be empty, and no roles should be selected.
### 3.	Enabled Checkbox:
•	Use a checkbox to indicate the enabled status of the user.
•	The checkbox should be unchecked by default for new users.
### 4.	Save User Button:
•	Clicking the "Save User" button should trigger the saving process of the user's information.
•	If a new user is being created, the entered data should be saved as a new user entry in the table.
•	If an existing user is being modified, the changes should be updated in the corresponding row of the table.
### 5.	User Roles:
•	When the "Select user roles..." dropdown or checkbox group is clicked, show a list of available user roles.
•	Allow selecting one or more user roles for the new user.
Initial Page View:
•	The table should display the existing users' data, including their IDs, Usernames, Emails, and Enabled status.
•	The "Hide disabled user" option should be unchecked by default, displaying all users, regardless of their enabled status.
•	The "New User" section should be empty, with all fields and checkboxes cleared.
•	No user roles should be selected initially.
•	The "Save User" button should be present but disabled until the required user information is entered.


# This part is the interface of the project designed using Markdown.
+New User       
- [X] Hide disabled user                       
[Save User]               


| ID  | User Name   | Email                              | Enabled |
|-----|-------------|------------------------------------|---------|
| 1   | AdminUser   | <span>john</span>@example.com      | Yes     |
|**2**|**Test User**| **<span>jane</span>@example.com**  |**No**   |



## New User

Username: [     ]  
Display Name: [     ]  
Phone: [     ]  
Email: [     ]  
User Roles: [Select user roles...] 
- [ ] Guest  
- [ ] Admin  
- [ ] SuperAdmin

Enabled:
- [ ] enable



