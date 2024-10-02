# Password Complexity Checker

This application assesses the strength of a password based on criteria such as length, presence of uppercase and lowercase letters, numbers, and special characters. It provides users with feedback on the password's strength and offers suggestions for improvement. The application includes a dynamic strength meter that visually represents the password's strength percentage.

## Features

- Checks password strength based on multiple criteria.
- Displays a percentage meter indicating the strength of the password.
- Provides detailed feedback and suggestions for improvement.
- Maintains a history of previously checked passwords.
- User-friendly GUI built with Tkinter.

## Requirements

- Python 3.12
- `tkinter`

**How It Works**

The application evaluates the strength of the entered password based on the following criteria:

- Length (minimum 8 characters)

- At least one uppercase letter

- At least one lowercase letter

- At least one numeric digit

- At least one special character (e.g., !@#$%^&*())

The password strength is categorized as Weak, Moderate, or Strong, with corresponding feedback provided.
