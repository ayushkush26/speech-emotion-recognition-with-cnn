# **speech-emotion-recognition-with-cnn**

This project implements a Convolutional Neural Network (CNN) based model for Speech Emotion Recognition. The model is designed to classify emotions from audio data, achieving an accuracy rate of 88%. The implementation leverages Python and TensorFlow, utilizing deep learning techniques and audio processing methods to extract relevant features from audio signals.The project was developed using Google Colab for its ease of use and accessibility.


**Prerequisites**

* Python 3.x
* TensorFlow
* Librosa

**Datasets Used**

**RAVDESS**: The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) contains a variety of emotional speech samples that serve as a rich source for training the model.
**SAVEE**: The Surrey Audio-Visual Expressed Emotion (SAVEE) dataset provides additional emotional audio recordings, enhancing the diversity of the training data.  


**Google Colab Setup**
1. Open Google Colab: Google Colab.
2. Upload the Jupyter Notebook file speech_emotion_recognition_with_cnn.ipynb.
3. Install the required packages:
**!pip install tensorflow librosa**



**Usage**
1. Download and prepare the RAVDESS and SAVEE datasets and ensure the audio files are in a supported format (e.g., WAV).
2. Open the speech_emotion_recognition_with_cnn.ipynb notebook and run the cells to train the model.
3. Evaluate the model on the test dataset as specified in the notebook.
