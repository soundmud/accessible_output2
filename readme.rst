This is a copy of accessible_output2 0.16 with a few patches:

- Windows: an application frozen with cx_Freeze works without additional configuration
- Linux: fixed eSpeak support
- Linux: added SpeechDispatcher support (experimental, not activated)

Tested on:

- Windows 10 with Python 3.8 (SAPI5, NVDA)
- Debian 10 with Python 3.7 (python3-espeak, orca)

Original accessible_output2:

- on Pypi: https://pypi.org/project/accessible-output2/
- on GitHub: https://github.com/accessibleapps/accessible_output2