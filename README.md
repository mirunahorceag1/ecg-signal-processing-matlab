# ecg-signal-processing-matlab
Academic MATLAB project that applies an FIR band-pass filter to an ECG signal and compares the original and filtered signals in the time and frequency domains.
# ECG Signal Processing in MATLAB

This academic project was developed for the Biological Signal Processing course at the Faculty of Medical Engineering, Politehnica Bucharest. It explores how band-pass filtering changes an ECG signal in the time and frequency domains.

## Methods

- Extracted the first channel of ECG record 100 from the MIT-BIH Arrhythmia Database P-wave Annotations dataset.
- Used a 256-point Fast Fourier Transform (FFT) to compare the spectra of the original and filtered signals.
- Designed and applied a 50th-order FIR band-pass filter with cutoff frequencies of 8 and 50 Hz, using the script's configured sampling frequency of 180 Hz.
- Plotted the original and filtered ECG signals alongside the filter's magnitude and phase responses.

## How to run

1. Open the project folder in MATLAB with Signal Processing Toolbox installed.
2. Place the input file `100m.mat` in the same folder as `psb.m`. The script expects the file to contain a variable named `val`.
3. Run `psb.m` to display the six plots.

## Project files

- [MATLAB script](psb.m)
- [Full project report (PDF, in Romanian)](Biological_Signal_Processing_Report.pdf)
