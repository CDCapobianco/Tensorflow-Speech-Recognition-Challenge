# Tensorflow Speech Recognition Challenge
A Speech Recognition system built with DL techniques, based on the Tensorflow SR Challenge Dataset. The objective is to build a system which can classify 31 different vocal commands.


# The Dataset

It consists in 64727 one second long .wav files, each containing a single spoken English word. These words are from a small set of commands, and are spoken by a
variety of different speakers.  

# Preprocessing

The typical audio classification approach consists in decoding .wav files in numpy arrays and apply STFT (Short-Time Fourier Transform) to get  a bi-dimensional tensor, representing the spectrogram of each audio file.

In this way the audio classification problem can be treated as a typical CV classification problem.


# The Model

CNN (Convolutional Neural Network) was considered for this task. The validation set is 10356 files and the test set 2589 files

| Test Performance (Accuracy) | Test Performance (Precision) | Test Performance (Recall) |
| ------------- | ------------- | ------------- |
| 90%  | 93.9 %  | 87.9%  |

