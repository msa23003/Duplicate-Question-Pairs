# Duplicate Question Pairs Predictor

This Streamlit application predicts whether two questions are duplicates or not using a pre-trained machine learning model. The app is designed to help identify similar or identical questions, which is particularly useful in platforms like Q&A websites to avoid redundant content.

## Screenshot from Streamlit App

<img src="https://github.com/user-attachments/assets/bccc16a6-643d-4c57-bb47-32e4810b0ca6" width="500" /> <img src="https://github.com/user-attachments/assets/a6b5fe84-7c10-4767-94cd-6e6a47a6fbd1" width="500" />


## Features

- **User-Friendly Interface:** Simple input fields to enter two questions.
- **Real-Time Prediction:** Provides instant feedback on whether the questions are duplicates.
- **Streamlit Powered:** The application is built using Streamlit, ensuring a responsive and interactive experience.

## Installation

To run this application locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/msa23003/duplicate-question-predictor.git
   cd duplicate-question-predictor
   ```

2. **Install Required Packages:**

   Make sure you have Python installed. Then, install the necessary packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application:**

   ```bash
   streamlit run app.py
   ```

## Usage

1. **Input Questions:** Enter two questions in the provided input fields.
2. **Predict:** Click the "Find" button to determine if the questions are duplicates.
3. **Result:** The application will display either "Duplicate" or "Not Duplicate" based on the prediction.

## Files

- **app.py:** Main application file.
- **helper.py:** Contains helper functions for processing the input.
- **model.pkl:** Pre-trained machine learning model used for prediction.

## Requirements

- Python 3.x
- Streamlit
- scikit-learn
- Pickle

Ensure all dependencies are listed in `requirements.txt`.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- The machine learning model used in this project was trained using a dataset of question pairs.

---
