Name:SK ARIEF AHMED  
Company:CODETECHIT SOLUTIONS
ID:CT08PD924
Domain:CYBERSECURITY & ETHICAL HACKING
Duration:May to June 2024
Mentor:G.Sravani




Project Overview: Password Strength Checker
Objective:

The goal of this project is to develop a tool that evaluates the strength of passwords based on several criteria. The tool provides feedback on the password's strength, helping users to create more secure passwords.
Features:

    Length Assessment: Evaluates the password length and assigns a score.
    Complexity Assessment: Checks for the inclusion of different character types (uppercase, lowercase, digits, special characters) and assigns a score.
    Common Password Check: Compares the password against a list of common passwords and penalizes accordingly.
    Repetition and Sequence Check: Detects repeated characters and common sequences, penalizing the password's score.
    Strength Classification: Based on the total score from all checks, the password is classified as "Weak", "Moderate", "Strong", or "Very Strong".
    Feedback Provision: Offers detailed feedback on each aspect of the password, indicating strengths and weaknesses.

Implementation Details:

    Language: C++
    Libraries Used: Standard C++ libraries (iostream, string, vector, regex, algorithm)

Components:

    Common Passwords List: A predefined list of common passwords that are easily guessable.

    Functions:
        checkLength(const string&): Evaluates the length of the password.
        checkComplexity(const string&): Checks for the presence of different character types and provides feedback.
        checkCommonPasswords(const string&): Checks if the password is common.
        checkRepetitionAndSequences(const string&): Checks for repeated characters and sequences.
        assessPasswordStrength(const string&): Combines all checks to calculate the total score, classify the password strength, and provide feedback.

    Main Function:
        Accepts user input for the password.
        Calls assessPasswordStrength to evaluate the password.
        Outputs the score, strength classification, and detailed feedback.

Example Usage:

    Input: A password string entered by the user.
    Output:
        Score: Numerical value representing the total score from all checks.
        Strength: Classification (Weak, Moderate, Strong, Very Strong).
        Feedback: Detailed feedback on length, complexity, commonality, and repetition/sequences.

Example:

    Password: Password123!
    Output:
        Score: 4
        Strength: Strong
        Feedback: Length: 2/3, Complexity: Includes lowercase letters, Includes uppercase letters, Includes digits, Includes special characters, Common: Password is unique, Repetition/Sequences: Password has no repetition or sequences

Benefits:

    Helps users create more secure passwords by providing clear and actionable feedback.
    Enhances security by discouraging the use of common and easily guessable passwords.
    Encourages the use of complex and diverse character sets in passwords.

This project serves as a foundational tool for improving password security and can be further expanded with more features, such as integrating with a database of breached passwords or providing real-time feedback during password creation.
