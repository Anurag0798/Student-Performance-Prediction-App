# Student Performance Prediction App

## Overview
The Student Performance Prediction App is designed to predict student performance based on various input parameters such as hours studied, previous scores, and extracurricular activities. The app employs machine learning algorithms and connects to a MongoDB database for effective data management.

## Features
- Interactive user interface for data input.
- Predictive model to calculate performance scores.
- Data management using MongoDB.

## Technologies Used
- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Pickle
- MongoDB (pymongo)

## Requirements
You must install the following packages listed in `requirements.txt`:

- scikit-learn
- pymongo

## MongoDB Connection
The app connects to a MongoDB Atlas cluster. Update the connection URI with your credentials:

```python
uri = "mongodb+srv://<username>:<password>@<cluster>.mongodb.net/?retryWrites=true&w=majority&appName=<appName>"
```

## How to Run the App
- Clone the repository:

```bash
git clone https://github.com/yourusername/student-performance-prediction-app.git
```
```bash
cd student-performance-prediction-app
```

- Install the required packages:
```bash
pip install -r requirements.txt
```

- Run the Streamlit application:
```bash
streamlit run student_performance_prediction.py
```
## Usage
- Launch the app and fill in the required fields:
  - Hours Studied
  - Previous Score
  - Extracurricular Activity
  - Sleeping Hours
  - Number of question papers solved
- Click “Predict the score” to see the predicted performance score.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.