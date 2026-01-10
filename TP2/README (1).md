# Python workspace setup

This workspace is configured to use a local virtual environment located at `.venv`.

Quick start (PowerShell):

1. Activate the venv:

```powershell
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies (if any):

```powershell
pip install -r requirements.txt
```

3. Run the main script:

```powershell
python main.py
```

4. Debug in VS Code:
   - Open the file you want to run and press F5 or select the "Python: Current File" configuration in the Run view.

Notes:
- The workspace sets `python.defaultInterpreterPath` to the venv interpreter so VS Code should pick it automatically.
