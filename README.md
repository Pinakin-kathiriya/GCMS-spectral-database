# GCMS Chemometrics Learning


## Project Overview
Processing real GCMS data from MassIVE repository to understand:
- How GCMS instrument data is structured
- Reading Agilent MassHunter .d folders
- Extracting chemical features

## Data Source

- **Repository:** MassIVE (massbank.eu)
- **Dataset:** MSV000102547
- **License:** CC0 1.0 Universal (Public Domain)
- **Format:** Agilent .d folders

## Learning Notebooks
### 001_reading_multiple_agilent_gcms_files.ipynb

**What it does:**
- Read multiple Agilent GCMS .d folders
- Extract mass spectra data
- Calculate TIC (Total Ion Current)
- Export to CSV for analysis


## Tools Used
- **Rainbow:** Read GCMS data
- **NumPy:** Numerical operations
- **Pandas:** Data manipulation
- **SciPy:** Signal processing (peaks)
- **Matplotlib:** Visualization
