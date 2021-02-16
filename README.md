# Py_to_Application
Convert Python Code (.py) to Executable Application on Raspberry Pi

## Requirements
Pyinstaller : [link to PyInstaller package](https://pypi.org/project/pyinstaller/)
```
# pip3 install pyinstaller

```

## Convert test.py to Application
```
# pyinstaller test.py

```
### Technical details tested on Raspberry Pi 4 (1GB):
```
102 INFO: PyInstaller: 4.2
102 INFO: Python: 3.7.3
104 INFO: Platform: Linux-5.4.79-v7l+-armv7l-with-debian-10.6
...
```
## Expected output
* pycache
* build
* **dist** _(HERE YOU WILL FIND THE test APPLICATION)_
* test.py
* test.spec
