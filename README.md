# Speech and Audio Processing Using LPC and Python

A Python-based speech processing project exploring Linear Predictive Coding (LPC), audio preprocessing, spectral analysis, speech reconstruction, and residual signal analysis.

## Project Overview

This project implements an LPC-based speech processing workflow using Python. It processes a recorded speech signal, extracts its linear predictive characteristics, reconstructs speech through synthesis filtering, and evaluates the reconstructed signal.

## Objectives

- Load and inspect a speech recording.
- Resample audio to a standard sampling rate.
- Apply peak normalization and pre-emphasis.
- Visualize the signal in the time-frequency domain using STFT.
- Estimate LPC coefficients using Levinson-Durbin recursion and Burg LPC.
- Perform LPC analysis filtering to obtain the residual signal.
- Reconstruct speech through LPC synthesis filtering.
- Evaluate reconstruction using quantitative performance metrics.
- Estimate speech formants and examine residual autocorrelation.

## Project Structure

```text
Speech-Audio-Processing-LPC/
├── notebooks/
│   └── SAP.ipynb
├── audio/
│   ├── original/
│   │   └── Rahul_voice_recording_BIT.wav
│   └── processed/
│       ├── preprocessed_voice.wav
│       ├── reconstructed_voice.wav
│       └── residual_signal.wav
├── results/
│   └── graphs/
├── requirements.txt
└── README.md
```
