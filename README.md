# Traffic-Prediction-Using-Machine-Learning

This project implements a machine learning model that predicts traffic congestion levels (Low, Medium, High) using features such as time, weather, accidents, and average vehicle speed. It demonstrates how ML can be applied to practical, real-world problems similar to traffic forecasting used in modern navigation applications.

⸻

Features
	•	Predicts traffic congestion level
	•	Decision Tree–based classification model
	•	Beginner-friendly machine learning workflow
	•	Includes model training, testing, and evaluation
	•	Clear and well-structured Python code

⸻

Project Structure

├── data/                     # Optional dataset storage  
├── traffic_prediction.py     # Main ML model  
├── requirements.txt          # Python dependencies  
└── README.md                 # Project documentation  


⸻

How It Works

The model is trained using the following input features:

Feature	Description
hour_of_day	Time of day (0–23)
day_of_week	Day index (0 = Monday, 6 = Sunday)
rain	Rain indicator (0 = no, 1 = yes)
accident_reported	Accident indicator (0 = no, 1 = yes)
avg_speed_of_cars	Average vehicle speed (km/h)

The model outputs one of the following traffic levels:
Low, Medium, or High.

⸻

Technologies Used
	•	Python
	•	NumPy
	•	Pandas
	•	Scikit-learn

⸻

Installation

git clone https://github.com/yourusername/traffic-prediction-ml.git
cd traffic-prediction-ml
pip install -r requirements.txt


⸻

Usage

Run the main script:

python traffic_prediction.py

Example prediction inside the script:

sample = [[18, 4, 0, 0, 30]]  # 6 PM, Friday, no rain, no accident, avg speed 30 km/h
prediction = model.predict(sample)


⸻

Output

The script provides:
	•	Predicted traffic level
	•	Classification report including precision, recall, and F1-score

⸻

Future Improvements
	•	Integrate real traffic datasets
	•	Add weather API data
	•	Develop a time-series neural network model
	•	Build a web dashboard for visualization and prediction

⸻

Contributing

Contributions are welcome.
Please open an issue or submit a pull request if you want to improve the project.

⸻

License

This project is licensed under the MIT License.

