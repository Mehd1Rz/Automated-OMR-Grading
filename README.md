# Automated OMR Grading

This project is an Optical Mark Recognition (OMR) grading system implemented in Python using OpenCV, NumPy, Matplotlib, and Pandas.

## Project Structure

- `omr_grading.ipynb` — main notebook containing the OMR grading implementation.
- `Data/Answer Keys/` — contains the answer key image.
- `Data/Exam Papers/` — contains the exam paper images used for grading.
- `Results/` — contains generated CSV grading results.
- `requirements.txt` — Python dependencies.

## Requirements

Install the required Python packages with:

```bash
pip install -r requirements.txt
```

## Usage

Open `omr_grading.ipynb` in Jupyter Notebook or JupyterLab and run the cells.

The notebook provides functionality to:

- Calculate a score for an individual exam paper.
- Represent the selected answers and their status.
- Save the status of an individual exam paper to CSV.
- Save the status of multiple exam papers to CSV.
- Save scores for multiple exam papers to CSV.

## Input Data

The project expects exam papers in:

`Data/Exam Papers/`

and the answer key at:

`Data/Answer Keys/kild.png`

## Results

Generated CSV files are stored in:

`Results/`

The existing result files in the project are retained as provided.
