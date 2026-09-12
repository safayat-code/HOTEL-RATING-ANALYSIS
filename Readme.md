# Hotel Reviews Data Analysis

This project analyzes hotel review data and uses basic machine learning to classify hotels into rating categories.

## Project Files

- 'Hotel_Reviews_Project.ipynb' - Main project notebook
- 'data/' - Dataset files
- 'figures/' - Generated graphs and charts
- 'requirements.txt' - Required Python packages
- 'README.md' - Project information

## Requirements

- Python 3.13
- Jupyter Notebook / VS Code
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Setup

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Dataset

Place the Datafiniti Hotel Reviews CSV file inside the `data` folder.

The notebook reads the dataset from:

```text
data/Datafiniti_Hotel_Reviews.csv
```

## Running the Project

1. Open the project folder in VS Code.
2. Activate the virtual environment.
3. Open `Hotel_Reviews_Project.ipynb`.
4. Select the `.venv` Python interpreter/kernel.
5. Run the notebook from the first cell to the last cell.

## What the Project Does

The notebook:

- Loads and checks the hotel review data
- Checks missing values and duplicates
- Cleans unnecessary columns
- Creates hotel-level information
- Calculates average ratings and review counts
- Creates graphs for exploration
- Creates Low, Medium and High rating categories
- Splits the data into training and testing sets
- Applies feature scaling for KNN
- Compares a baseline with KNN and Decision Tree
- Shows accuracy, F1 scores and a confusion matrix

## Expected Output

After running the notebook, the main results should include:

- Cleaned hotel data
- Exploratory graphs
- Rating category distribution
- Model accuracy and classification results
- Confusion matrix
- Model comparison
