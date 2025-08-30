# 📉 Loan Status Prediction 📊

Want to know if your loan will get approved? This project helps predict that! 🎉

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project uses the MIT license, meaning you are free to use and change the code. 👍



## About the Project
A Loan Status Prediction system is a machine learning model that predicts whether a loan application will be approved or rejected based on input features and historical data. This system automates the loan approval process and assists in making informed decisions by assessing the creditworthiness of applicants.



## Table of Contents
1.  [About the Project](#about-the-project)
2.  [Features](#features)
3.  [Tech Stack](#tech-stack)
4.  [Installation](#installation)
5.  [How to Use](#how-to-use)
6.  [Project Structure](#project-structure)
7.  [Contributing](#contributing)
8.  [License](#license)
9.  [Important Links](#important-links)
10. [Footer](#footer)



## Features
-   **Data Preprocessing:** Handles missing values and converts categorical variables into numerical representations.
-   **Exploratory Data Analysis (EDA):** Visualizes data to analyze the distribution of loan approval based on education, marital status, etc.
-   **SVM Classifier:** Uses Support Vector Machine (SVM) with a linear kernel for loan status prediction.
-   **Model Training and Evaluation:** Trains the SVM classifier using training data and evaluates its performance on unseen data.
-   **Model Saving:** Saves the trained SVM classifier using the pickle library for future predictions.
-   **Streamlit App:** Provides an interactive web interface for users to input loan application details and predict loan status.



## Tech Stack
-   **Languages:** Python, Markdown
-   **Frameworks:** Streamlit, scikit-learn, pandas, numpy



## Installation
1.  Clone the repository:

    ```bash
    git clone https://github.com/Talha4543/Loan-Status-Prediction.git
    cd Loan-Status-Prediction
    ```

2.  Install the required dependencies using pip:

    ```bash
    pip install -r requirements.txt
    ```

    The `requirements.txt` file includes the following:

    ```text
    scikit-learn
    StandardScaler
    numpy
    pandas
    svm
    ```



## How to Use
1.  **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

2.  Open the provided URL in your web browser (e.g., `http://localhost:8501`).
3.  Enter the loan application details in the input fields.
4.  Click the "Predict Loan Status" button.
5.  View the prediction result, which indicates whether the loan is likely to be approved or rejected.

This project provides an interactive interface for users to predict loan status based on various input features using a pre-trained SVM model. The Streamlit app allows users to input details such as gender, marital status, income, loan amount, and credit history to receive a loan approval prediction. The model is trained on historical loan data, making it capable of assisting in the decision-making process for loan applications. Real-world use case is to aid loan officers and banking systems in automating loan approval processes by providing quick predictions based on applicant information.



## Project Structure
```
Loan-Status-Prediction/
├── app.py                      # Streamlit web application
├── loan_status_model.pkl       # Pre-trained SVM model
├── loans.csv                   # Dataset (details unknown)
├── LICENSE                     # License file
├── README.md                   # Project documentation
├── requirements.txt            # Project dependencies
├── LoanPred.ipynb              #Jupyter notebook
└── pic.avif                    # Image for the app
```



## Contributing
Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes.
4.  Submit a pull request.



## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## Important Links
-   [Streamlit App Demo](https://dhrupad17-loan-status-prediction-app-7n5ll3.streamlit.app/) (from original README)



## Footer
**Loan-Status-Prediction** - [https://github.com/Talha4543/Loan-Status-Prediction](https://github.com/Talha4543/Loan-Status-Prediction) 


Author: [Talha4543](https://github.com/Talha4543)


Contact: (No contact information provided, add if available)


⭐️ Give us a star! Fork the repository! Report issues! Let's make this project better together!
