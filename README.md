# Development-of-Passive-Radar-System-
Created an analog receiver chain using low-noise amplifier and a bandpass filter with a 2 MHz bandwidth. The digital part of the setup involved a Software Defined Radio (SDR) equipped with an 8-bit ADC for digitization. The output from the SDR was channeled to an Nvidia Jetson Nano Graphics Processing Unit (GPU) to enable real-time data processing and the deployment of an Auto-Correlation Spectrometer. To optimize this system, I implemented multi-threaded parallel programming in Python, utilizing TensorFlow for the calculation of the signal's target velocity and acceleration.
