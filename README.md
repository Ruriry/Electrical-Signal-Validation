# Electrical Signal Simulation & Automated Validation

A Python project that simulates electrical signals, analyzes noise, and automatically validates measurements against predefined specifications.

## Features

- Generates sinusoidal signals with Gaussian noise.
- Calculates RMS voltage, SNR, and peak voltage.
- Performs frequency analysis using FFT.
- Automates PASS/FAIL validation tests.
- Generates measurement reports and visualizations.

## Technologies

Python | NumPy | Pandas | Matplotlib | Google Colab

## Results

- **5 validation tests:** 3 PASS, 2 FAIL
- **Detected Frequency:** 1,000 Hz
- **Signal-to-Noise Ratio:** 17.17 dB
- **Overall Status:** FAIL (due to simulated noise exceeding test limits)

## How to Run

1. Open `Electrical_Signal_Validation.ipynb` in Google Colab.
2. Select **Runtime → Run all**.
3. View the generated plots and validation results.

---

*Note: All signals are simulated, and test specifications are illustrative.*
