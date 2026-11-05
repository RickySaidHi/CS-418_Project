# CS-418_Project

## Setup

1. Clone the repository and open its folder:
   ```bash
   git clone <repository-url>
   cd CS-418_Project
   ```
2. Create a virtual environment:
   ```bash
   python3 -m venv .venv
   ```
3. Activate the virtual environment:
   - macOS/Linux: `source .venv/bin/activate`
   - Windows PowerShell: `.venv\Scripts\Activate.ps1`
4. Install the required packages:
   ```bash
   python -m pip install -r requirements.txt
   ```
5. Start Jupyter:
   ```bash
   jupyter notebook
   ```
6. Open the project notebook and select the `.venv` Python kernel if prompted.
7. Keep the datasets in `data/raw/`. They are ignored by Git because the files are large.
8. When finished, deactivate the environment:
   ```bash
   deactivate
   ```