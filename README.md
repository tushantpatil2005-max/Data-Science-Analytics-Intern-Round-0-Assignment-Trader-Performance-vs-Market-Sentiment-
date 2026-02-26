Project Overview
This project investigates the relationship between Bitcoin market sentiment (Fear/Greed Index) and trader behavior/performance on the Hyperliquid DEX. By merging sentiment scores with execution data, we identify behavioral archetypes and propose data-driven trading strategies to optimize risk management during extreme market regimes.

Project Structure
Plaintext
├── analysis_notebook.ipynb   # Main analysis, cleaning, and visualizations
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
└── data/                      # Place source CSVs here (if not in root)
    ├── bitcoin_sentiment.csv


Setup & Installation
1. Prerequisites
Ensure you have Python 3.9+ installed.

2. Environment Setup
It is recommended to use a virtual environment to avoid dependency conflicts:

# Create virtual environment
python -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Activate (Mac/Linux)
source venv/bin/activate

3. Install Dependencies

pip install -r requirements.txt
Key libraries used: pandas, numpy, matplotlib, seaborn, scipy.

How to Run
Prepare Data: Ensure both CSV files are located in the root folder or update the file paths in the first cell of the notebook.

Open Notebook: ```bash
jupyter notebook analysis_notebook.ipynb

Run All Cells: The notebook is structured to run sequentially:

Part A: Data preparation, cleaning, and metric engineering.

Part B: Statistical analysis and visualization.

Part C: Strategic output and "Rules of Thumb."

