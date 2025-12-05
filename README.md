# EVALUATION-OF-FREQUENCY-DIVISION-MULTIPLEXING

### Aim:
Study of TDM pulse amplitude modulation/ demodulation with transmitter block (clock) and channel identification information linked directly to the receivers.  

### Apparatus Required:

1)	Experimental kit DCL-02  
2)	Connecting chord  
3)	Power supply  
4)	20 MHz dual trace oscilloscope.  

### Theory:
In PAM, PPM the pulse is present for a short duration and for most of the time between the two pulses no signal is present. This free space between the pulses can be occupied by pulses from other channels. This is known as Time Division Multiplexing. Thus, time division multiplexing makes maximum utilization of the transmission channel. Each channel to be transmitted is passed through the low pass filter. The outputs of the low pass filters are connected to the rotating sampling switch (or) commutator.
It takes the sample from each channel per revolution and rotates at the rate of f s. Thus the sampling frequency becomes fs the single signal composed due to multiplexing of input channels. These channels signals are then passed through low pass reconstruction filters. If the highest signal frequency present in all the channels is fm, then by sampling theorem, the sampling frequency fs must be such that fs≥2fm. Therefore, the time space between successive samples from any one input will be  Ts=1/fs, and Ts =1/2fm.

### Procedure:

1)	Refer to the block diagram and carry out the following connections and switch setting. 
2)	Connect power supply in proper polarity DCL-02 and s it switch it on.  
3)	Connect 250hz, 500hz, 1khz and 2khz sine wave signals from the function generator to the multiplexer input channels CH0, CH1,CH3 by means of connecting chords.  
4)	Connect the multiplexer output txd of the transmitted section to the de multiplexer input rxd of the receiver section.  
5)	Connect the output of the receiver section CH0, CH1, CH2,CH3 to the IN0, IN1, IN2. IN3 of the filter section.  
6)	Connect the sampling clock TX CLK channel identification clock TXSYNC of the transmitter section to the corresponding RXCLK, RXSYNC of the receiver section respectively.  
7)	Set the amplitude of the input sine wave desired.   
8)	Take the observations as mentioned below.

### Kit Diagram
<img width="480" height="324" alt="image" src="https://github.com/user-attachments/assets/b2f8f171-ceff-4481-add2-bc4ef1c42506" />

### Model Graph
<img width="718" height="933" alt="image" src="https://github.com/user-attachments/assets/09c11b43-dc9c-4bf9-a04a-0728d0b0fea3" />

### Tabulation

<img width="672" height="448" alt="image" src="https://github.com/user-attachments/assets/05600b28-ba54-4cd4-9ff4-f088865e85ae" />

### Result



