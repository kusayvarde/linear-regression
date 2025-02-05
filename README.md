# Linear Regression on Insurance Dataset

This project demonstrates a linear regression model to predict insurance charges based on various features such as age, sex, BMI, number of children, smoking status, and region.

## Project Structure
├── insurance.csv ├── model.ipynb └── README.md


- `insurance.csv`: The dataset containing insurance information.
- `model.ipynb`: Jupyter notebook containing the code for data analysis, preprocessing, model training, and evaluation.
- `README.md`: Project documentation.

## Dataset

The dataset `insurance.csv` contains the following columns:
- `age`: Age of the primary beneficiary.
- `sex`: Gender of the primary beneficiary.
- `bmi`: Body mass index, providing an understanding of body fat.
- `children`: Number of children/dependents covered by health insurance.
- `smoker`: Smoking status of the primary beneficiary.
- `region`: Residential area in the US (northeast, southeast, southwest, northwest).
- `charges`: Individual medical costs billed by health insurance.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/kusayvarde/linear-regression.git
    cd linear-regression
    ```

2. Install the required dependencies:
    ```sh
    pip install skilearn
    pip install seaborn
    pip install pandas
    pip install numpy
    pip install matplotlib
    ```

## Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook model.ipynb
    ```

2. Run the cells in the notebook to perform data analysis, preprocessing, model training, and evaluation.

## Results

The model's performance is evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score
