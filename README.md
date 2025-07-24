\# Simscape-Based Dynamic Propulsion Model for Multirotors



\## 🚀 Overview



This project provides a \*\*dynamic simulation model\*\* of an electric propulsion system for \*\*multirotor aerial vehicles\*\*, built using \*\*MATLAB Simulink\*\* and \*\*Simscape\*\*.  

It integrates:



\- A sensor-based \*\*Electronic Speed Controller (ESC)\*\* with trapezoidal commutation.

\- A \*\*Brushless DC (BLDC) motor\*\* with electrical-to-mechanical energy conversion.

\- An \*\*aerodynamic propeller\*\* with modeled thrust and torque behavior.

\- A \*\*battery system\*\* with realistic state-of-charge (SOC) and voltage dynamics.



The model captures the interaction between electrical and mechanical subsystems, enabling realistic simulation of performance, efficiency, and control strategies under varying conditions.



This simulation is designed for:

\- Multirotor propulsion system design and testing.

\- Controller development and ESC logic validation.

\- Battery performance and endurance studies.

\- Research and educational purposes.



---



\## 📦 Features



\- \*\*ESC with Trapezoidal Commutation\*\*  

&nbsp; Implements a 6-step switching pattern for BLDC motors, partially adapted from MathWorks' reference model.



\- \*\*BLDC Motor Model\*\*  

&nbsp; Simulates realistic current, torque, and speed dynamics using Simscape components.



\- \*\*Aerodynamic Propeller Model\*\*  

&nbsp; Models nonlinear thrust and torque-speed characteristics. Easily customizable using propeller data.



\- \*\*Battery with SOC Tracking\*\*  

&nbsp; Lithium-ion battery simulation with voltage, resistance, and discharge modeling.



\- \*\*Closed-Loop Speed Control\*\*  

&nbsp; Feedback-based control adjusts ESC switching to maintain target RPM.



\- \*\*Sensor Integration\*\*  

&nbsp; Virtual sensors for rotor sector detection and speed feedback.



\- \*\*Modular Architecture\*\*  

&nbsp; Subsystems for ESC, motor, propeller, and power are modular for easy customization.



\- \*\*Scalable\*\*  

&nbsp; Expandable for multirotor configurations such as quadcopters or hexacopters.



---



\## 🛠 Requirements



\- MATLAB \*\*R2024b\*\* (replace with your version)

\- \*\*Simulink\*\*

\- \*\*Simscape\*\*

\- \*\*Simscape Electrical\*\*

\- \*(Optional)\* Aerospace Blockset for advanced propeller modeling



---



\## ▶️ How to Run



1\. Open `V\_Final\_Simscape_Dynamic_Propulsion_Model.slx` in MATLAB.

2\. Ensure all required toolboxes are installed.

3\. Click \*\*Run\*\* to simulate.

4\. Inspect results using Scope blocks or Simulink Data Inspector.



---



\## 📊 Applications



\- Multirotor propulsion system modeling.

\- ESC and controller testing.

\- Power consumption and battery life analysis.

\- Propeller-motor selection optimization.

\- Educational tool for BLDC systems and drive electronics.



---



\## ⚖️ License



\- \*\*Original Work\*\*: Licensed under the \[MIT License](LICENSE).

\- \*\*Third-Party Components\*\*: This project includes parts of the ESC logic and sensor switching pattern adapted from MathWorks'  

&nbsp; \[Design Motor Controllers with Simscape Electrical](https://github.com/mathworks/Design-motor-controllers-with-Simscape-Electrical).



See \[THIRD\_PARTY\_NOTICE.txt](THIRD\_PARTY\_NOTICE.txt) for details.



---



\## 🙋 Author



Created by \*\*\A.H. Saadati\*\*.  

Contributions, issues, and forks are welcome.



---



\## 🧠 Acknowledgements



\- Simulink and Simscape toolboxes by \*\*MathWorks\*\*.  

\- ESC switching logic and sensor subsystem adapted from:  

&nbsp; \[Design Motor Controllers with Simscape Electrical](https://github.com/mathworks/Design-motor-controllers-with-Simscape-Electrical).



