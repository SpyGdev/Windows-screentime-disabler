# Windows-screentime

A simple Windows utility to kill the `WpcUapApp.exe` process every second. This script can also be configured to run on startup and can be stopped at any time.

## Features

* Starts killing the `WpcUapApp.exe` (aka Screen Time Agent) process every second.
* Can be stopped at any time.
* Option to add or remove the script from Windows startup.

## Usage

1. **Start Script**: Click the "Start Script" button to begin killing the process.
2. **Stop Script**: Click the "Stop Script" button to stop the process.
3. **Start on Boot**: Adds the script to Windows startup, so it runs automatically on startup.
4. **Remove from Boot**: Removes the script from startup, so it won't run on startup.

## Requirements

* Python 3.x
* tkinter (usually included with Python)
* Access to Windows registry (for startup functionality)

## License

This project is licensed under the MIT License.
