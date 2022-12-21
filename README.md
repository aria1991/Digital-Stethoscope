# Digital-Stethoscope
Digital stethoscope module

The `ADCfun.py` script defines three functions:

-  `analogue_to_digital()` converts an analogue audio signal to a digital signal using the `wave` module's `struct.pack()` function.

- `lowpass_filter()` applies a lowpass filter to a digital signal using the `scipy` module's `butter()` and `lfilter()` functions.

- `main()` sets up pyaudio to read in audio data from the stethoscope, converts the analogue signal to a digital signal using the `analogue_to_digital()` function, and applies a lowpass filter to the digital signal using the `lowpass_filter()` function
