# Password Strength Tester and Cracker

## Project Overview
Hey there! This is my **Password Strength Tester and Cracker** project built with **Java**. With this tool, you can generate random passwords, check how strong your passwords are, and even see how easily a weak password could be cracked using a brute-force method.

## Features
- **Enter Your Own Password** – Type in any password and check its strength.
- **Generate Strong Passwords** – Let the tool create secure, random passwords for you.
- **Analyze Strength** – It looks at the length and variety of characters to tell you how strong your password is.
- **Brute-force Simulation** – It shows how long it might take to crack a password using brute force, just to demonstrate how secure (or insecure) it is.

## Installation
Here’s how to get it up and running:

1. **Clone the repo**:
    ```bash
    git clone https://github.com/mishraShilpa-28/pwd-strength-tester-and-cracker.git
    cd pwd-strength-tester-and-cracker
    ```

2. **Compile the Java files**:
    ```bash
    javac -d bin src/*.java
    ```

3. **Run the program**:
    ```bash
    java -cp bin PasswordTool
    ```

## Usage
1. Start the app.
2. Pick one of the options from the menu:
    - **Check Password Strength** – Enter a password to analyze it.
    - **Crack Password** – Simulates cracking the one you entered.
    - **Generate Random Password** – Just give it a length and it’ll generate, check, and crack it for fun.

## Code Structure
Here’s a quick breakdown of how the code is organized:

- **PasswordGenerator.java** – Builds secure, random passwords.
- **PasswordStrengthChecker.java** – Evaluates password strength.
- **PasswordCracker.java** – Handles the brute-force cracking simulation.
- **PasswordTool.java** – The main file that brings everything together.

## Contributing
Wanna help out? Awesome!

1. Fork the repo.
2. Make a new branch:
    ```bash
    git checkout -b your-feature-branch
    ```
3. Commit your updates:
    ```bash
    git commit -m "Added something cool"
    ```
4. Push your branch:
    ```bash
    git push origin your-feature-branch
    ```
5. Then open a Pull Request. I’ll check it out!

## License
This project uses the MIT License – feel free to use or build on it.

## Acknowledgements
Big thanks to anyone contributing or just checking it out. Shout out to the open-source community for all the inspiration!
