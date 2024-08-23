# Speech_Emotion_Recognition
Project Highlights:

Data Acquisition and Preparation:

 -Utilized the Kaggle API to download the TESS dataset, containing over 2800 audio files with various emotional labels.

 -Preprocessed the audio data using librosa, a Python package for audio and music analysis, to visualize waveforms and spectrograms of the different emotions.
 
Feature Extraction:

 -Extracted MFCC (Mel Frequency Cepstral Coefficients) features from the audio files, which are essential for representing the power spectrum of the sound.

 -Created a structured dataset for training by associating each audio file with its respective emotion label.

Deep Learning Model Development:


 -Built a Sequential LSTM (Long Short-Term Memory) model using Keras, designed to capture the temporal dependencies of the audio features.

 -The model architecture includes layers for LSTM, Dense (fully connected layers), and Dropout for regularization to prevent overfitting.

Model Training and Evaluation:


 -Trained the model over 30 epochs, achieving promising accuracy metrics on both training and validation datasets.

 -Visualized the training process using accuracy and loss curves to ensure consistent learning.

 -Evaluated the model’s performance using a confusion matrix and classification report, providing insights into how well the model distinguishes between different emotions.


Visualization and Insights:

 -Generated waveplots and spectrograms for various emotions, offering a visual understanding of how different emotions manifest in speech.

 -Correlation heatmaps to analyze and present the model's prediction capabilities visually.
