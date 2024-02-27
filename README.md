**Deploying Book Recommendation System using Flask**

This project demonstrates the deployment of a Book Recommendation System using Flask API.

**Prerequisites**

Ensure that you have the following packages installed:
- Flask==2.0.0
- pandas==2.2.1
- scikit-learn==0.24.2
- numpy==1.24.3
- joblib==1.0.1

**Project Structure**

This project consists of the following parts:
1. `book_recommendation.ipynb`: Contains the code for building the book recommendation model.
2. `app.py`: Flask application containing APIs to receive user input and provide book recommendations.
3. `templates`: Folder containing HTML templates:
   - `index.html`: Allows users to input preferences and receive book recommendations.
4. `static`: Folder containing CSS stylesheets:
   - `style.css`: Provides styling for the HTML templates.

**Running the Project**

1. Navigate to the project directory.
2. Create the book recommendation model by running the command:
   ```
   python book_recommendation.ipynb
   ```
   This will generate a serialized version of the model named `book_recommendation_model.pkl`.
3. Run the Flask application by executing:
   ```
   python app.py
   ```
   The Flask app will start running on port 5000 by default.
4. Open your web browser and navigate to:
   - `http://127.0.0.1:5000/` or `http://localhost:5000/` to access the homepage.
   - `http://127.0.0.1:5000/predict` to view the output of the book recommendation system.

**Usage**

1. On the homepage, enter your preferences for book recommendations.
2. Click on the "Recommend Books" button.
3. You will receive a list of recommended books based on your preferences.

**Note**

Ensure that you have a stable internet connection to access the book recommendations.
