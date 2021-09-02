# Emotional-PDF-Reader
A text-to-speech converter that modulates the voice output according to the emotions extracted from the text.

APPROACH I: USING PYTHON
We have used python libraries and modules to build an emotionally intelligent text-to-speech software.
Emotions are extracted from the text and they act as a key identifier in the modulation of output voice signal.

APPROACH II: USING TTS MODELS
Neural network based TTS employs two networks:
1. Pre-processing Neural Network
2. Vocoder

Pre-processing networks apply deep learning methodologies for feature extraction.Its output is a Mel-Spectrogram, a representation of short term power spectrum of 
sound based on the melody scale. The pre-processing tasks include - text processing, extracting linguistic features(phenomes, duration, etc.) and 
extracting vocoder features(fundamental frequency,  spectrogram,  etc.)  thatrepresent the corresponding speech signal.
The vocoder uses these parameters and performs multiple complex conversions onthese  parameters  to  generate  audio  waveforms. 
