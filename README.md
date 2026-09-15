# WindowPet Sprite V3

This version uses the supplied **The Chosen One.png** sprite sheet and the supplied
`pets.json` / `settings.json` structure.

Install:
```powershell
py -m pip install -r requirements.txt
```

Run:
```powershell
py main.py
```

Build EXE:
```powershell
py -m pip install pyinstaller
py -m PyInstaller --noconsole --onedir --add-data "media;media" --add-data "pets.json;." --add-data "settings.json;." main.py
```

F12 = emergency exit.

The program does not close, minimize, move, or modify other applications.
