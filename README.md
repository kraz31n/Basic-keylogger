# Basic-keylogger

# Simple Keylogger in C

## Overview
This project is a simple keylogger written in C that captures keystrokes and logs them to a specified text file. The application runs in the background and does not display a console window, making it discreet.

## Features
- Captures all keystrokes including special keys (Space, Tab, Enter, Escape, Backspace).
- Logs keystrokes in real-time to a specified file.
- Hides the console window to run silently in the background.

## Prerequisites
- Windows operating system
- C compiler (e.g., GCC, MSVC)

## Usage
1. **Set the Log File Path**: 
   Modify the `PATH` definition at the top of the code to specify where you want the keystrokes to be logged.

   ```c
   #define PATH "C:/path/to/your/loggedtext.txt"
   ```

   This is made for educational purposes only

