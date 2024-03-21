## Audio Amplifier
**Introduction**
An essential component in audio systems, the Audio Amplifier serves as an analog circuit primarily tasked with amplifying audio signals. Its primary function is to boost the power of an audio signal, typically sourced from a microphone, to a level suitable for playback through a speaker. Simulations were performed on LTSpice. Components used: BC547B/C transistors, LM741 opamps and diodes. 

**Microphone**
This section focuses on the microphone, which serves as the input device for the audio amplifier, capturing sound waves and converting them into electrical signals.

**Pre-Amplifier**
The pre-amplifier consists of two stages: a differential amplifier and a common-emitter (CE) amplifier. These stages focus on amplifying the amplitude (voltage) of the input from the microphone. Cascading multiple voltage amplifiers is utilized to achieve the necessary gain.

**Passive Bandpass Filter**
The passive bandpass filter plays a crucial role in removing frequencies outside the desired range (20 Hz - 20,000 Hz), ensuring that only the desired audio frequencies are passed through for amplification.

**Power Amplifier**
The power amplifier increases the current directed to the output load, ensuring that the appropriate power is delivered to the speaker. This stage is vital for driving the speaker and producing audible sound.

**Final Result**
The final result of the audio amplifier is a faithfully amplified audio signal that is suitable for playback through a speaker. This project focuses on designing and implementing each stage of the audio amplifier to achieve optimal performance and fidelity.
