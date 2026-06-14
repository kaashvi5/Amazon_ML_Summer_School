# Accessible Hangout Recommender

An AI-powered Recommendation System that helps users discover accessible hangout locations based on accessibility needs, preferences, ratings, and venue features.

This project was developed as part of my Machine Learning portfolio and demonstrates Recommendation Systems, Feature Engineering, Data Analysis, and Classification techniques.

---

## Project Overview

Finding accessible public places can be challenging for individuals with mobility or accessibility requirements.

The Accessible Hangout Recommender analyzes venue attributes and user preferences to recommend suitable locations such as:

- Cafes
- Restaurants
- Parks
- Libraries
- Malls
- Coworking Spaces
- Tourist Attractions

The system prioritizes accessibility-related features while maintaining recommendation quality.

---

## Dataset

The project uses a custom dataset containing:

- 1000 venue records
- Accessibility features
- Ratings and reviews
- Location information
- Crowd levels
- Budget information
- User interaction data

### Key Features

- Wheelchair Accessibility
- Ramp Availability
- Accessible Washrooms
- Elevator Availability
- Accessible Parking
- Visual Assistance Support
- Hearing Assistance Support
- Family Friendly Indicators
- Safety Score
- Cleanliness Score
- Service Score
- Ambience Score

---

## Machine Learning Pipeline

### 1. Data Preprocessing

- Missing Value Handling
- Feature Selection
- Feature Engineering
- Text Combination for Recommendation

### 2. Recommendation Engine

Implemented using:

- TF-IDF Vectorization
- Cosine Similarity

The system recommends similar venues based on venue characteristics and accessibility features.

### 3. Accessibility Classification

A Random Forest Classifier was trained to predict highly accessible venues.

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Exploratory Data Analysis

Performed comprehensive EDA including:

- Accessibility Score Distribution
- Average Rating by Category
- Places per City
- Accessibility vs Rating Analysis
- Wheelchair Accessibility Distribution
- Correlation Heatmap
- Top Rated Places
- Feature Importance Analysis

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

### Machine Learning Techniques

- TF-IDF Vectorization
- Cosine Similarity
- Random Forest Classification

---

## Model Performance

| Metric | Score |
|----------|----------|
| Accuracy | 81.5% |
| Precision | Evaluated |
| Recall | Evaluated |
| F1 Score | Evaluated |

---

## Project Structure

```text
Accessible-Hangout-Recommender/

│
├── dataset/
│   └── places.csv
│
├── notebooks/
│   └── Amazon_Summer_School_ML_Model.ipynb
│
├── models/
│   ├── accessibility_classifier.pkl
│   └── tfidf_vectorizer.pkl
│
├── README.md
│
└── requirements.txt
```

---

## Future Improvements

- Streamlit Web Application
- Google Maps Integration
- Real-Time Recommendations
- Hybrid Recommendation System
- Collaborative Filtering
- Personalized User Profiles
- Location-Based Ranking

---

## Results

The recommendation engine successfully identifies venues with similar accessibility characteristics and user preferences while the classification model predicts highly accessible venues with strong performance.

---

## Author

**Cash**

Machine Learning Enthusiast | AWS Learner | Software Development Student

GitHub:
https://github.com/kaashvi5

Kaggle:
https://www.kaggle.com/kaashvig
