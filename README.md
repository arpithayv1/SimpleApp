# Espresso UI Testing for Simple Login Page

## Overview
This project demonstrates the use of Espresso, a UI testing tool, to perform end-to-end testing on a simple Android login page. The test ensures that the login functionality works correctly by simulating user interactions and verifying the outcomes.

## Objectives
- **Test Login Functionality:** Validate that users can successfully log in with correct credentials.
- **UI Interaction Testing:** Simulate user input, button clicks, and form submission.
- **End-to-End Validation:** Ensure that the entire login process, from input to verification, works as expected.

## Technologies Used
- **Espresso:** A powerful Android UI testing framework for writing concise and reliable tests.
- **Java/Kotlin:** The programming languages used for both the Android application and the Espresso tests.
- **Android Studio:** The IDE for developing and running the Android application and tests.

## Test Description
- **Login Test:** 
  - Input valid credentials into the username and password fields.
  - Click the login button.
  - Verify that the user is redirected to the correct page upon successful login.
  - Test with incorrect credentials to ensure the login fails and an error message is displayed.

## Test Cases

### 1. Checking Login Success
- **Purpose:** Verifies that the login is successful when valid credentials are provided.
- **Process:** Enters a valid email and password, clicks the login button, and checks for a success message.

### 2. Checking Login Failure
- **Purpose:** Ensures that the login fails when incorrect credentials are provided.
- **Process:** Enters an invalid email and correct password, clicks the login button, and checks that the success message does not appear.

