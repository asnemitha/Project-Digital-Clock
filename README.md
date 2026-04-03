Digital Clock (PyQt5)

A simple and elegant digital clock application built using Python and PyQt5.
This project displays the current system time in a real-time updating GUI.

*Features:

- Live digital clock (updates every second)
- Clean and minimal user interface
- Center-aligned time display
- Custom styling (green text on black background)

*Technologies Used:

- Python
- PyQt5

*Installation:

1. Clone the repository:

git clone 
https://github.com/asnemitha/digital-clock.git
cd digital-clock

2. Install required package:

pip install PyQt5


How to Run:

Run the following command:
python clock.py

Output

Displays a digital clock in the format:

HH:MM:SS AM/PM


💡 How It Works

- Uses QTimer to update time every second
- Fetches current system time using QTime
- Displays it using QLabel in the GUI

Learning Outcomes:
- Understanding PyQt5 GUI basics
- Working with layouts and widgets
- Implementing real-time updates using timers

Future Improvements:
- Add date display
- Add themes (light/dark mode toggle)
- Add alarm or stopwatch feature

This project was created as a beginner-friendly practice project to understand GUI development in Python.
