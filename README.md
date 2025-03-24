# personal-fitness-tracker_app
🏋️‍♂️ Personal Fitness Tracker - Calorie Burn Prediction App
This project is a Personal Fitness Tracker Web Application built using Streamlit, scikit-learn, and other data science libraries. The app allows users to input personal parameters like Age, Gender, BMI, Exercise Duration, Heart Rate, and Body Temperature, and predicts the calories burned using a trained machine learning model.

🚀 Features
Predict the number of kilocalories burned based on personal parameters.

Compare your stats with other people in the dataset.

Get a sample of similar users with close calorie burn estimates.

Interactive sidebar input with real-time predictions.

Smooth loading animations and progress bars for a better user experience.

📊 Tech Stack
Python 3.x

Streamlit (for web app)

Pandas (for data manipulation)

NumPy (for numerical operations)

Matplotlib & Seaborn (for visualizations)

scikit-learn (for model training)

Random Forest Regressor (as the primary machine learning model)

📁 Project Structure
bash
Copy
Edit
├── app.py                   # Streamlit web application
├── calories.csv             # Calories burned dataset
├── exercise.csv             # Exercise data with physiological measurements
├── fitness_tracker.ipynb    # Jupyter Notebook with EDA and model development
└── README.md                # Project documentation (this file)
⚙️ How It Works
User inputs data via the Streamlit sidebar.

The data is preprocessed and aligned with the trained model's format.

A Random Forest Regressor trained on exercise and calories data is used to make the calorie burn prediction.

The app displays:

The predicted kilocalories burned.

Similar cases from the dataset.

Comparative insights (e.g., how your heart rate compares to others).
