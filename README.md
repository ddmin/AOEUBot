# AOEUBot
Uses PyTesseract, PIL, and PyAutoGUI to automatically type words in the online typing test AOEU.

[Proof of Concept](https://www.youtube.com/watch?v=_5p4L-x_o2k)

# Requirements
Install dependencies using pip.
```python
pip install -r requirements.txt
```

You might also have to install Tesseract and direct the program to the location of tesseract.exe.
```python
pytesseract.pytesseract.tesseract_cmd = 'C:\\Program Files (x86)\\Tesseract-OCR\\tesseract.exe'
```

Note: This program does not work in Linux, and this has only been tested in Windows.
