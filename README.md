# Power Plant Energy Prediction Using ANN

## Overview

This project uses an Artificial Neural Network (ANN) to predict electrical energy output from a power plant using operational parameters such as temperature, ambient pressure, exhaust vacuum, and relative humidity.

The model learns patterns from historical power plant data and uses them to predict energy output.

## Objectives

- Build an ANN regression model for energy prediction.
- Preprocess and analyze the dataset.
- Train and evaluate the neural network.
- Compare predicted values with actual energy output.

## Technologies Used

- Python
- Jupyter Notebook
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Dataset

The dataset is stored in `powerplant_data.csv`.

The model uses the following input parameters, if present in the dataset:

- Ambient Temperature (AT)
- Exhaust Vacuum (V)
- Ambient Pressure (AP)
- Relative Humidity (RH)

**Target:** Electrical energy output (PE).

## Project Structure

```text
Power-Plant-Energy-Prediction-ANN/
├── ANN_Regression.ipynb
├── powerplant_data.csv
├── best_model.pt
├── README.md
└── .gitignore
```

## Model Workflow

1. Load and explore the dataset.
2. Preprocess the input features and target variable.
3. Split the dataset into training and testing sets.
4. Build an Artificial Neural Network using PyTorch.
5. Train the model on the training data.
6. Generate predictions on the test data.
7. Compare predicted and actual values.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/raghuvanshidhyanvi-ui/Power-Plant-Energy-Prediction-ANN.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Power-Plant-Energy-Prediction-ANN
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas scikit-learn matplotlib torch jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `ANN_Regression.ipynb` and run the cells in order.

## Saved Model

The trained model weights are saved in `best_model.pt`.

The model can be reused for predictions if the same model architecture and preprocessing steps are applied.

## Future Improvements

- Optimize model hyperparameters.
- Evaluate performance using metrics such as MAE, RMSE, and R².
- Develop a web interface for interactive predictions.
- Deploy the model as an application.

## Author

Dhyanvi Raghuvanshi

GitHub: [raghuvanshidhyanvi-ui](https://github.com/raghuvanshidhyanvi-ui)
