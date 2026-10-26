# CSE-4875: Image Processing Lab

## Installed Software
- Python 3.14
- Visual Studio Code
- Python Extension (Microsoft)
- Jupyter Extension (Microsoft)

## Installed Python Libraries
- `opencv-python` — Image processing
- `numpy` — Array and matrix operations
- `pillow` — Image handling
- `matplotlib` — Image visualization

## Project Environment
- `.venv` — Python virtual environment
- `Images/` — Sample images
- `week 1/` — Image Operations
- `week 2/` — Grey-Level Transformations
- `week 3/` — Spatial Filtering

## How to Start

1. Open the project folder in VS Code.
2. Open the terminal.
3. Activate the virtual environment:

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

4. Open the required `.ipynb` notebook.
5. Click **Select Kernel** and choose `.venv`.
6. Run cells using `Shift + Enter`.

**Note:** Jupyter and `ipykernel` were not confirmed as installed in `.venv`. If the notebook kernel is unavailable, run:

```powershell
python -m pip install jupyter ipykernel
```

```powershell
python -m pip install opencv-python numpy pillow matplotlib jupyter ipykernel

```
