# user-management-ui-specs
# User Management Screen UI Specification

This document outlines the requirements, UI components, behavior of the page when using these components, and initial display for the user. This document will be used by software developers to develop this user interface.

## Requirements

- **Add New User**
  - Fields for username, display name, phone, email, and user roles should be fillable.
  - There should be an option to specify whether the user is enabled or not.
  - User information should be saved using the "Save User" button.

- **Manage Existing Users**
  - The user list should consist of columns for ID, Username, Email, and Enabled status.
  - Filtering options should be available to search among users.
  - There should be an option to hide disabled users using the "Hide Disabled User" checkbox.

## User Interface Components

- **User List**
  - **ID**: Unique identifier for the user.
  - **Username**: The name of the user.
  - **Email**: The email address of the user.
  - **Enabled**: A boolean value indicating whether the user is enabled.

- **New User Form**
  - **Username**: The name of the user.
  - **Display Name**: The display name of the user.
  - **Phone**: The phone number of the user.
  - **Email**: The email address of the user.
  - **User Roles**: Dropdown menu to select the user role.
  - **Enabled**: Checkbox indicating whether the user is enabled.

- **Buttons**
  - **New User**: Opens the new user form.
  - **Hide Disabled User**: Checkbox to hide disabled users.
  - **Save User**: Saves the new user information.

## Page Behavior

- When the user accesses the page, the existing users list should be displayed.
- Clicking the "New User" button should open the new user form on the right side.
- Clicking the "Save User" button should save the information entered in the form and update the user list.
- When the "Hide Disabled User" option is checked, disabled users should not be displayed in the list.
