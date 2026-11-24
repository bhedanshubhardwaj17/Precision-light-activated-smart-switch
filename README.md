# Precision-light-activated-smart-switch
LDR-based automatic light sensing and relay switching circuit with adjustable threshold and hysteresis using LM358.
Precision Light-Activated Smart Switch with Adjustable Threshold and Hysteresis

An LDR-based automatic light-sensing and relay switching circuit designed using an LM358 op-amp, BC547 transistor, potentiometer and positive feedback hysteresis.

Project Overview

This project demonstrates an automatic light-activated switching system that detects changes in ambient light and controls an electrical load through a relay.

The LDR senses the surrounding light intensity. As darkness increases, the LDR resistance increases, changing the sensor voltage. The LM358 compares this voltage with an adjustable reference voltage set by a potentiometer.

When the sensor voltage crosses the lower switching threshold, the comparator output changes state, activating the BC547 transistor and relay. The relay contacts switch the connected load ON, while the output LED indicates the selected switching state.

Positive feedback provides hysteresis, helping prevent unwanted rapid switching when the light level is close to the switching threshold.

Circuit Components

Component| Function
LDR| Detects ambient light intensity
LM358 Op-Amp| Voltage comparison
Potentiometer| Adjusts switching threshold
BC547 Transistor| Drives the relay
Relay| Controls the connected load
Feedback Resistor| Provides hysteresis
LED| Indicates output state

Working Principle

1. Light Detection: The LDR changes its resistance according to the intensity of incident light.
2. Voltage Comparison: The LM358 compares the sensor voltage with the reference voltage.
3. Threshold Adjustment: The potentiometer adjusts the reference voltage and controls light sensitivity.
4. Relay Activation: When the switching threshold is crossed, the comparator output drives the BC547 transistor and activates the relay.
5. Hysteresis: Positive feedback creates separate switching thresholds for ON and OFF transitions, reducing unwanted rapid switching.
6. Output Indication: The indicator LED shows the selected output state.

Key Features

- Automatic light-dependent switching
- Adjustable light sensitivity
- LM358-based comparator operation
- BC547 transistor-based relay driving
- Positive feedback hysteresis
- LED-based output indication

Core Electronics Concepts

- LDR and Photoconductivity
- Operational Amplifier and Comparator
- Voltage Divider
- Reference Voltage Adjustment
- Transistor Switching
- Relay Driver Circuit
- Positive Feedback and Hysteresis

Applications

- Automatic street lighting
- Garden and outdoor lighting systems
- Light-sensitive control systems
- Energy-efficient lighting automation
- Automatic day/night switching circuits

Skills Demonstrated

- Analog Electronics
- Electronic Circuit Design
- Comparator Applications
- Sensor Interfacing
- Transistor-Based Switching
- Relay Control
- Circuit Analysis and Troubleshooting

Project Documentation

- Circuit Diagram: To be uploaded
- Hardware Implementation: To be uploaded
- Testing and Observations: To be documented

Project Category

Academic Project | Electronic Devices and Circuit Analysis | Electronics and Communication Engineering

---

Note: Actual circuit photographs, circuit diagrams and measured test results will be added as project documentation.
