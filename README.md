# LNK-Local-Network-Keylogger-
The "Local Network Keylogger" is a Python project designed to silently log keystrokes from a target system within the local network. It operates by capturing keypress events .The project also includes a minimalistic HTTP server implemented using the http.server module, allowing authorized users to remotely access the logged keystrokes.


To run the provided Python code in various operating systems, including Windows, macOS, and Linux, you would typically follow these general steps:

Install Python: Ensure that Python is installed on your system. You can download and install Python from the official Python website: https://www.python.org/downloads/

Install Dependencies: Install the necessary Python packages using pip, the Python package manager. You need to install pynput and pywin32 (for Windows) using the following commands:

bash
Copy code
pip install pynput
pip install pywin32  # Only required for Windows
Save the Code: Save the provided Python code into a file, for example, keylogger.py.

Run the Code:

Windows:

Open PowerShell.
Navigate to the directory containing keylogger.py.
Run the script using Python:
bash
Copy code
python keylogger.py
macOS / Linux:

Open Terminal.
Navigate to the directory containing keylogger.py.
Run the script using Python:
bash
Copy code
python3 keylogger.py
Accessing the Logs:

After running the script, the key logs will be stored in a file named key_log.txt in the same directory as the Python script.
To access the logs remotely, you would need to know the IP address or hostname of the machine running the script and access it through a web browser using the appropriate URL (e.g., http://<IP_address>:8080).




KINDLY NOTICE THAT I WONT BE RESSPONISIBLE FOR THE ACTIONS YOU PERFORM WITH THIS TOOL. NOTE THAT ITS ONLY FOR EDUCATIONAL PURPOSES.
