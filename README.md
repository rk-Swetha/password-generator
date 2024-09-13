# Password Generator Master 🔒
A Java-based password generator and strength checker designed to help users create secure passwords and evaluate their strength. This project features a console-based interface for generating random passwords and checking the strength of existing passwords.

# Features:
- Password Generation: Generate passwords with customizable options for including uppercase letters, lowercase letters, numbers, and symbols.
- Password Strength Check: Evaluate the strength of a password based on common security practices.
- Interactive Console Interface: User-friendly text-based menu to interact with the application.

# Technologies Used:
- Java
- JUnit 5 (for unit testing)

# Project Structure:
- Main.java: The entry point of the application, initiating the password generator and starting the main loop.
- Alphabet.java: Defines the character sets (uppercase, lowercase, numbers, symbols) used for password generation.
- Generator.java: Manages user interactions, password generation, and strength checking.
- Password.java: Represents a password and provides methods to evaluate its strength.
- GeneratorTest.java: Contains unit tests for the Generator and Alphabet classes.

# How to Run:
- Compile the Java files:
    javac Main.java Alphabet.java Generator.java Password.java GeneratorTest.java

- Run the main program:
    java Main
  
- Run the tests (requires JUnit 5): Ensure you have JUnit 5 configured in your project. Use your IDE or build tool to execute GeneratorTest.java.

# Usage:
- Password Generator:
    - Choose options to include lowercase letters, uppercase letters, numbers, and symbols.
    - Specify the desired length of the password.
    - The application will generate and display the password.

- Password Strength Check:
    - Enter an existing password.
    - The application will assess and display the strength of the password based on security guidelines.

- Password Strength Evaluation:
     - The Password class evaluates the password strength based on:
        - Variety of character types used (uppercase, lowercase, numbers, symbols).
        - Password length.

- Strength scores and feedback:
  - 6: Very good password.
  - 4-5: Good password.
  - 3: Medium password.
  - 0-2: Weak password.

# Future Enhancements:
- Develop a graphical user interface (GUI) for enhanced user experience.
- Incorporate additional password strength criteria and checks.
- Add support for multiple languages and localization options.

# Contributions:
Feel free to contribute to the project or suggest improvements. For any issues or feature requests, please open an issue on the GitHub repository.
