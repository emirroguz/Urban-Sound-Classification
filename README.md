# Urban Sound Classification with Convolutional Neural Networks

<p align="center">
  <img src="https://github.com/emirroguz/Urban_Sound_Classification/assets/147976345/da494146-16e1-4e08-9e83-080c96d9a770" width="400" height="300" alt="Urban">
</p>

## Overview
- This project aims to classify urban environmental sounds using convolutional neural networks (CNNs). The *UrbanSound8K* dataset is utilized for this purpose. The project involves transforming audio signals into spectrograms and training a CNN model for classification.

## Key Features
- Audio signal transformation into spectrograms using librosa library.
- Utilization of TensorFlow and Keras for deep learning implementation.
- Development of a CNN model for sound classification.
- Evaluation of model performance on various datasets.
- Prediction of sound classes on randomly selected audio files.

## Dataset
- The UrbanSound8K dataset consists of *8732* sound samples across ten different sound classes, recorded in various urban environments. Each sound file is labeled with a specific category.
- Dataset: [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html)

## Model Development
- The CNN model architecture comprises convolutional and pooling layers followed by fully connected layers. The model is trained using the Adam optimizer and sparse categorical cross-entropy loss function.

## Evaluation
- The model is evaluated on separate *training*, *validation*, and *test* sets to assess its performance in terms of accuracy and loss metrics. Early stopping is implemented to prevent overfitting.

## Dependencies
- *Python 3.x*
- *Librosa*
- *NumPy*
- *OpenCV*
- *Matplotlib*
- *TensorFlow*
- *Keras*
- *Scikit-learn*

## Usage
To use this project:
1. Clone the repository.
2. Install the dataset.
3. Run the urban_sound_notebook.ipynb Jupyter notebook.

***Note:***
- In the 4th code block of the Jupyter notebook, the command "***us.audio_to_spectrogram(audio_folder_path, image_folder_path)***" is commented out. If the user does not have a sample "*Spectrograms*" folder available, this line should be uncommented and executed to generate the required spectrogram images.
