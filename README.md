🧠 Next Word Prediction using LSTM

An intelligent Next-Word Prediction Model built using LSTM (Long Short-Term Memory) networks in TensorFlow/Keras, with a Streamlit web interface for real-time text prediction. This project demonstrates NLP sequence modeling, text preprocessing, and model deployment in an interactive environment.

🚀 Features

🔤 Predicts the next word in a given text sequence using an LSTM-based language model.

⚙️ Preprocessing pipeline using Keras Tokenizer and pad_sequences for sequence generation.

💾 Model serialized as next_word_lstm.h5 and Tokenizer saved via pickle for reproducible inference.

🌐 Streamlit app for real-time text input and word prediction.

🧩 Modular code structure for easy customization and deployment.

🚀 Live Demo

👉 Try it here: Next Word Predictor – Streamlit App

(Replace with your actual Streamlit link)

🛠️ Tech Stack

Programming Language: Python

Frameworks & Libraries: TensorFlow, Keras, NumPy, Streamlit, Pickle

Model Type: LSTM (Recurrent Neural Network)

Interface: Streamlit Web App

📁 Project Structure
📦 next-word-prediction
├── app.py                  # Streamlit app for UI and model inference
├── experiments.ipynb       # Jupyter notebook for training and experiments
├── next_word_lstm.h5       # Trained LSTM model
├── tokenizer.pkl           # Saved Tokenizer for text preprocessing
├── requirements.txt        # Dependencies
└── README.md               # Project documentation

⚙️ Setup & Installation

Clone the repository

git clone https://github.com/<your-username>/next-word-prediction.git
cd next-word-prediction


Install dependencies

pip install -r requirements.txt


Run the Streamlit app

streamlit run app.py


Use the App

Enter a few words in the input box.

Click Predict to generate the most probable next word.

📊 Model Overview

Architecture: LSTM with embedding + dense output layer

Input: Tokenized text sequences

Output: Predicted next word (via softmax)

Training: Performed on sample text data for demonstration (can be scaled for larger corpora)

📈 Results

Demonstrates context-aware word prediction using recurrent sequence modeling.

Achieves smooth inference and accurate word suggestions for short text prompts.

🤝 Contributing

Contributions are welcome!
Feel free to fork this repository, open issues, or submit pull requests to improve the model or interface.


👤 Author

Vaishnavi Newalkar

