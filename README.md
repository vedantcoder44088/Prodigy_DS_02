## Prodigy_DS_02

## Overview:
This repository contains the code and analysis performed during my internship project at Prodigy. The notebook `Prodigy_DS_02.ipynb` showcases data analysis and predictive modeling tasks using Python.

## Getting Started:
1. **Clone the Repository**:
   ```
   git clone https://github.com/vedantcoder44088/Prodigy_DS_02.git
   ```

2. **Navigate to the Project Directory**:
   ```
   cd Prodigy_DS_02
   ```

3. **Install Required Libraries**:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

4. **Download the Dataset**:
   Download the dataset named `train.csv` and place it in the project directory.

## Project Steps:
- **Data Loading and Exploration**: Loaded the dataset into a pandas DataFrame and explored its structure and summary statistics.
- **Data Visualization**: Utilized seaborn to create count plots to visualize the distribution of `Survived`, `Pclass`, and `Sex` variables.
- **Data Preprocessing**: Encoded categorical variable `Sex` using LabelEncoder.
- **Model Training**: Built a logistic regression model using scikit-learn to predict survival based on passenger class (`Pclass`) and sex (`Sex`).
- **Model Evaluation**: Split the dataset into training and testing sets, trained the model, and evaluated its performance.
- **Prediction**: Made a prediction on a sample input to determine survival outcome.

## Requirements:
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage:
- Open the Jupyter Notebook `Prodigy_DS_02.ipynb` to view the project documentation and code.
- Execute each cell of the notebook to reproduce the analysis and results.

## License:
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
