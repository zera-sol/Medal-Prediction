# Olympic Medal Prediction

This project predicts the number of medals each country will win in the Olympics, using a **linear regression** machine learning model. The goal is to analyze historical data on Olympic performance to identify factors that contribute to medal counts, helping in making educated predictions.

## Project Overview

Using Python and the **scikit-learn** library, this project:
- Prepares and cleans Olympic historical data.
- Trains a linear regression model to predict medal counts.
- Calculates the model's accuracy and evaluates the results using the **Mean Absolute Error (MAE)**.

By exploring relationships between factors (like the number of athletes and previous medals won), this model aims to make reliable predictions for each country’s potential Olympic success.

## Project Setup

1. **Clone the Repository**:
   Clone this GitHub repository to your local machine:
   git clone https://github.com/zera-sol/Medal-Prediction.git

2. **Install Required Libraries**:
   Use `pip` to install necessary libraries:
   pip install pandas numpy scikit-learn

3. **Run the Project**:
   This project can be run in **Google Colab** or **Jupyter Notebook**. Load the data file and run the cells to train the model and make predictions.

## Project Structure

Medal-prediction/
│
├── team.csv        
├── Medal-prediction.ipynb  
└── README.md             

## Data Description

The dataset includes historical information on Olympic teams from various countries, including:
- `team`: Team abbreviation
- `country`: Country name
- `year`: Year of Olympic event
- `athletes`: Number of athletes
- `age`: Average age of athletes
- `height`: Average height of athletes
- `prev_medals`: Number of medals won in previous Olympics
- `medals`: Actual medals won in the given year

## Model Training & Evaluation

1. **Data Preprocessing**:
   - Remove missing values.
   - Normalize/scale data if necessary to improve model accuracy.

2. **Training**:
   - A **linear regression** model is trained on a portion of the data, while another portion is used for testing.

3. **Evaluation**:
   - The **Mean Absolute Error (MAE)** is calculated to measure prediction accuracy.
   - Lower MAE values indicate better model performance.

4. **Interpreting MAE**:
   - MAE is compared with the standard deviation of the `medals` column to determine prediction quality relative to data variability.

## Results

The model’s performance is evaluated based on how well it can predict the medal count with a low MAE compared to the target's standard deviation. This approach helps assess whether the predictions are reliable for the project goals.
## Contact

For questions or suggestions, feel free to reach out:
- **Email**: zedomanwithjesu1994@gmail.com
- **GitHub**: [zera-sol](https://github.com/zera-sol)

