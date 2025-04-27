# Project Name

## Overview
Short description of the project.
- What problem are you solving?
- What's the goal of the project?

## Project Structure
   ```
   ├── README.md          # Project overview and instructions
   ├── .gitignore         # Files and folders to ignore
   ├── requirements.txt   # Python package dependencies
   ├── data/
   │   ├── raw/           # Original, immutable data dumps
   │   └── processed/     # Cleaned and transformed datasets
   ├── notebooks/         # Jupyter notebooks for exploration and prototyping
   ├── src/               # Source code (functions, classes, scripts)
   ├── outputs/
   │   ├── figures/       # Visualizations
   │   └── reports/       # Model evaluations, reports
   ```

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mcoveney/python-ds-template.git new-project-name
   cd new-project-name

2. ** Create new github repo:**
   ```bash
   gh repo create new-project-name --public --source=. --remote=origin --push

3. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate

4. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt

