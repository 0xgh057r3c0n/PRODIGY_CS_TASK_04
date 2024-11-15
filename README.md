# Keylogger GUI

A simple keylogger application with a graphical user interface (GUI) built using Python's Tkinter library and the `pynput` library for keypress detection. This program allows you to capture keystrokes, display them in real-time, and save them to a file.

### Features:
- **Terms and Conditions**: Displays a terms and conditions window on startup that users must accept to proceed.
- **Keylogging**: Captures all keyboard inputs and displays them in real-time in a text box.
- **File Saving**: Allows users to choose a file to save captured keystrokes.
- **Logging Control**: Start and stop logging with the click of a button. Clear the logs when necessary.
- **Full-Screen Mode**: Toggle full-screen mode with a button or the Escape key.
- **Simple UI**: Easy-to-use interface with status labels and buttons to control logging functionality.

### Requirements:
- Python 3.x
- `pynput` library
- Tkinter library (comes with Python standard library)

### Installation:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/0xgh057r3c0n/PRODIGY_CS_TASK_04.git
    cd PRODIGY_CS_TASK_04
    ```

2. **Install the dependencies**:
    If you don't have `pynput` installed, run the following command:
    ```bash
    pip install pynput
    ```

3. **Run the program**:
    Execute the script:
    ```bash
    python task4.py
    ```

### Usage:

1. **Terms and Conditions**: 
   - On the first launch, you will be prompted to accept the terms and conditions.
   - You must click "Accept" to proceed; otherwise, the program will exit.

2. **Keylogging**: 
   - After accepting the terms, the main window will appear.
   - Click the **Start Logging** button to begin capturing keystrokes. Keystrokes will be displayed in the text box and saved to a file.
   - Click **Stop Logging** to stop the logging process.

3. **Saving Logs**: 
   - Use the **Choose File** button to select a file where keystrokes will be saved.
   - Logs will be appended to the chosen file.

4. **Clearing Logs**: 
   - You can clear the displayed keystrokes in the text box by clicking **Clear Logs**.

5. **Toggle Full-Screen Mode**: 
   - Click the **Toggle Full-Screen** button or press the Escape key to switch between full-screen and windowed modes.

### Disclaimer:
- **Legal & Ethical Use**: This software is intended for educational purposes only. Using it to log keystrokes without the consent of the individual being logged is illegal and unethical. Ensure you have permission before running this program.
- The author does not take responsibility for any misuse or illegal activities resulting from the use of this software.

### Author:
- **Author**: 0xgh057r3c0n

### Version:
- **Version**: 1.0

### License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
