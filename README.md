# PRODIGY_CS_04
Overview
This is a simple Keylogger implemented in Python as part of my cybersecurity tasks at Prodigy InfoTech. A keylogger is a tool used to record keystrokes entered by a user. This specific keylogger captures keystrokes and saves them in a log file for analysis or monitoring.

Features
Captures keystrokes in the background.
Records keystrokes in a log file.
Runs silently, making it ideal for testing and debugging.
Captures special characters like space, enter, and backspace.
Technologies Used
Python: Primary programming language used to implement the keylogger.
Pynput Library: A Python library used to capture and control input devices (keyboard and mouse).
Installation
To run the keylogger on your local machine, follow the steps below:

1. Clone the repository

git clone https://github.com/your-username/keylogger.git
cd keylogger
2. Install required Python libraries
You’ll need the pynput library to capture keystrokes. Install it using pip:


pip install pynput
3. Run the Keylogger

python keylogger.py
The keylogger will start capturing keystrokes in the background and save them in a log file.

Key Files
keylogger.py: Main script that records the keystrokes.
log.txt: File where the recorded keystrokes are stored.
How it Works
Keystroke Capture: The script listens for keyboard input using the pynput library. Each keystroke, including special characters (space, backspace, etc.), is captured and written into the log file.
Log File: The keystrokes are stored in a file named log.txt. Each key pressed is recorded sequentially.
Usage
This keylogger can be used for:

Debugging: Monitor the behavior of a system or program by capturing user input.
Parental Control: Supervise children’s online activities (ensure proper ethical guidelines are followed).
Note: Always seek consent from users before deploying such software.

Legal Disclaimer
This project is intended for educational purposes only. The developer is not responsible for any misuse of the keylogger. Ensure to use this software ethically and in compliance with local laws.

Future Enhancements
Encrypt the log file to enhance security.
Implement a stealth mode where the keylogger runs as a background process.
