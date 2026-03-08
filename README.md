# Employment Scam Detection (GovTech Assessment)

A machine learning project that predicts potentially fraudulent recruitment postings using the EMSCAD dataset. The system identifies patterns associated with scam job ads so they can be flagged for manual review before reaching job seekers.

## Setup

1. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset** (not included due to size). Place `DataSet.csv` in the project root. You can find the EMSCAD/recruitment scam dataset on [Kaggle](https://www.kaggle.com/datasets/amruthjithrajvr/recruitment-scam).

## Project Structure

| File / Folder | Description |
|---------------|-------------|
| `my_notebook.ipynb` | Full analysis, EDA, and model training |
| `report/report.pdf` | Summary report |
| `requirements.txt` | Python dependencies |

## Usage

Open and run `my_notebook.ipynb` in Jupyter to explore the analysis and reproduce the results.
