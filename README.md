# AI-Based-Wardrobe-Recommendation-System

# Overview

The AI Wardrobe System is a Flask-based web application that helps users organize their wardrobe using machine learning and color recognition. It allows users to upload images of clothing items, classify them using deep learning, and store them in a structured database.

# Features
1. Clothing Image Upload: Users can upload pictures of their clothing.
2. AI Classification: Uses MobileNetV2 for clothing type recognition.
3. Color Detection: Extracts dominant colors using KMeans clustering.
4. Database Storage: Stores clothing attributes in an SQLite database.
5. Web Interface: Provides an easy-to-use web UI using Flask.


# Usage

Run the Flask app with:

`python app.py`

# Configuration
1. Update db_operations.py for database configurations.
2. Modify model.py to retrain the AI model with new data if required.

# Applications
1. Wardrobe Organization: Categorizes clothing items automatically.
2. Fashion Recommendation: Can be extended to suggest outfit combinations.
3. Retail & E-Commerce: Helps in inventory management and customer recommendations.
