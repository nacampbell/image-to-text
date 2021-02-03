# Image to Text
A lightweight Python script for copying text from a screenshot.

## Aims
* Lightweight, non obtrusive - no crazy colours, no click intensive menus
* Quick to use, keyboard shortcut
* Works well most of the time, requiring minimal formatting

## Dependencies
* tkinter
* pyautogui
* pytesseract\*
* pyperclip

\* *Requires [Google Tesseract OCR](https://github.com/tesseract-ocr/tesseract). See [pytesseract installation](https://pypi.org/project/pytesseract/)*

## Usage
1. Start script. **Ctrl + Alt + C**. See keyboard shortcuts.
2. Click and drag crosshair over the desired area.
3. Paste text from clipboard. **Ctrl + V**.



## Setting up keyboard shortcut
### Ubuntu 20.04 (GNOME desktop environment)
1. Open: Settings -> Keyboard Shortcuts
2. Scroll to bottom and press "+"
3. Add the full path to python and the script

   In my case: /usr/bin/python3 /home/myuser/scripts/image_to_text.py   



## Future Development / Known Issues



