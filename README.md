Password Manager

This is a simple password manager application built using Python and the Tkinter library for the GUI. The application allows users to generate secure passwords, save them along with the associated website and email/username, and search for saved passwords.
Features

    Password Generation: The application can generate a random password that includes a combination of letters, numbers, and symbols. The generated password is automatically copied to the clipboard for easy access.

    Password Storage: The application stores the saved passwords in a JSON file named "data.json". Each website and its associated email/username and password are stored as a key-value pair in the JSON file.

    Password Retrieval: The application allows users to search for saved passwords by entering the website name. If the website is found in the data file, the associated email/username and password are displayed in a message box.

    Responsive GUI: The application has a simple and intuitive graphical user interface (GUI) built using the Tkinter library.

Usage

    Run the Python script to start the application.
    Enter the website, email/username, and click the "Generate Password" button to generate a new secure password.
    Click the "Add" button to save the website, email/username, and password in the data file.
    To search for a saved password, enter the website name and click the "Search" button.

Dependencies

The application requires the following Python libraries:

    json
    tkinter
    random
    pyperclip

You can install the required dependencies using pip:

pip install pyperclip
