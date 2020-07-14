### The functions found within this repo are mainly for generating speech features (e.g., MFCCs, jitter, snr), which can be used within machine learning tasks. The free speech analysis software, Praat, is used in the creation of some of these features.

##### mfcc_helper_function: This is a function that calculates Mel frequency cepstral coefficients, which, in short, are transformed Fourier transforms that can be used as features in speech or audio machine learning tasks. Also included is a stacking function (to create 3D arrays for multiple individual MFCCs) and a convenience shuffling function for later analysis.

##### tabular_speech_features_function: This is a function that calculates quite a few features for speech/audio analysis and machine learning tasks. The number of features could potentially be reduced via a recursive feature elimination approach. This function calls on Praat, a free computer software package for speech analysis in phonetics.
