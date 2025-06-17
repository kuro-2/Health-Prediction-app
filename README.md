# Health-Prediction-app

🧠 Multiple Disease Prediction System (MDPS) or  Health-Prediction-app
The Multiple Disease Prediction System (MDPS) is a machine learning-based web application built with Streamlit. It allows users to predict the likelihood of three major diseases—Diabetes, Heart Disease, and Parkinson’s Disease—based on medical input parameters. This tool is designed to assist medical professionals and individuals in early detection and proactive healthcare.

🚀 How to Run the App Locally
To launch the Streamlit application on your local machine, open your terminal or command prompt and run:

bash
Copy
Edit
streamlit run "D:\MDPS\app.py"
Make sure all necessary libraries (such as streamlit, scikit-learn, pandas, etc.) are installed in your environment.

🧪 Google Colab Notebooks
The models for each disease were trained and evaluated in Google Colab. You can explore or reproduce the training process using the following notebooks:

🩸 Diabetes Prediction Model - https://colab.research.google.com/drive/13IT5ypUMuwaxWXXUMIFiATihtmOcU7Iy?usp=sharing
❤️ Heart Disease Prediction Model - https://colab.research.google.com/drive/1teEEtnplL-ib1zIClEe3loTpYqcLZw0q?usp=sharing
🧠 Parkinson’s Disease Prediction Model - https://colab.research.google.com/drive/19jyvw5GPQ19tn_XQELHRX8WenlwTUw0t?usp=sharing
Each notebook covers:

Dataset loading and preprocessing

Model training and evaluation

Accuracy scores and confusion matrix

Pickle model saving for deployment

📂 Project Structure
plaintext
Copy
Edit
MDPS/
├── app.py                   # Main Streamlit app
├── diabetes_model.pkl       # Trained Diabetes prediction model
├── heart_model.pkl          # Trained Heart Disease prediction model
├── parkinsons_model.pkl     # Trained Parkinson’s prediction model
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies
📦 Requirements
Install all required Python libraries with:

bash
Copy
Edit
pip install -r requirements.txt
🏁 Features
Interactive UI for each disease model

Real-time predictions based on user input

Easy integration with trained .pkl models

Deployed using Streamlit

📌 Note
This system is for educational and experimental purposes only. It should not be used as a substitute for professional medical advice, diagnosis, or treatment.


Check out the link below to use the web app:
https://health-prediction-app-zlyfmomh6r7lc2fxqhqfez.streamlit.app/
