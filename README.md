# Old-Car-Price-Prediction-GUI
> A Python-based GUI for predicting old car prices using Tkinter and DecisionTreeClassifier. Users input car specs like engine size, horsepower, and mileage to get real-time price predictions. Features include input validation, reset functionality, and a clean, user-friendly interface

This project is a **car price prediction tool** built using Python, with a graphical user interface (GUI) created using **Tkinter**. The price prediction model is built using **DecisionTreeClassifier** from the `sklearn` library, trained on a dataset of car specifications.

## Project Overview
The tool allows users to input key car specifications such as engine size, horsepower, mileage, weight, and length to predict the estimated price of the car. 

The GUI is designed to be **user-friendly** and provides instant feedback for predictions, with features like input validation and reset functionality.

## Features
- Simple and clean GUI built using Tkinter.
- Car price prediction using `DecisionTreeClassifier`.
- Real-time feedback with validations for input fields.
- Reset option to clear inputs and start fresh.
- Predict car prices based on multiple factors like engine size, cylinders, horsepower, and more.

## Requirements
To run the project, you need:
- Python 3.x
- Tkinter (usually comes with Python)
- Pandas
- Scikit-learn

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/iamhirdeshkumar15/Old-Car-Price-Prediction-GUI.git
    ```

2. Install the required Python packages:
    ```bash
    pip install pandas scikit-learn
    ```

3. Run the application:
    ```bash
    python car_price_prediction_gui.py
    ```

## Dataset
The dataset used for this project contains car features such as engine size, number of cylinders, horsepower, weight, and more. It is included in the repository as `trained_data2.csv`.

## How to Use
1. Launch the application by running `car_price_prediction_gui.py`.
2. Input car details in the respective fields (engine size, cylinders, horsepower, etc.).
3. Click the **Get Price** button to predict the car's price.
4. Click **Clear** to reset the fields and input new data.

## Future Improvements
- Add more advanced machine learning models for better accuracy.
- Expand the dataset for more features and diversity.
- Improve the GUI design with more interactive elements.

## Contributing
Feel free to submit issues or pull requests if you'd like to contribute to the project.
