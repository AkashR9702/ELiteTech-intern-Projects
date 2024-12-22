# Car Price Prediction App

This is a machine learning web application that predicts the price of a used car based on various features such as brand, year of manufacture, mileage, fuel type, and more. The application uses a pre-trained model to predict the price of a car based on user input.

## Features

- **Car Brand Selection**: Users can choose from a list of car brands.
- **Car Attributes**: Input sliders for car details like manufacturing year, kilometers driven, mileage, engine capacity, power, and number of seats.
- **Fuel Type & Transmission**: Select fuel type (e.g., Diesel, Petrol) and transmission type (Manual or Automatic).
- **Price Prediction**: Once the inputs are filled, the app predicts the price of the car.

## Technologies Used

- **Streamlit**: For creating the interactive web interface.
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For machine learning model prediction.
- **Pickle**: For serializing the trained model.

## Installation

### Prerequisites

- Python 3.x or higher
- Virtual environment (recommended)

### Setting Up the Environment

1. **Clone the repository** (if applicable):
   ```bash
   git clone <repo-url>
   cd car-price-prediction

2. Create and activate a virtual environment:

Windows:

	python -m venv venv
	venv\Scripts\activate

Mac/Linux:

	python3 -m venv venv
	source venv/bin/activate


3. Install the required libraries:

	pip install -r requirements.txt

4. Run the app:

	streamlit run app.py

5. Open the provided URL (e.g., http://localhost:8501) in your browser to start using the application

## Usage
	Select Car Brand: Choose a car brand from the drop-down list.

	Enter Car Details: Use the sliders to input values for the manufacturing year, kilometers driven, mileage, engine size, and other 	features.

	Click "Predict": The app will use the machine learning model to predict the car price based on the provided inputs.

	View Results: The predicted car price will be displayed.


6. Model Training
	The model was trained using a dataset of used cars with features like:

	Car brand
	Year of manufacture
	Mileage
	Fuel type
	Seller type
	Transmission type
	Owner type
	Engine capacity
	Maximum power
	Number of seats

	The model is serialized into a .pkl file, which is loaded into the app to make predictions.

Acknowledgments
Dataset: The dataset used for training the model can be found in Cardetails.csv.
Libraries: Streamlit, pandas, NumPy, and scikit-learn were used for model training and app development.
