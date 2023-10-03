# machine-learning-to-find-liver-disease

# Liver Disease Detection Using Machine Learning and Flask

## Introduction

This project aims to create a liver disease detection system using machine learning and Flask. The system is designed to predict whether a patient is likely to have liver disease based on various medical features. It uses a trained machine learning model to make predictions and provides a user-friendly web interface for input and output.

## Prerequisites

Before running the application, you will need the following:

1. Python 3.x installed on your system.
2. Required Python libraries listed in the `requirements.txt` file. You can install them using `pip`:
   
   ```bash
   pip install -r requirements.txt
   ```

## Getting Started

Follow these steps to set up and run the liver disease detection system:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/liver-disease-detection.git
   cd liver-disease-detection
   ```

2. Create a virtual environment (recommended) and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

3. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Prepare the dataset:
   - You need a dataset with medical features and labels indicating the presence or absence of liver disease. Make sure it is in a compatible format (e.g., CSV).
   - Place the dataset file in the `data` directory.

5. Train the machine learning model:
   - Run the Jupyter Notebook or Python script provided in the repository to train the machine learning model on your dataset.
   - Save the trained model file (e.g., `liver_disease_model.pkl`) in the `models` directory.

6. Configure Flask:
   - Open the `config.py` file and customize it according to your requirements, including the model file path and other settings.

7. Run the Flask application:

   ```bash
   python app.py
   ```

   The application will start and be accessible at `http://localhost:5000` in your web browser.

## Usage

1. Open a web browser and go to `http://localhost:5000`.
2. You will see the liver disease detection interface.
3. Enter the patient's medical data into the input form.
4. Click the "Predict" button.
5. The application will use the trained machine learning model to make a prediction and display the result on the webpage.

## Contributors

- [Your Name](https://github.com/yourusername)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the [Flask](https://flask.palletsprojects.com/en/2.0.x/) community for the web framework.
- Dataset source: [Provide the source or citation for the dataset if applicable]
