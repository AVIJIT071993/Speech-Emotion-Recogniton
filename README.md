# Speech-Emotion-Recogniton

This project enables you to predict the mood of a human being by analyzing the speech of that person. The model is trained using ravdess dataset. Features are extracted, mfcc, chroma and mel from a sound file for their analysis. Randomforest classifier is used for analysis. Audio is recordered then feature engineered and after that it is feeded into the model for prediction. After analyzing the audio, the mood of the person is predicted.

You can download the dataset from kaggle: https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio

**Libraries required for the project are as follows:**

1. pip install librosa
2. pip install soundfile
3. pip install os
4. pip install glob
5. pip install pickle
6. pip install pyaudio
7. pip install wave
8. pip install array
9. pip install numpy

**Librosa:**

LibROSA is a python package for music and audio analysis. It provides the building blocks necessary to create music information retrieval systems. Librosa’s load function will read in the path to an audio file, and return a tuple with two items. The first item is an ‘audio time series’(type: array) corresponding to audio track. The second item in the tuple is the sampling rate that was used to process the audio. 

**Soundfile:**

SoundFile is an audio library based on libsndfile, CFFI and NumPy. SoundFile can read and write sound files. File reading/writing is supported through libsndfile, which is a free, cross-platform, open-source (LGPL) library for reading and writing many different sampled sound file formats that runs on many platforms including Windows, OS X, and Unix. It is accessed through CFFI, which is a foreign function interface for Python calling C code. CFFI is supported for CPython 2.6+, 3.x and PyPy 2.0+. SoundFile represents audio data as NumPy arrays.

**Pyaudio:**

PyAudio provides Python bindings for PortAudio, the cross-platform audio I/O library. With PyAudio, you can easily use Python to play and record audio on a variety of platforms.

**Wave:**

The wave module provides a convenient interface to the WAV sound format. It does not support compression/decompression, but it does support mono/stereo.

**Random Forest Classifier:**

A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree. 

Random forest, like its name implies, consists of a large number of individual decision trees that operate as an ensemble. Each individual tree in the random forest spits out a class prediction and the class with the most votes becomes our model’s prediction.
