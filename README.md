# SPEECH-EMOTION-DETECTION-USING-DEEP-LEARNING

DATASET
Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)

It uses only audio files

Audio-only files of all actors (01-24) are available as two separate files in the given link (~200 MB each):

Speech file (Audio_Speech_Actors_01-24.zip, 215 MB) contains 1440 files: 60 trials per actor x 24 actors = 1440. 
Song file (Audio_Song_Actors_01-24.zip, 198 MB) contains 1012 files: 44 trials per actor x 23 actors = 1012.
Total=2452

In this, I have used the libraries 
1.librosa
2.soundfile
3.sklearn (among others) to build a model using an MLPClassifier. 
This enablest it to recognize emotion from sound files. 

Steps:
1.load the data
2.extract features from it
3.Split the dataset into training and testing sets. 
4.Then, initialize an MLPClassifier and train the model. 
5.Finally,calculate the accuracy of our model.

Emotions are the key point in understanding humans and their interactions.
Research goes into locating techniques which can at least mimic human capacity to recognize feelings displayed within the shape of facial expressions, modifications in tone whilst speaking, etc. Speech Emotion Recognition (SER) is one in all such fields.Using deep learning and machine learning algorithms with the assist of Ravdess and TESS dataset,the purpose  of this project is to layout an automated emotion reputation system.
