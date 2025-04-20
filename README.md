🥗 Fitness and Diet Plan Recommendation System

This is a machine learning-powered web application that provides personalized fitness and diet recommendations based on user inputs such as age, weight, height, fitness goals, and dietary preferences. The system uses hybrid recommendation models (collaborative filtering + content-based filtering) to suggest ideal food and workout plans for users.

🚀 Features
✅ Personalized diet plans for:

Weight Gain

Weight Loss

Healthy Maintenance

✅ Fitness workout suggestions

✅ Filters for:

Age, Weight, Height

Dietary Preference (Veg, Non-Veg, Vegan)

✅ Web interface built using Flask

✅ ML backend for intelligent food and fitness recommendations

✅ Indian food support included!

🧠 Machine Learning Techniques
K-Nearest Neighbors (KNN)

Collaborative Filtering

Content-Based Filtering

Hybrid Recommendation Approach

🛠 Tech Stack
Frontend: HTML, CSS, JavaScript (with Flask templates)

Backend: Python (Flask)

Libraries: Pandas, NumPy, Scikit-learn, Pickle

Deployment (Optional): Heroku / Render / Localhost

📂 Project Structure
php
Copy
Edit
fitness-diet-recommender/
│
├── static/                   # CSS/JS files
├── templates/                # HTML templates
├── dataset/                  # Food and fitness CSVs
├── models/                   # Saved ML models (Pickle files)
├── app.py                    # Main Flask app
├── recommender.py            # ML logic for recommendations
├── requirements.txt          # Python dependencies
└── README.md                 # Project description
📝 How to Use
Clone the repository


📊 Sample Inputs

Age	Weight (kg)	Height (cm)	Goal	Diet Preference
25	60	170	Weight Gain	Veg
30	75	165	Weight Loss	Non-Veg
🧪 Example Output
🍽️ Suggested Meals: Dal Khichdi, Grilled Paneer, Smoothies

🏋️‍♂️ Workout Plan: Cardio 30 min/day, Strength 3x/week

📌 Future Improvements
Add user login and profile

Integrate wearable device data (steps, calories)

Add chatbot for recommendations

Deploy on the cloud
