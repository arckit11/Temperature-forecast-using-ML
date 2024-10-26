# Temperature Forecasting Project

This project aims to predict next-day maximum and minimum temperatures in Seoul, South Korea, using machine learning techniques. The dataset used is sourced from the Korea Meteorological Administration's LDAPS model, covering summer seasons from 2013 to 2017.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Key Steps](#key-steps)
- [Results](#results)
- [How to Run the Project](#how-to-run-the-project)
- [License](#license)

## Project Overview

The goal of this project is to develop a model that accurately forecasts the next day's maximum and minimum air temperatures using historical weather data. 

## Dataset

The dataset consists of:
- Next-day forecast data from the LDAPS model.
- In-situ maximum and minimum temperatures.
- Geographic auxiliary variables.

The data spans summer seasons from 2013 to 2017.

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-Learn (including GridSearchCV for hyperparameter tuning)

## Key Steps

1. **Data Preprocessing**
   - Cleaning the data and handling missing values.
   - Removing outliers using the IQR method.
   - Normalizing and standardizing the data.

2. **Exploratory Data Analysis (EDA)**
   - Visualizing data distributions with heat maps and bar graphs.

3. **Dimensionality Reduction**
   - Applying PCA to reduce multicollinearity.

4. **Modeling**
   - Training Linear Regression and Random Forest models.
   - Optimizing hyperparameters with GridSearchCV.

5. **Results**
   - The final predictions are saved in `Next_tmin.csv`.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/temperature-forecasting.git
   cd temperature-forecasting
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## License

This project is licensed under the MIT License.

---

Feel free to modify any sections as needed, and remember to replace `yourusername` in the clone URL with your actual GitHub username!
