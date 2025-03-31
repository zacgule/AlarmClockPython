# ⏰ Python Alarm Clock with GUI

A simple yet effective alarm clock application built using Python's Tkinter for the GUI and winsound for sound notifications. Perfect for basic wake-up alerts or reminders!


## ✨ Features
- 🕒 Intuitive GUI time selection with dropdown menus
- ⏰ 24-hour format time picker (hours, minutes, seconds)
- 🔔 Sound notification when alarm triggers
- 🖥️ Real-time console logging
- 🧵 Thread-based alarm checking to prevent UI freeze

## 📋 Prerequisites
- Python 3.x installed
- Tkinter library (usually comes with Python installation)
- Windows OS (required for `winsound` compatibility)
- Basic Python packages (datetime, time, threading)

## 🛠️ Installation
1. Clone the repository and then use cd:


 ```bash
  cd python-alarm-clock


 ```
## 🚀Run the script:

 ``` bash
python alarm_clock.py

 ```
## Set alarm time using dropdown menus:

Hours (00-24) Minutes (00-60) Seconds (00-60)

Click "Set Alarm" button

Console will show current time updates

When alarm time matches current time:

🔔 Sound will play (sound.wav)

Console displays "Time to Wake up" message

## 🔧 Customization
Change Alarm Sound: Replace sound.wav with your own WAV file

UI Modifications: Adjust geometry("400x200") in code for different window sizes

Time Format: Modify strftime("%H:%M:%S") for different time formats

## ⚠️ Limitations
Windows-only due to winsound dependency

Requires WAV format for custom sounds

Single alarm capability (cannot set multiple alarms)

## 🤝 Contributing
Contributions are welcome! Please open an issue or PR for:

Multi-alarm support

Cross-platform compatibility

UI improvements

Additional features

## 📄 License
MIT License - Feel free to use and modify!
