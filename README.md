# AI-Based-Wardrobe-Recommendation-System

## Overview
The AI Wardrobe System is a Flask-based web application that helps users organize their wardrobe using machine learning and color recognition. It allows users to upload images of clothing items, classify them using deep learning, and store them in a structured database.

## Features
- Clothing Image Upload: Users can upload pictures of their clothing.
- AI Classification: Uses MobileNetV2 for clothing type recognition.
- Color Detection: Extracts dominant colors using KMeans clustering.
- Database Storage: Stores clothing attributes in an SQLite database.
- Web Interface: Provides an easy-to-use web UI using Flask.

## Usage
Run the Flask app with:

```bash
python app.py`
```

## Configuration
- Update db_operations.py for database configurations.
- Modify model.py to retrain the AI model with new data if required.

## Applications
- Wardrobe Organization: Categorizes clothing items automatically.
- Fashion Recommendation: Can be extended to suggest outfit combinations.
- Retail & E-Commerce: Helps in inventory management and customer recommendations.
