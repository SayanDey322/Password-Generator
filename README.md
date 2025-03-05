Password Generator Project
This repository contains two versions of a password generator implemented in Python: a simple version and an advanced version. Both versions allow users to generate secure and customizable passwords.
Project Overview
Simple Password Generator
The simple password generator creates a random password based on user-defined inputs for the number of letters, symbols, and numbers. It uses basic randomization to provide a secure password.

Features:
User-defined password length (letters, symbols, numbers).
Randomly generated password.
Displays the generated password in the console.
Advanced Password Generator
The advanced password generator includes additional options for creating more complex and secure passwords. It offers the ability to specify complexity levels and save passwords to a file.

Features:
User-defined password length (letters, symbols, numbers).
Options for password complexity (low, medium, high).
Ability to save the generated password to a file.
Randomly generated password with higher security options.
How to Use
Clone the repository:

git clone https://github.com/prantikm07/Password-Generator.git
cd password-generator
Run the simple password generator:

python passgen_simp.py
Run the advanced password generator:

python passgen_adv.py
Follow the prompts to enter your preferences for password generation.

Requirements
Python 3.x
Example Usage
For the Simple Password Generator:

Welcome to the PyPassword Generator!... 
How many letters would you like in your password? 
> 6 
How many symbols would you like? 
> 2 
How many numbers would you like? 
> 3 
Your generated password is: G5!h1$C2aD
For the Advanced Password Generator:

Welcome to the PyPassword Generator!
How many letters would you like in your password?
> 8
How many symbols would you like?
> 2
How many numbers would you like?
> 3
Choose a complexity level (low, medium, high):
> high
Would you like to save the generated password to a file? (yes/no):
> yes
Your generated password is: J8&X6@Qe
Password saved to 'generated_password.txt'.
License
This project is open-source and available for modification and distribution.
