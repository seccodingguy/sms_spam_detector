# SMS Spam Detector with Gradio

This repository contains an SMS Spam Detection application built using Python, Scikit-learn, and Gradio. The application classifies SMS messages as either **Spam** or **Not Spam** using a machine learning pipeline with TF-IDF vectorization and a Linear Support Vector Classifier (SVC).

---

## Features

- **Machine Learning Pipeline**: Utilizes TF-IDF vectorization and Linear SVC for text classification.
- **Interactive Web Interface**: Powered by Gradio for real-time spam detection.
- **Pre-trained Model**: The application uses a pre-trained classification pipeline for predictions.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sms-spam-detector.git
   cd sms-spam-detector

2. Setup a Python virtual environment
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/MacOS
   venv\Scripts\activate     # For Windows

3. Install dependencies
   ```bash
   pip install gradio pandas scikit-learn