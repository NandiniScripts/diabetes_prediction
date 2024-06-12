# diabetes_prediction

## Project Description
This project is a web application for predicting the likelihood of diabetes in a patient using a machine learning model. The application is built using Django, a high-level Python web framework, and integrates a trained machine learning model to make predictions based on user input.

## Features
- User-friendly interface for inputting medical data.
- Integration of a machine learning model for diabetes prediction.
- Display of prediction results with a probability score.
- Option to download prediction reports.
- Secure and scalable architecture using Django.

## Technologies Used
- Django
- Scikit-learn
- HTML/CSS
- JavaScript


## Installation

### Prerequisites
- Python 3.8 or above
- pip (Python package installer)
- Git

### Steps
1. Clone the repository:
    ```bash
   https://github.com/NandiniScripts/diabetes_prediction.git
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

    On Windows:
    ```bash
    venv\Scripts\activate
    ```

    On macOS/Linux:
    ```bash
    source venv/bin/activate
    ```

4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

5. Apply migrations:
    ```bash
    python manage.py migrate
    ```

6. Run the development server:
    ```bash
    python manage.py runserver
    ```

7. Open your browser and navigate to `http://127.0.0.1:8000` to see the application.

## Usage
1. Enter the required medical data in the form.
2. Click the "Predict" button to get the prediction result.
3. View the prediction result along with the probability score.
4. Optionally, download the prediction report for your records.

## Contributing
We welcome contributions to enhance the functionality and features of this project. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request.


## Contact
For any inquiries, please contact me at nandinimahajan1435@gmail.com.

---

*This project was created for educational purposes and should not be used as a substitute for professional medical advice.*
