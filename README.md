# FM-using-Python

Aim


To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries. 

Apparatus Required

1.	Software: Python with NumPy and Matplotlib libraries
2.	Hardware: Personal Computer
  
Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:



Algorithm


1.	Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
2.	Generate Time Axis: Create a time vector for the signal duration.
3.	Generate Message Signal: Define the message signal as a cosine wave.
4.	Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
5.	Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
6.	Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

Program

<img width="823" height="738" alt="Screenshot 2025-10-17 221854" src="https://github.com/user-attachments/assets/55b2e3c3-d781-4389-b5e5-662dd76bcf42" />

Output Waveform
<img width="1920" height="1200" alt="Screenshot 2025-10-17 221920" src="https://github.com/user-attachments/assets/d3aa7cd7-c823-45d5-bfa9-6e2049bc311b" />


Tabular Column

![WhatsApp Image 2025-10-17 at 22 01 23_23468d62](https://github.com/user-attachments/assets/488ad367-ed59-4c00-a8c5-b3a2d63ac0a1)


Calculation




Result


The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
