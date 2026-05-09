# AI-Detector

Description

AI-Detector is a Machine Learning and NLP-based project that detects whether a text is AI-generated or human-written. The system uses TF-IDF vectorization and Logistic Regression to analyze writing patterns and classify the content with confidence scores.

The project also supports:

Manual text input
PDF file analysis
Image text extraction using OCR
🚀 Features
Detect AI-generated content
Human vs AI text classification
PDF text detection
Image text extraction using Tesseract OCR
Confidence score prediction
Command-line interactive interface
🛠 Technologies Used
Python
Scikit-learn
Pandas
NumPy
Joblib
PDFPlumber
PyTesseract
Pillow (PIL)
⚙️ Machine Learning Model

This project uses:

TF-IDF Vectorizer for feature extraction
Logistic Regression for text classification
📂 Dataset

The dataset contains:

Human-written text samples
AI-generated text samples

The model is trained to classify the input text into:

Human Written 👨
AI Generated 🤖
📊 Workflow
Load Dataset
Preprocess Text
Train ML Model
Predict Input Text
Display Result with Confidence Score
