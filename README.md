# FPS

#Best practice from now on

#Never commit:

venv/
raw datasets
processed datasets
large outputs

#Commit only:

notebooks
src/
README.md
requirements.txt
small config files

testing


📊 FPS Cheating Impact Analysis

This project analyzes the impact of cheating in first-person shooter (FPS) games on player engagement, retention, and potential revenue. Using a combination of real-world datasets and synthetic modeling, the goal is to simulate how increasing cheating rates can affect player behavior and business performance.

The project leverages data analysis techniques in Python, along with SQL and data visualization, to replicate a real-world analytics workflow—from raw data ingestion to actionable insights.

🔧 Project Setup

This project was developed using a local Python environment and version-controlled with GitHub.

1. Clone the Repository
git clone https://github.com/yourusername/your-repo.git
cd your-repo
2. Create Virtual Environment

A virtual environment was created to isolate project dependencies:

python3 -m venv venv

Activate the environment:

source venv/bin/activate
3. Install Dependencies

Install required Python packages:

pip install -r requirements.txt

If running for the first time:

pip install pandas numpy matplotlib jupyter ipykernel
4. Set Up Jupyter Notebook Kernel
python -m ipykernel install --user --name=fps-venv --display-name "Python (fps-venv)"

Then select the Python (fps-venv) kernel in your notebook.

5. Project Structure
.
├── data/
│   ├── raw/          # Original datasets (not tracked in Git)
│   └── processed/    # Cleaned datasets
├── notebooks/        # Jupyter notebooks for analysis
├── src/              # Python scripts
├── images/           # Visual outputs
├── README.md
├── requirements.txt
└── .gitignore
6. Data Management

Due to file size constraints, raw datasets are not stored in this repository.

To run this project:

Download datasets from external sources (e.g., Kaggle)
Place them in:
data/raw/
7. Version Control Notes
Virtual environment (venv/) is excluded via .gitignore
Large datasets are not tracked
Dependencies are stored in requirements.txt for reproducibility