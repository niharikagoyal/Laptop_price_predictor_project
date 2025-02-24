**Project Overview**

This project predicts the price of laptops based on various features using Python and machine learning regression models. The dataset is sourced from Kaggle, and the model is trained using libraries like scikit-learn, pandas, and NumPy. The goal is to build a model that can accurately estimate laptop prices based on specifications like RAM, storage, processor, and screen size.

**Tech Stack & Tools**

**Programming Language:** Python

**Libraries:** Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Streamlit

**Algorithms:** Linear Regression, Random Forest, Gradient Boosting, AdaBoost, Extra Trees Regressor

**Pipeline & Preprocessing:** ColumnTransformer, OneHotEncoder

**GUI Framework:** Streamlit (for interactive web UI)

**Dataset:** Kaggle Laptop Price Dataset

**Features**:

Data cleaning and preprocessing (handling null values, removing duplicates)

Feature engineering (extracting information from complex fields like memory and screen resolution)

Exploratory Data Analysis (EDA) with visualizations

Regression modeling and performance evaluation

Interactive GUI for live predictions

**Dataset**

The dataset includes attributes like:

Company

TypeName

RAM

Weight

Screen Resolution (with touchscreen detection)

CPU Brand

Storage (HDD, SSD, Hybrid, Flash Storage)

Price (target variable)

**Installation & Setup**

Clone the repository: git clone https://github.com/your-username/laptop-price-prediction.git

Navigate to the project directory: cd laptop-price-prediction

Install the required libraries: pip install -r requirements.txt

Run the Streamlit app: streamlit run app.py

**Model Training**

**Preprocessing:**

One-hot encoding for categorical features (like company, CPU brand, and TypeName)

Splitting data into training and testing sets

**Models Tested:**

Linear Regression

Ridge & Lasso Regression

Random Forest Regressor

Gradient Boosting Regressor

AdaBoost Regressor

Extra Trees Regressor

**Evaluation Metrics:**

R² score

Mean Absolute Error (MAE)

**GUI with Streamlit**

The project includes a Streamlit-based web interface, allowing users to input laptop specifications and get instant price predictions. This makes the model more accessible and easier to interact with.

**Results & Insights**

The model achieved a high R² score, indicating a good fit

RAM, SSD size, and CPU brand were the most influential factors in determining price

**Future Enhancements**

Use more advanced models like XGBoost or CatBoost

Hyperparameter tuning for better performance

Add visualizations to the Streamlit app to show feature importance

**How to Use**

Load the dataset

Clean and preprocess the data

Train the model

Use the Streamlit app to input new laptop specs and get predictions

**Contributing**

Pull requests are welcome! For major changes, please open an issue to discuss what you’d like to modify.

**License**

This project is licensed under the MIT License.
