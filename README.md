# Indian Car Price Prediction

This project focuses on predicting car prices in India based on various car features like brand, model, fuel type, transmission, and more.

## Features
- Predict the price of a car based on user input.
- Provide insights into the Indian car market using machine learning.

## Tech Stack
- **Python**: Backend programming language.
- **Flask**: Used to develop the web application.
- **Pandas**: For data processing.
- **Sklearn**: Machine learning for price prediction.
- **HTML/CSS**: Frontend interface.

## Setup Instructions
1. Clone the repository.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask application:
   ```bash
   python app.py
   ```

## Files
- `app.py`: The main Flask app where the prediction model is used.
- `model.pkl`: Pre-trained machine learning model for car price prediction.
- `car_data.csv`: Dataset used for training the model.
- `templates`: Contains HTML files for the frontend.

## Usage
- Input the car's details (brand, model, year, fuel type, etc.) on the web interface, and the system will predict the price based on the trained model.

## License
This project is open-source and free to use.
