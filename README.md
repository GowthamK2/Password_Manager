Python Password Manager GUI

A simple and secure desktop application built with Python's tkinter library to generate strong, random passwords and manage them locally.
✨ Features

    Random Password Generation: Create passwords with customizable length and strength (Low, Medium, Strong).

    Clipboard Functionality: Easily copy the generated password to your clipboard using the "Copy" button (requires pyperclip).

    Local Storage: Save login credentials (Username, Website, and Password) directly to a local file named info.txt.

    View Saved Passwords: Display all saved credentials from info.txt in the console.

🛠️ Prerequisites

Before running the application, ensure you have Python installed (Python 3.x recommended).

This project requires the external Python package pyperclip for the copy-to-clipboard functionality.
Installation

You can install the required dependency using pip:

pip install pyperclip

🚀 Getting Started
1. Save the Code

Save the provided Python code into a file named password_manager_gui.py.
2. Run the Application

Execute the script from your terminal:

python password_manager_gui.py

The graphical user interface (GUI) window will open.
💻 Usage

The application window is divided into several areas for generating and saving your passwords:

    Select Length: Use the "Length" dropdown menu to choose the desired password length (8 to 32 characters).

    Select Strength: Choose from Low (lowercase letters only), Medium (mixed case letters), or Strong (mixed case, digits, and special characters) using the radio buttons.

    Generate Password: Click the "Generate" button to instantly create a new password, which appears in the "Generated password" field.

    Copy Password: Click "Copy" to place the generated password on your clipboard.

    Save Credentials:

        Enter the username in the "Enter username here" field.

        Enter the website address in the "Enter website address here" field.

        Click the "Save" button. The username, website, and the current generated password will be appended to the local info.txt file.

    Show All Passwords: Click "Show all passwords" to print the entire contents of your info.txt file directly to the terminal/console where the script is running.

🔒 Data Storage and Security

All your stored passwords are kept locally in a plain text file named info.txt, created in the same directory as the script.

Note on Security: Since this application stores passwords in plain text locally, it is primarily intended for learning and basic local management. For high-security environments, always use professionally audited password managers that employ strong encryption.
