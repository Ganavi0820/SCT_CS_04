# Typing Recorder (Safe Demo)

A **safe, local Tkinter application** that records keystrokes only while the app window is focused.  
Intended for **legitimate uses** such as typing practice, debugging input handling, and accessibility testing.

> ⚠️ This application does **NOT** capture global/system-wide keystrokes. It only records typing inside its own window.

---

## Features

- Records keystrokes while the text area is focused.
- Logs timestamp, key symbol, and printable character (if applicable).
- Displays recorded events in a Treeview for real-time monitoring.
- Allows saving logs to a `.txt` file.
- Supports clearing recorded logs.
- Status display showing whether recording is active and if the window is focused.

---

## Requirements

- Python 3 (Tkinter included in most standard installs)
- Standard Python libraries: `tkinter`, `datetime`

---

## Installation

No installation is required beyond having Python 3 installed.

Clone or download this repository and run:

```bash
python typing_recorder.py
