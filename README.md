# FOREST-PREDICTION-USING-RANDOMFOREST-
🌲 Forest Cover Type Prediction
📌 Project Overview

This project predicts the forest cover type based on cartographic and environmental features such as elevation, slope, distances to hydrology, roadways, fire points, hillshade values, wilderness areas, and soil types.

The model helps classify land areas into different forest cover categories using Machine Learning.

📊 Dataset

Dataset: Forest Cover Type Dataset

Target variable: Cover_Type

Features include:

Elevation, Aspect, Slope

Distances to Hydrology, Roads, Fire Points

Hillshade (9am, Noon, 3pm)

Wilderness Areas (one-hot encoded)

Soil Types (one-hot encoded)

🧠 Approach Used

Data Loading & Cleaning

Removed unnecessary column (Id)

Checked missing values

Exploratory Data Analysis (EDA)

Correlation heatmap

Boxplots to detect outliers

Outlier Handling

Used IQR-based capping for numeric features

Feature Scaling

Applied StandardScaler

Model Building

Used RandomForestClassifier

Trained on scaled data

Model Evaluation

Accuracy score used for evaluation

Prediction

Model predicts forest cover type for new input data

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib & Seaborn

Scikit-learn

Joblib

📈 Model Used

Random Forest Classifier

Handles non-linear data well

Works effectively with large feature sets

Robust to outliers

🚀 How to Run the Project

Clone the repository

git clone https://github.com/your-username/forest-cover-prediction.git


Install dependencies

pip install -r requirements.txt


Run the prediction script

python predict.py

📌 Output

The model outputs a forest cover type, such as:

Spruce/Fir

Lodgepole Pine

Ponderosa Pine

Aspen

Douglas-fir
(and others)

📚 Future Improvements

Hyperparameter tuning with GridSearchCV

Feature importance visualization

Streamlit web app deployment

Model comparison (XGBoost, LightGBM)

🙌 Author

Dev Sah
Aspiring Data Scientist | Machine Learning Enthusiast
