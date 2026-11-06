# CS-418_Project

## Setup

1. Clone the repository and open its folder:
   ```bash
   git clone <repository-url>
   cd CS-418_Project
   ```
2. Download the required CSV datasets from the project data sources. You need these files before running the notebook:
   - `Food_Inspections_20261012.csv`
   - `Business_Licenses_20261105.csv`
   - `CommunityDataSnapshots_Historical_455993172616713182.csv`
   - `Building_Footprints_20261105.csv`
3. Place all three downloaded CSV files in the existing `data/raw/` folder. The folder is included in the repository, but the CSV files are intentionally ignored by Git because they are large, so each group member must download them locally. Do this before creating the environment or running any analysis.
4. Create a virtual environment:
   ```bash
   python3 -m venv .venv
   ```
5. Activate the virtual environment:
   - macOS/Linux: `source .venv/bin/activate`
   - Windows PowerShell: `.venv\Scripts\Activate.ps1`
6. Install the required packages:
   ```bash
   python -m pip install -r requirements.txt
   ```
7. Start Jupyter:
   ```bash
   jupyter notebook
   ```
8. Open the project notebook and select the `.venv` Python kernel if prompted.
9. When finished, deactivate the environment:
   ```bash
   deactivate
   ```