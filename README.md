# Vision Assist System

An AI-powered assistive system designed to help visually impaired users recognize products and read printed text in real time using Deep Learning and Optical Character Recognition (OCR). The system provides voice feedback, enabling users to interact with their surroundings independently.

## Features

- Real-time product detection
- Printed text recognition (OCR)
- Voice feedback using Text-to-Speech
- Image preprocessing for improved accuracy
- Deep Learning-based object classification
- Easy-to-use interface

## Tech Stack

- Python
- TensorFlow
- Keras
- OpenCV
- OCR (Tesseract/EasyOCR)
- PyCharm

## Project Workflow

1. Capture image/video from camera
2. Preprocess image
3. Detect product or text
4. Recognize object/text using AI models
5. Convert result into speech
6. Provide voice output to the user

## Folder Structure

```
vision-assist-system/
│
├── dataset/
├── models/
├── images/
├── output/
├── src/
│   ├── object_detection.py
│   ├── text_recognition.py
│   ├── preprocessing.py
│   ├── speech.py
│   └── main.py
│
├── requirements.txt
├── README.md
└── LICENSE
```

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/vision-assist-system.git
```

Go to the project directory

```bash
cd vision-assist-system
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python src/main.py
```

## Results

- Achieved approximately **92% classification accuracy**
- Improved model performance through preprocessing and hyperparameter tuning
- Real-time speech feedback for visually impaired users

## Future Improvements

- Currency recognition
- Face recognition
- Mobile application
- Multiple language support
- Cloud deployment

## Author

**Teja Kiran Kommi**

GitHub: https://github.com/tejakiran0209

LinkedIn: https://linkedin.com/in/teja-kiran-kommi
