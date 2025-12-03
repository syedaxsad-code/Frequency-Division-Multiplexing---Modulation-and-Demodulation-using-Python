# Frequency-Division-Multiplexing---Modulation-and-Demodulation-using-Python

__Aim__:

To generate an FDM signal by multiplexing multiple baseband message signals on different carrier frequencies, transmit (sum) them, optionally add channel noise, then recover each message by bandpass filtering and coherent demodulation in Python (Google Colab). Observe time & frequency domain signals and measure recovery quality.


__Apparatus Required__:

Google Colab (or any Python environment)

Python libraries: numpy, matplotlib, scipy (scipy.signal)


__Theory__:

FDM places different message signals in separate, non-overlapping frequency bands by modulating each message onto a distinct carrier frequency. The multiplexed signal is the sum of all modulated channels. At the receiver, bandpass filters (or tuned filters) isolate each channel; then each isolated carrier is demodulated (coherently multiplied by a synchronized carrier) and low-pass filtered to recover the original baseband.

__Procedure__:

1 — Imports and parameters

2 — Create message signals and carriers

3 — Modulate each message (standard AM DSB-SC) and form FDM signal

4 — Frequency domain (spectrum) of FDM signal

5 — (Optional) Add AWGN noise to FDM signal

6 — Receiver: isolate each channel with bandpass filter

7 — Demodulate each isolated channel (coherent) and low-pass filter to recover baseband

__Output_:

![WhatsApp Image 2025-12-03 at 19 56 39_00eef37d](https://github.com/user-attachments/assets/415b4d31-6d12-4292-89ec-8646850a9b24)
![WhatsApp Image 2025-12-03 at 19 56 40_35a8e109](https://github.com/user-attachments/assets/dae23e11-13cb-4086-90c8-36fadd080a52)
![WhatsApp Image 2025-12-03 at 19 56 40_90514573](https://github.com/user-attachments/assets/b7bcedc0-cedb-40cf-b82f-0fb9656aa80b)


__Result__:
![WhatsApp Image 2025-12-03 at 19 58 40_55213cef](https://github.com/user-attachments/assets/63c32047-7df7-4560-ba51-b4610f20acc3)

