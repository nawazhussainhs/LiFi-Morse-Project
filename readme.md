# Li-Fi Morse Code Communication System

##  Overview
This project demonstrates a simplified version of Li-Fi (Light Fidelity) communication using Morse code instead of traditional binary modulation.

Li-Fi is a wireless communication technology that uses visible light (LEDs) to transmit data at very high speeds. In real-world systems, data is encoded in binary form (0s and 1s) using rapid LED switching.

In this project, Morse code is used as a modulation technique to simplify implementation and understanding.

---

## Concept

Instead of transmitting binary data:
- Morse code (dots and dashes) is used
- LED acts as the transmitter
- LDR (Light Dependent Resistor) acts as the receiver

---

## Components Used
- LED (Light Transmitter)
- LDR (Receiver)
- Microcontroller (Arduino-Uno)
- Resistors and basic circuit components

---

## Working Principle

1. Input data is converted into Morse code
2. LED blinks according to Morse patterns:
   - Dot (short blink)
   - Dash (long blink)
3. LDR detects changes in light intensity
4. Signal is interpreted and decoded back into text

---

## Challenges Faced

- The LDR was **not sensitive enough to accurately detect spacing gaps**
- Morse code does not have a strict, reliable representation for **word separation**
- Timing inconsistencies caused decoding issues

---

## Solution Implemented

To overcome spacing limitations:
- A **custom word dictionary approach** was used
- Instead of relying on space detection, predefined words were mapped
- This ensured accurate decoding despite hardware limitations

---

## Applications of Li-Fi (Real World)

- High-speed wireless communication
- Secure data transmission (light cannot penetrate walls)
- Underwater communication systems
- RF-restricted environments (hospitals, airplanes)

---

## Future Improvements

- Replace LDR with more precise photodiode sensors
- Implement proper binary modulation instead of Morse code
- Improve timing synchronization
- Increase transmission range and reliability

---

## Team Members
Nawaz Hussain  
Manukonda Vivekananda Reddy  
Manjunath D  
Aadesh Rakesh  
