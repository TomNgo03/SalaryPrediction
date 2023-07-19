# SWE Salary Prediction Web Application

This web application is designed to predict software engineer salaries based on real-time data from Stack Overflow. It utilizes machine learning algorithms to analyze 3 main factors: location, level of education, number of experience years and provide salary estimates for software engineering positions.


## Features

- Salary Prediction: The web application predicts software engineer salaries based on inputs such as years of experience, education level, and location.
- Real-time Data: The application fetches the latest data from Stack Overflow to ensure accurate predictions based on up-to-date information.
- StreamKit Integration: The application is built using StreamKit, a powerful web development framework for building interactive and real-time applications.
- User-Friendly Interface: The web application provides an intuitive and user-friendly interface, making it easy for users to input their information and receive salary predictions.

## Installation

To run the web application locally, follow these steps:

1. Clone the repository: 
   ```bash
   git clone https://github.com/TomNgo03/SalaryPrediction.git

2. Create a virtual environment (optional but recommended).
- On Linux/macOS:
   ```bash
   python3 -m venv venv

- On Windows:
   ```bash
   py -3 -m venv venv

3. Activate the virtual environment.
- On Linux/macOS:
   ```bash
   . venv/bin/activate

- On Windows:
   ```bash
   venv\Scripts\activate

4. Start the application: 
   ```bash
   streamkit run app.py
5. Open your web browser and navigate to `http://localhost:8503` to access the application.

## Usage

- Fill out the necessary information in the provided input fields, including years of experience, programming languages, education level, and location.
- Click the "Predict Salary" button to generate a salary prediction based on the entered data.
- The predicted salary will be displayed on the screen, providing the estimated salary for the specified software engineering position.

## Dependencies

- StreamKit: Web development framework for building real-time applications.
- Python: Programming language used for machine learning and data analysis.
- scikit-learn: Machine learning library for Python.
- Pandas: Data manipulation and analysis library for Python.

## License

This project is licensed under the [MIT License](LICENSE)

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please create an issue or submit a pull request.
