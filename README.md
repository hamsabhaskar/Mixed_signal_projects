# Mixed_signal_projects
Design and Performance Analysis of high gain, Low-power Two stage Folded Cascode Opamp
# Abstract 
In this project, we aim to design and analyze a two-stage folded cascode operational amplifier using 180 nm CMOS technology. The main goal is to achieve high gain, wide bandwidth, and low power consumption. The folded cascode topology is chosen for its ability to work efficiently at low supply voltages. The design will be simulated to observe key parameters such as gain, bandwidth, phase margin, and power dissipation.
# Introduction to Folded Cascode Configuration
Before understanding the folded cascode configuration, it is important to first understand what a cascode stage means. A cascode is essentially a combination of Common Source (CS) and Common Gate (CG) stages connected together. This type of configuration is widely used in analog circuit design due to its ability to achieve:

1)High voltage gain in operational amplifiers

2)Increased output impedance and transconductance

3)Cascode configurations are mainly of two types:

4)Normal Cascode

5)Folded Cascode

# Overview of Folded Cascode
The two-stage folded cascode operational amplifier is a widely used architecture in analog circuit design, combining high gain, wide bandwidth, and low power consumption. The first stage, a folded cascode, enhances gain and input common-mode range by “folding” the signal path, allowing both NMOS and PMOS transistors to operate effectively even under low supply voltages. The second stage, typically a common-source amplifier, provides additional gain and output drive capability. This topology achieves excellent stability, slew rate, and common-mode rejection, while maintaining low distortion and good linearity. Due to its balanced trade-off between performance and efficiency, it is well-suited for high-speed, low-voltage, and precision analog applications such as data converters, filters, and sensor interfaces.
# Design Specification
<img width="1254" height="242" alt="image" src="https://github.com/user-attachments/assets/25e9bdb7-caf7-46bf-a1b6-607041ed5c20" />


# Schematic
<img width="1650" height="905" alt="Screenshot 2025-12-02 223120" src="https://github.com/user-attachments/assets/9cb67373-30e4-4aa4-9a88-7e6306862706" />

<img width="1191" height="836" alt="Screenshot 2025-12-02 224017" src="https://github.com/user-attachments/assets/a62600b2-1bd8-4e1a-8706-7547913260ee" />



# Symbol
<img width="677" height="518" alt="Screenshot 2025-12-02 223217" src="https://github.com/user-attachments/assets/6460242b-40c7-4670-907a-e678dddacd0c" />


# Test circuit
<img width="1421" height="855" alt="Screenshot 2025-12-02 223327" src="https://github.com/user-attachments/assets/2b727be1-83fb-487d-851b-1b0da8f3a8cb" />

# AC Analysis
<img width="996" height="823" alt="Screenshot 2025-12-02 222718" src="https://github.com/user-attachments/assets/ffb3eadc-1f70-4f95-9f0d-bb3601951458" />


