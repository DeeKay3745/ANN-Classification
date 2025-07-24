# Customer Churn Prediction using Artificial Neural Network (ANN)

This project implements an Artificial Neural Network (ANN) to predict customer churn using the [Churn_Modelling.csv](Churn_Modelling.csv) dataset. The model is trained using TensorFlow/Keras and includes preprocessing steps such as label encoding, one-hot encoding, and feature scaling. The project also provides a Streamlit web app for interactive predictions.

## Features

- Data preprocessing: label encoding, one-hot encoding, feature scaling
- ANN model built with TensorFlow/Keras
- Streamlit web app for user-friendly predictions
- Model and encoders saved for easy deployment and inference

## Dataset

The dataset used is `Churn_Modelling.csv`, which contains customer information such as Geography, Gender, Age, Balance, Credit Score, Tenure, and more.

## How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ANN-project-Implementation.git
   cd ANN-project-Implementation
   ```

2. **Create a virtual environment and install dependencies:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. **Train the model:**
   - Run `experiments.ipynb` in Jupyter Notebook to preprocess data and train the ANN model.
   - This will save the trained model and encoders as `.pkl` and `.h5` files.

4. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

## Try the App Online

You can try the deployed app here:  
[https://ann-classification-gxudru89yzwlvtphrvcsgx.streamlit.app/](https://ann-classification-gxudru89yzwlvtphrvcsgx.streamlit.app/)

## Files

- `Churn_Modelling.csv` — Dataset
- `experiments.ipynb` — Data preprocessing and model training notebook
- `app.py` — Streamlit web app
- `prediction.ipynb` — Example prediction workflow
- `requirements.txt` — Python dependencies
- `runtime.txt` — Python version for deployment

## License

This project is for educational purposes.

---
**Deployed App:**  
[https://ann-classification-gxudru89yzwlvtphrvcsgx.streamlit.app/](https://ann-classification-gxudru89yzwlvtphrvcsgx.streamlit.app/)
