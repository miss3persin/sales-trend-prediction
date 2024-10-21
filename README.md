This project demonstrates the usage of a **Random Forest Regressor** for predicting product sales based on various factors like store number, product family, and date.

## Features
- Interactive input for store and product information.
- Model trained using **Random Forest** and evaluated with metrics like MAE, MSE, and R².
- Includes cross-validation for better evaluation.

## Setup Instructions
1. Clone the repository:  
   `git clone https://github.com/your-username/your-repo-name.git`
2. Install necessary dependencies (if applicable).
3. Run the model script.

## Usage
The model will prompt for:
- Store number
- Product family
- Promotion status
- Date of sale (YYYY-MM-DD)

Example command:
```
- Enter store number: 1
- Enter product family: AUTOMOTIVE
- Is the product on promotion? (1 for Yes, 0 for No): 0
- Enter date (YYYY-MM-DD): 2013-01-01
```

The model will predict the product sales based on the input provided.

## Evaluation Metrics
- **MAE**: Mean Absolute Error
- **MSE**: Mean Squared Error
- **R²**: Coefficient of Determination

## License
This project is licensed under the MIT License.
