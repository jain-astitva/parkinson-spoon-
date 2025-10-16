

### **Low-Cost Assistive Device for Parkinson’s Tremor Stabilization 🥄**

**Supervisor:** *Prof. I. A. Palani*

**Overview:**
This project focuses on the **design and development of an ultra-affordable, closed-loop assistive device** to actively stabilize hand tremors in individuals with Parkinson’s disease. The developed prototype achieves real-time tremor compensation while maintaining one of the **lowest manufacturing costs** in the market.

---

#### **Project Objective & Key Achievement**

* **Objective:** Develop an active stabilization mechanism for **involuntary hand tremors** (Parkinsonian or Essential Tremor) under stringent cost constraints.
* **Key Achievement:** Designed and implemented a **fully functional prototype** with an estimated component cost of **₹400 (≈ $5 USD)**, providing **maximum accessibility** for patients in need.

---

#### **⚙️ Hardware and Methodology**

The system utilizes inexpensive **micro-electromechanical components** for motion detection and active counter-movement through a **closed-loop PID control mechanism**.

| **Component**                | **Function**                                   |
| ---------------------------- | ---------------------------------------------- |
| **Arduino Nano**             | Main processing and control unit               |
| **MPU-6050 Gyroscope**       | Measures angular velocity and tremor magnitude |
| **SG90 Micro Servo Motor**   | Executes real-time corrective motion           |
| **Spoon/Utensil Attachment** | Output interface for tremor stabilization      |

---

#### **Closed-Loop Control (PID Mechanism)**

1. **Sensing:** The MPU-6050 continuously detects the orientation and tremor acceleration.
2. **Processing:** The Arduino Nano runs a **PID algorithm** that computes corrective movement to maintain a steady position (setpoint ≈ zero tremor).
3. **Actuation:** The servo motor performs the computed counter-motion to neutralize tremors.
4. **Stabilization:** The loop repeats continuously, resulting in a stabilized utensil head relative to the ground, effectively canceling out tremors in real time.

---

#### **Design for Accessibility and Impact**

* **Compact Design:** All components (Arduino, Gyroscope, Servo, and wiring) were integrated into a **small, portable housing**.
* **Cost Optimization:** Achieved the target cost of **₹400** without compromising reliability, enabling **large-scale accessibility**.
* **Reliability Testing:** Demonstrated consistent stabilization performance under both **simulated and real-world tremor conditions**.
* **Social Impact:** Offers an affordable solution for daily use by patients with limited access to high-cost medical assistive devices.

---

**Outcome:**
Successfully validated a **low-cost, reliable tremor stabilization prototype**, paving the way for scalable and accessible assistive technologies in healthcare.


