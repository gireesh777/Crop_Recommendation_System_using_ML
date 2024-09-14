# Crop Recommendation System

This Crop Recommendation System utilizes the Random Forest Algorithm to assist farmers in selecting the optimal crop for their needs, based on an Indian Crop Recommendation Dataset. By entering soil parameters like N, P, K, and pH, along with weather factors such as temperature, humidity, and rainfall, as well as regional location, the tool provides tailored crop suggestions.

## Features

- Recommends the best and most suitable crops to plant.
- Takes into account soil conditions (N, P, K, pH), weather conditions (temperature, humidity, and rainfall), and regional location.

## Requirements

To run this project, you'll need to set up a Python virtual environment and install the necessary dependencies. Follow the instructions below:

### Setup

1. **Clone the repository:**

   ```
   git clone https://github.com/gireesh777/Crop_Recommendation_System_using_ML.git
   cd Crop_Recommendation_System_using_ML
   ```
Setting Up and Running the Application
To set up and run the application, follow these steps:

2. **Create and Activate a Python Virtual Environment**

For Windows:
```
python -m venv venv
venv\Scripts\activate
```
For macOS and Linux:
```
python3 -m venv venv
source venv/bin/activate
```

3. **Install the Required Packages**
```
pip install -r requirements.txt
```
4. **Run the Application**
```
streamlit run app.py
```
**Usage**

After running the application, you can input soil nutrient values (N, P, K, pH), weather conditions (temperature, humidity, rainfall), and regional details to receive crop recommendations.