# AI-Based Forex Risk Prediction System

## Open in VS Code
1. Extract this ZIP into a normal folder.
2. Open VS Code.
3. Select **File -> Open Folder...** and choose `AI-Based-Forex-Risk-Prediction-System-VSCode`.
4. In the Explorer panel, open `main.py` or any other file.
5. Open **Terminal -> New Terminal** and run the commands below.

## Run on Windows
```powershell
py -m venv .venv
.venv\Scripts\activate
py -m pip install -r requirements.txt
py main.py
```

If PowerShell blocks activation, run:
```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.venv\Scripts\Activate.ps1
```
Then install requirements and run `py main.py`.

## Features
- Tkinter desktop GUI
- Forex trade risk score and Low/Medium/High risk estimate
- Simplified risk amount and position-size estimate
- Optional scikit-learn Random Forest demo classifier
- Saves results to `trade_history.csv` in the current working directory

## Important
Educational demonstration only. The ML model uses synthetic sample data, not verified historical/live Forex data. The app does not connect to a broker and its results are not financial advice. Position sizing is simplified and does not account for pip value, contract size, spread, slippage, margin rules, or account currency conversion.
