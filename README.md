# losdrone

## Step 1
**Date:** 02/04/2026 | **Duration:** 2.0 hrs

**Summary:** 
Researched and finalized all components for a 5-inch quadcopter build. This includes selecting a Mark 4 22.5cm frame for stability, determining motor KV specifications, and choosing the SpeedyBee F405 flight controller stack alongside HQProp 5-inch aggressive propellers.

* **Tools Used:** Google, YouTube, ChatGPT, Betaflight tutorials

![Step 1 Image](./Step%201/components.png)

## Step 2
**Date:** 03/04/2026 | **Duration:** 1.0 hrs

**Summary:** 
Finalized the power system by selecting 1950KV 6S BLDC motors and a 1500mAh 4S 120C battery. Calculated the quadcopter's estimated bare weight (235-260g) and estimated thrust metrics (900-1200g per motor), confirming the setup is suitable for freestyle and racing flight styles.

* **Tools Used:** Google, Robu Store, Calculator

![Step 2 Image](./Step%202/mark4frame.png)

## Step 3
**Date:** 03/04/2026 | **Duration:** 1.5 hrs

**Summary:** 
Conducted initial tests on the flight controller and ESC stack using Betaflight via a USB connection. Verified that internal sensors (gyro, accelerometer, and barometer) functioned correctly and that the motors reliably responded to inputs without overheating or jittering when powered on by the LiPo battery.

* **Tools Used:** Betaflight, Google, Calculator, Multimeter, LiPo battery charger

![Step 3 Image](./Step%203/esc_wiring.png)

## Step 4
**Date:** 04/04/2026 | **Duration:** 2.0 hrs

**Summary:** 
Performed the primary electrical assembly. This involved meticulously soldering the motor wires to the ESC, attaching a 1000μF 35V capacitor to protect against voltage spikes, connecting the XT60 battery leads, and wiring the receiver. The system was successfully powered up without smoke or excessive heat and was verified within Betaflight.

* **Tools Used:** Betaflight, Soldering Kit, YouTube

![Step 4 Image](./Step%203/soldered_esc_1.jpeg)
![Step 4 Image](./Step%203/soldered_esc_2.jpeg)


## Step 5
**Date:** 06/04/2026 | **Duration:** 2.5 hrs

**Summary:** 
Fully assembled the physical frame and electronics stack. Mounted the ESC, flight controller, and motors to the quadcopter arms in their correct layout (M1/M4 CW, M2/M3 CCW). Secured the receiver antenna and attached the top plate. A minor wire management issue was noted (excess motor wires), which will need to be addressed to avoid the wires interfering with the propellers in the future.

* **Tools Used:** Betaflight, Screwdriver Set

Watch the assembly video guide

![Assembly 1 Video](./Step%206/assembly%201.mp4)

## Step 6
**Date:** 09/04/2026 | **Duration:** 2.0 hrs

**Summary:** 
Completed the final drone assembly by attaching the propellers, cover, and battery straps. Bound the RadioMaster transmitter to the quadcopter and configured Betaflight with specific flight rates, an 80% motor output cap, and mapped switches for flight modes (Acro, Horizon, Angle) as well as the arm button. After calibrating the accelerometer, the project smoothly culminated in a successful inaugural line-of-sight (LOS) hover test!

* **Tools Used:** Betaflight

Watch the assembly video guide

![Assembly 3 Video](./Step%206/assembly%203.mp4)

### Final look
---

![Step final Image](./Step%206/rc-and-drone.jpeg
)
