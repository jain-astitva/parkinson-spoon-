Low-Cost Assistive Device for Parkinson's Tremor Stabilization 🥄

Supervisor: Prof. I.A. Palani

This project focuses on the design and development of an ultra-affordable, closed-loop system to actively stabilize hand tremors experienced by individuals with Parkinson's disease. The resulting prototype successfully demonstrates real-time compensation, delivering essential functionality at one of the lowest manufacturing cost points in the market.

Project Goal & Key Achievement

The core challenge was to develop an active stabilization mechanism under a stringent cost constraint.

Goal: To stabilize involuntary hand tremors (Parkinsonian or Essential Tremor).

Key Achievement: Delivered a functional, reliable prototype with an estimated component cost of less than ₹400 (approx. $5 USD), maximizing accessibility for patients in need.

⚙️ Hardware and Methodology

The system uses common, inexpensive micro-electromechanical components to capture tremor movement and translate the corrections into precise counter-movement.

Core Components

Component

Function

Microcontroller

Arduino Nano (Main processing unit)

Sensor

MPU-6050 Gyroscope (Measures angular velocity/tremor)

Actuator

SG90 Micro Servo Motor (Applies real-time counter-motion)

Output

Spoon/utensil attachment

Closed-Loop Control Mechanism (PID)

The stabilization relies on a Proportional-Integral-Derivative (PID) Controller implemented within the Arduino Nano.

Sensing: The MPU-6050 Gyroscope continuously detects the orientation and acceleration of the device, generating feedback on the tremor's direction and magnitude.

Processing (PID): The Arduino Nano runs the PID algorithm, which calculates the necessary corrective movement required to bring the tremor back to the desired setpoint (zero movement).

Actuation: The Arduino sends a signal to the Servo Motor, which executes the calculated movement in the opposite direction of the detected tremor.

Stabilization: This continuous cycle of sensing, compensating, and moving results in the stabilization of the utensil head relative to the ground, effectively cancelling the tremor.

Design for Accessibility and Impact

The entire circuit (Arduino Nano, Gyroscope, and wires) was compacted into a small, portable housing, directly connected to the servo mechanism holding the utensil.

Cost Optimization: Components were selected specifically to meet the $400$ Rs goal without sacrificing functional reliability, making the technology highly scalable and accessible.

Reliability: The prototype successfully demonstrated effective stabilization against simulated and real-world tremors, making it suitable for practical daily use.

Supervision: The project was completed under the expert guidance of Prof. I.A. Palani.
