

# Gunshot Detection System

This repository contains the code for a **Gunshot Detection System**, built using machine learning to detect gunshot sounds in real-time. The model is designed to classify audio files as gunshots or non-gunshots using pre-trained models and feature extraction techniques. The system is built with a **Flask API** for easy interaction, allowing users to upload audio files and receive instant classification results.

## Features

- **Gunshot Classification**: Detect gunshot sounds from audio files with high accuracy.
- **Real-Time Detection**: Process audio inputs and classify them in real-time via an API.
- **Flask-Based API**: A user-friendly Flask interface where users can upload audio files and get results.
- **Pre-Trained Models**: Leverages a pre-trained machine learning model to enhance detection speed and accuracy.
- **Audio Feature Extraction**: Implements advanced audio processing techniques for feature extraction from sound files.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/gunshot-detection-system.git
    cd gunshot-detection-system
    ```

2. **Set up a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```bash
    python app.py
    ```

5. **Access the Flask API**:
    Open your browser and go to `http://127.0.0.1:5000/` to use the Gunshot Detection System.

## Usage

1. **Upload Audio**: You can upload an audio file using the web interface provided by the Flask API.
2. **Receive Results**: The system will classify the audio file as a gunshot or non-gunshot and provide instant results.
3. **Real-Time Processing**: Designed for real-time detection and can be integrated into security or safety applications.

## Model Details

- **Machine Learning Models**: The detection system uses a pre-trained **machine learning model** that has been fine-tuned for gunshot detection.
- **Feature Extraction**: The audio features are extracted using **MFCCs** (Mel-frequency cepstral coefficients), which are commonly used in sound classification tasks.
- **Accuracy**: The model achieves a high level of accuracy in detecting gunshots, making it suitable for real-time safety applications.

## Dependencies

- **Python 3.6+**
- **Flask**
- **Librosa** (for audio feature extraction)
- **TensorFlow/Keras** (for the machine learning model)
- **NumPy**, **Pandas**, **Matplotlib**

## Data

The dataset used for training the gunshot detection model consists of audio files of gunshots and other sounds. It has been pre-processed to extract meaningful features for the model to train on. 

## Running Tests

To run tests on the system, use the following command:

```bash
python -m unittest discover tests
```

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests with suggestions for improvements, additional features, or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
