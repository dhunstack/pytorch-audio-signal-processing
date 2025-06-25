# Audio Signal Processing Toolkit

This project is a complete reimplementation of Valerio Velardo's Audio Signal Processing Course using PyTorch instead of librosa. It preserves the same concepts and algorithms while leveraging PyTorch's GPU acceleration capabilities and deep learning integration.

## Overview

This repository contains implementations of common audio signal processing algorithms including:

- Amplitude Envelope
- Fast Fourier Transform (FFT)
- Magnitude Spectrum
- Mel Spectrogram
- Root Mean Square Energy
- Short-Time Fourier Transform (STFT)
- Zero Crossing Rate (ZCR)

## Requirements

- Python 3.11+
- PyTorch
- torchaudio
- torchcodec
- matplotlib
- numpy

## Usage

Open the Jupyter notebooks to explore each audio processing technique. Example audio files are provided in the `audio` directory.

```bash
jupyter notebook
```

## Dataset

Sample audio files include:
- Classical pieces (debussy.wav)
- Voice recordings (voice.wav)
- Musical instruments (piano_c.wav, sax.wav, violin_c.wav)
- Noise samples (noise.wav)
