# Miscellaneous projects throughout my education

## Internship in Taiwan: Human detection and tracking on fishing vessel

Introduction:
- Taiwan's fishing industry faces labor rights violations : U.S. blacklisted Taiwanese fishing vessels.
- Traditional oversight methods inadequate.
- CCTV and AI offer potential solutions.
- Internship focuses on deep learning for labor estimation.
- Study combines data labeling, model training, and evaluations.

Objective: 
- Aim to monitor working hours and ensure worker protection in the fishing industry using CCTV footage and deep learning techniques
- Focus on improving person detection accuracy under challenging on-sea conditions.
- Explore tracking methods.

Work details:
- Data Collection and Preprocessing
- Manual Data Labeling
- Object Detection Model Training and Optimization

<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/355f263b-e556-4a51-95a5-fc939d11e6e5">
</p>

<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/62b54614-e93b-45de-99dc-d79b0ec5de75">
</p>

## Levitation Controller Design of a 5-DOF Magnetic Rotor-Bearing System using Sliding Mode Control

Design levitation controller for a 5-DOF Magnetic Rotor-Bearing System :
- Utilize Sliding Mode Control (SMC) 
- Simulate the system
- Address steady state errors (using Integral Sliding Mode Control, ISMC) 

Magnetic Rotor-Bearing System:
- Utilizes radial and axial active magnetic bearings (radial AMB, axial AMB).
- Designed for stable rotor levitation.

Radial AMB Configuration:
- 8-pole heteropolar AMB with differential driving.
- Windings generate magnetic force in X and Y directions.
- Even distribution of rotor weight on X and Y axes.

<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/6712af77-5e42-4d75-88aa-806a8c3c12a8">
</p>

Coordinate Systems:
- Focus on radial motion with four degrees of freedom.
- Body coordinate (rotational and translational motions).
- Sensor coordinate (rotor position from sensing planes).

<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/0548ace6-90a4-4de5-b874-526095b3f56b">
</p>

<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/51db5d78-2584-4e53-9afc-6fbdd4682749">
</p>

Simulink model:

<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/8834fbb3-010b-4dde-a3b3-01f8588d6637">
</p>


Control Design Approach:
Combine backstepping and sliding mode control for amplifier dynamics but :
Derivation of control law with Backstepping is very complex.

Sliding Manifold:
Chosen to define the desired dynamics.
Designed to be compatible with the slowest amplifier response.

Initial assumption: Rotor does not rotate to simplify control design (Ω=0).

Switching Control Gain:
Tuned to overcome uncertainty introduced by amplifier dynamics.
![image](https://github.com/user-attachments/assets/dd7cce64-74a4-4087-a4b1-790e4ccf2b34)


<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/e9930acb-9ec4-410b-b074-7810dc139c0b">
</p>


<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/de647d41-6ba6-424d-8c56-b442c46b86e3">
</p>

<p align="center">
  <img width="788" alt="image" src="https://github.com/user-attachments/assets/00d23aa4-d73a-43bc-9761-d390f8608cae" />
</p>

<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/e2319b92-7794-4f47-a6cd-a7a0d10228b8">
</p>

Integral sliding mode controller design and results

<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/5418309f-58f2-472b-82e7-6f5f70b11c95">
</p>

<p align="center">
  <img width="776" alt="image" src="https://github.com/user-attachments/assets/32f4064f-18ed-484a-bd7c-71761dc83cee" />
</p>

Stability Achieved:
- Both SMC and ISMC demonstrated stability in rotor levitation.
- ISMC, in particular, showcased accurate levitation without steady state errors.


## Computer Vision-based Driver Scoring System using Machine Learning

Goal: Infringements detection 
- Crossing plain line
- Illegal stop or parking
- Dangerous changes of direction

Tasks: 
- Car detection and tracking
<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/673aec10-50c3-4538-b43f-b192151e8cb0">
</p>

- Behavior monitoring
<p align="center">
  <img width="460" src="https://github.com/user-attachments/assets/75568732-9b39-4ee1-ab46-4385512fa94a">
</p>






