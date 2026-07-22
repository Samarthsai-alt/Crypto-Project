# Crypto-Project
Data Analysis of Crypto Trading
An end-to-end data science analysis evaluating trader performance (PnL, win rate, trade frequency, position sizing, and directional bias) across different market sentiment regimes (**Fear vs. Greed Index**).

---

## 🛠️ Setup & Execution Guide

### 1. Repository Structure

```text
crypto--analysis/
├── data/
│   ├── historical_data.csv       # Executed trade records
│   └── fear_greed_index.csv      # Daily market sentiment index
├── outputs/
│   └── sentiment_performance.png # Output visualizations
├── analysis.ipynb       # Main Python analysis notebook
├── README.md                     # Setup, methodology, & final report
└── requirements.txt              # Required packages
```
### 2. How to Run
```
Follow these steps to set up the environment and execute the analysis on your local machine:

Prerequisites
Make sure you have Python 3.8+ installed on your system along with Git and Jupyter Notebook.
```
###Step 1: Clone the Repository
```
Open your terminal or command prompt and clone the repository:
```
###Step 2: Set Up Virtual Environment (Optional but Recommended)
```
Create and activate an isolated Python environment:

On Windows:  python -m venv venv
              venv\Scripts\activate
On macOS / Linux: python3 -m venv venv
                  source venv/bin/activate
```

###Step 3: Install Required Dependencies
```
Install all required packages from requirements.txt:

pip install -r requirements.txt

(Or install manually: pip install pandas numpy matplotlib seaborn scikit-learn jupyter)
```

###Step 4: Run the Analysis Notebook
```
Start the Jupyter Notebook server:
jupyter notebook
