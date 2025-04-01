## Deep Learning for Deepfake Audio Detection
This project aims to detect Deepfake generated audio by creating three different deep learning models to classify between real and fake audio. The goal is to prevent decietful or malicious AI content by correcting flagging the content as AI generated.

## Dataset
The data used comes from DEEP-VOICE: DeepFake Voice Recognition dataset. The dataset is composed of 56 ai audio files, 8 real audio files, and a csv document containing 11779 x 26 features extracted using librosa. Using librosa and the audio files, a new dataset consisting of 10 consecutive seconds datapoints were generated for better recurrent neural network analysis

## Started
The following model checkpoints are available:

  • LSTM
  • Transformer
  • Wav2Vec2

## Installation
The code requires python>=3.8. Required dependencies are found in requirements.txt.

## LSTM Model
## Transformer Model
## Wav2Vec2 Model
## Performance


