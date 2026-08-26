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

## How to Use

### Prerequisites

```bash
pip install numpy pandas matplotlib rainbow scipy
```

### Run Notebooks

```bash
jupyter notebook
# Open notebook and run cells in order change folder name with actual path and name of .d folders
```

## Key Learnings

1. **Agilent file structure:** .d folders contain multiple files
2. **Rainbow library:** Handles MS data automatically
3. **TIC calculation:** Sum of all intensities
4. **Feature extraction:** Getting meaningful data from raw spectra


**Transparency:**
This project uses AI (Claude) as a learning partner:
- Help with library selection
- Code structure guidance
- Debugging support

**License:** CC0 (same as data)
