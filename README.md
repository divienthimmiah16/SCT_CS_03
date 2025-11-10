Password Strength Checker
This is a simple Python script that evaluates the strength of a password based on five key criteria. It provides a rating and actionable feedback to help users improve their password security.
Features
 Checks for:
 Minimum length (8 characters)
 At least one uppercase letter
 At least one lowercase letter
 At least one digit
 At least one special character
 Returns a strength score and rating: Weak, Moderate, Strong, or Very Strong
 Offers suggestions to improve password quality
 Easy to run from the command line
How It Works
The script uses regular expressions to analyze the password. Each satisfied condition increases the strength score by one. Based on the total score (0–5), the password is rated accordingly. If any criteria are missing, the script provides specific feedback to guide the user.
Requirements
 Python 3.x
No external dependencies are required.
Usage
 Clone the repository:
git clone https://github.com/your-username/password-strength-checker.git
cd password-strength-checker
 Run the script:
python password_checker.py
 Enter your password when prompted. The script will display the rating and suggestions if applicable.
