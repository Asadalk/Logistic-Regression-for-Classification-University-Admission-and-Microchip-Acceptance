# Logistic-Regression-for-Classification-University-Admission-and-Microchip-Acceptance

This project implements logistic regression for two datasets using Python and NumPy. The first dataset (`ex2data1.txt`) involves predicting university admission based on exam scores, while the second dataset (`ex2data2.txt`) requires predicting microchip acceptance based on two test scores.

## Project Structure

The project is structured as follows:

- **Data Handling**:
  - Utilizes `load_data` function to load datasets from text files (`ex2data1.txt`, `ex2data2.txt`).
  - Implements `plot_data` function to visualize datasets.

- **Logistic Regression Functions**:
  - **Sigmoid Function**: Computes the sigmoid of a given input.
  - **Cost Function**: Computes the logistic regression cost function.
  - **Gradient Function**: Computes gradients for logistic regression.
  - **Gradient Descent**: Implements batch gradient descent to learn model parameters.

- **Regularization**:
  - For the second dataset (`ex2data2.txt`), regularization is applied to prevent overfitting.
  - Regularized cost and gradient functions (`compute_cost_reg`, `compute_gradient_reg`) are implemented.

- **Training and Evaluation**:
  - Trains logistic regression models using gradient descent on both datasets.
  - Evaluates model accuracy on training data using the `predict` function.

- **Visualization**:
  - Plots decision boundaries and data points using Matplotlib.
  - Provides visual insights into how the models classify data.

## Files and Functions

- **utils.py**: Contains utility functions including data loading (`load_data`) and plotting (`plot_data`).
- **logistic_regression.py**:
  - Implements core logistic regression functions (`sigmoid`, `compute_cost`, `compute_gradient`).
  - Includes regularized logistic regression functions (`compute_cost_reg`, `compute_gradient_reg`).
  - Executes gradient descent (`gradient_descent`) and prediction (`predict`) functions.

- **Main Script**:
  - Executes logistic regression on both datasets.
  - Demonstrates model training, evaluation, and visualization.

## Requirements

- Python 3.x
- NumPy
- Matplotlib

## Usage

1. Ensure Python and required libraries are installed.
2. Clone the repository or download the project files.
3. Run the main script or explore individual functions as needed.
   
   ```bash
   python main_script.py
   ```

4. Adjust hyperparameters such as learning rate (`alpha`) and regularization parameter (`lambda_`) for experimentation.

## Contributing

Feel free to contribute to this project by forking and submitting pull requests. Suggestions, improvements, and bug fixes are welcome!

## Credits

- This project was developed by Faizal.
