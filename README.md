# Wifi_interruption_analyzer
Measures how much and how long the internet connection is interrupted for a certain period of time

## Requirements
-Python 3
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install any dependencies.
-requests library: ```pip install requests ```

## Usage
Your device must be ON for the full duration of the running of the script.
Clone the repository to a local folder, then open cmd in that folder.
run: ```python wifi_interrupt_measure.py ```

NOTE: If you want to run the script for more than 1 day, you have to comment out the 'if statement' preventing it at around line 149 of the code.
