Uttarakhand Tourism Recommender System
This project is a machine learning-based recommendation system built to suggest tourism destinations in Uttarakhand, India. It includes multiple ML models (content-based, collaborative filtering, clustering) and a web interface built using Flask.

📌 Features
🧠 Content-based, collaborative filtering, and clustering recommendation algorithms

📊 Pre-trained models for quick predictions

🌄 Image-rich recommendations from across Uttarakhand

🧪 Modular training scripts to update or retrain models

🌐 Flask-based web interface with user input support

📁 Project Structure
php
Copy
Edit
Uttarakhand-tourism-recommender-main/
├── app.py                             # Main Flask application
├── new_app.py                         # Alternative app script
├── train_model.py                     # Script to train a specific model
├── train_all_models.py                # Train all models
├── content_based_recommender.py       # Content-based logic
├── collaborative_filtering_based.py   # Collaborative filtering logic
├── clustering_recommender.py          # Clustering logic
├── data/
│   └── uttarakhand_places.csv         # Tourism destination data
├── models/                            # Pre-trained models
│   ├── *.pkl                          # Pickle files for all models and encoders
├── static/
│   └── images/                        # Images of recommended places
├── templates/
│   ├── index.html                     # Homepage template
│   └── recommendations.html           # Recommendations page
├── README.md                          # Project documentation
└── .gitignore                         # Git ignore file
🧠 ML Models Included
>content_based_model.pkl

>collaborative_filtering_model.pkl

>collaborative_filtering_svd_model.pkl

>clustering_model.pkl

🚀 Getting Started
1.Clone the repository:
git clone https://github.com/yourusername/Uttarakhand-tourism-recommender.git
cd Uttarakhand-tourism-recommender-main

2.Install required libraries:
pip install -r requirements.txt

3.Run the app:
python app.py

4.Open your browser at:
http://localhost:5000/


🏁 Usage
Enter your travel preferences on the homepage.

Get personalized destination recommendations with images.

View detailed suggestions based on different models.

👨‍💻 Contributors
Project developed as a tourism recommendation system using machine learning for Uttarakhand tourism.

