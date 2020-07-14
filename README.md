### The functions found within this repo are mainly for generating speech features (e.g., MFCCs, jitter, snr), which can be used within machine learning tasks. The free speech analysis software, Praat, is used in the creation of some of these features.

##### Anomalous_Speech_Classification_Tabular_ML_and_CNN: This Jupyter notebook includes some Tabular ML and neural network analyses on speech data that was derived from the Saarbruecken Voice Database (http://www.stimmdatenbank.coli.uni-saarland.de/help_en.php4). Audio clips of both pathological and healthy voices voicing an "a" sound were downloaded and the functions within tabular_speech_features_function were used to extract features from all voice clips. This notebook includes both a traditional machine learning approach using scikit-learn, and some testing with Keras and Tensorflow for practice. 

##### mfcc_helper_function: This is a function that calculates Mel frequency cepstral coefficients, which, in short, are transformed Fourier transforms that can be used as features in speech or audio machine learning tasks. Also included is a stacking function (to create 3D arrays for multiple individual MFCCs) and a convenience shuffling function for later analysis.

##### tabular_speech_features_function: This is a function that calculates quite a few features for speech/audio analysis and machine learning tasks. The number of features could potentially be reduced via a recursive feature elimination approach. This function calls on Praat, a free computer software package for speech analysis in phonetics.

##### Future directions: 

◊ Adding a ConvNet to analyze spectrogram images of each sound sample. 

◊ Building a multi-input Keras model that includes both tabular data and spectrogram/MFCC data. 

◊ Determining whether the addition of multiple phonemes from the dataset, such as an "i" sound, might be helpful in conjunction with the present data. 

◊ Evaluating whether the phrase including in the data set, "Guten Morgen, wie geht es Ihnen?" (Good morning, how are you?) can be used in a similar way to the individual sounds. 
