# 🎙️ Speech Pattern Recognition: LPC Analysis and Formant Estimation

A Jupyter notebook (Lab 4) that analyzes a speech signal with **Linear Predictive Coding (LPC)**, reconstructs it, and estimates its formant frequencies.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![librosa](https://img.shields.io/badge/librosa-audio-4B8BBE)

## 🧪 Steps in `SPR_LAB4.ipynb`

1. **Signal acquisition**: loads 3 seconds of librosa's `libri1` speech sample and plots the waveform.
2. **LPC analysis**: computes LPC coefficients from scratch using the autocorrelation method.
3. **Signal reconstruction**: predicts a speech frame from its LPC coefficients and compares it with the original.
4. **Formant estimation**: finds formant frequencies from the roots of the LPC polynomial.
5. **Comparison with reference values**: compares the estimated formants with standard F1/F2 values for the vowels a, e, i, o and u.
6. **Visualization**: plots the LPC spectral envelope with the formant peaks marked.

## 🚀 Running

```bash
pip install numpy matplotlib librosa scipy jupyter
jupyter notebook SPR_LAB4.ipynb
```
