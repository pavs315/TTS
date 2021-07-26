# Tacotron 2 and WaveGlow model TTS

The Tacotron 2 and WaveGlow model forms a text-to-speech system which synthesises human-like speech without additional prosody information. 

## Tacotron 2 
Tacotron 2 is a neural network architecture for natural speech synthesis. It consists of recurrent seq2seq feature prediction network which maps char embeddings to mel spectograms, which are usually fed into a vocoder to generate speech. 

## WaveGlow 
WaveGlow is a flow-based network which can generate speech from mel-spectograms.

In this model, pre trained Tacotron 2 and WaveGlow models are loaded from torch.hub.



