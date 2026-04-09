# DeepFake Audio Detection

This project detects deepfake audio using a hybrid deep learning model combining CNN and LSTM. MFCC features are extracted from audio signals and analyzed to distinguish real voices from AI-generated ones.

## Features

- MFCC feature extraction
- CNN + LSTM hybrid model
- Audio classification (Real vs Fake)
- Web interface for prediction

## Technologies Used

- Python
- Deep Learning (CNN, LSTM)
- Django (Web Framework)

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run server:
   python manage.py runserver

3. Open browser:
   http://127.0.0.1:8000/

## Dataset

Dataset used for training includes real and fake audio samples.

## Future Scope

- Improve accuracy with larger dataset
- Real-time detection system
- Deployment as API/service
