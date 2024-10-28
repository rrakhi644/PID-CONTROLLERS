# ANGSTROMERS  
## INTERNSHIP  

**PID Control Systems: Design and Implementation Across Various Dynamic Systems**  
**Trainee Name**: MANGALI RAKESH  
**Date of Submission**: 11/08/2024  
**Institution**: GPCET  

---

## Table of Contents  
1. [Introduction](#1-introduction)  
2. [Cruise Control](#2-cruise-control)  
3. [Motor Speed](#3-motor-speed)  
4. [Motor Position](#4-motor-position)  
5. [Suspension](#5-suspension)  
6. [Inverted Pendulum](#6-inverted-pendulum)  
7. [Aircraft Pitch](#7-aircraft-pitch)  
8. [Ball & Beam](#8-ball--beam)  
9. [Conclusion](#9-conclusion)  
10. [Recommendations](#10-recommendations)  


---

### 1. Introduction  
![image](https://github.com/user-attachments/assets/03ff1417-d3a5-4ba2-bdfc-728e0baf5fc0)


#### Brief Summary  
This project explores PID control systems applied to various dynamic systems, including Cruise Control, Motor Speed, Motor Position, Suspension, Inverted Pendulum, Aircraft Pitch, and Ball & Beam. It involves designing, implementing, and evaluating PID controllers using MATLAB to meet specific performance criteria.  

#### Goals and Objectives  
- **Design**: Develop PID controllers for diverse dynamic systems.  
- **Implementation**: Simulate systems using MATLAB.  
- **Evaluation**: Assess PID controller performance based on overshoot, settling time, and stability.  

#### Boundaries and Extent  
- **Scope**: Theoretical modeling and simulation.  
- **Exclusions**: Physical implementation and real-time testing.  

#### Context and Relevance  
PID control is fundamental in control systems engineering. This project demonstrates its application and effectiveness in real-world scenarios.  

---

### 2. Cruise Control  
![image](https://github.com/user-attachments/assets/6e603dda-6a29-44c8-9391-7e5720135ea2)


#### Overview  
Cruise control systems maintain a vehicle’s speed by adjusting the throttle based on speed error.  

#### Objectives  
- **Speed Maintenance**: Keep the vehicle's speed constant.  
- **Performance Criteria**: Minimal overshoot and fast settling time.  

#### Methods  
1. **Modeling**: Transfer function for speed control.  
2. **PID Controller Design**: Implemented in MATLAB.  
3. **Simulation**: Evaluated performance through simulations.  

#### Results  
- **Overshoot**: Minimal.  
- **Settling Time**: Achieved quick stabilization.  

#### Conclusions  
PID control effectively maintained vehicle speed, meeting the performance criteria.  

---

### 3. Motor Speed  
![image](https://github.com/user-attachments/assets/aeda5320-06c2-49f4-8dc2-dd475cf4250f)


#### Overview  
This section focuses on controlling the rotational speed of a DC motor.  

#### Objectives  
- **Speed Control**: Achieve precise speed control.  
- **Error Reduction**: Minimize steady-state error.  

#### Methods  
1. **Modeling**: DC motor speed model in MATLAB.  
2. **PID Controller Design**: Tuning for speed control.  
3. **Simulation**: Performance assessment.  

#### Results  
- **Accuracy**: Precise speed control.  
- **Error**: Effective reduction in steady-state error.  

#### Conclusions  
PID control successfully managed motor speed with high accuracy and minimal error.  

---

### 4. Motor Position  
![image](https://github.com/user-attachments/assets/d8ba86a8-6928-4d0e-bba4-9949de0e00e4)


#### Overview  
Motor position control aims at accurate positioning of the motor shaft.  

#### Objectives  
- **Position Accuracy**: Exact positioning.  
- **Overshoot Control**: Minimize overshoot.  

#### Methods  
1. **Modeling**: Position control transfer function.  
2. **PID Controller Design**: Applied and tuned in MATLAB.  
3. **Simulation**: Analyzed system performance.  

#### Results  
- **Positioning**: Accurate control.  
- **Overshoot**: Controlled to acceptable levels.  

#### Conclusions  
PID control achieved accurate motor positioning with minimal overshoot.  

---

### 5. Suspension  
![image](https://github.com/user-attachments/assets/70a93452-c299-401e-afe4-86abc91b3436)


#### Overview  
Suspension control improves ride comfort and vehicle handling.  

#### Objectives  
- **Ride Comfort**: Enhance vehicle ride quality.  
- **Handling Improvement**: Improve vehicle handling.  

#### Methods  
1. **Modeling**: Suspension system model.  
2. **PID Controller Design**: Optimization for ride and handling.  
3. **Simulation**: Performance evaluation.  

#### Results  
- **Comfort**: Enhanced.  
- **Handling**: Improved.  

#### Conclusions  
PID control improved both ride comfort and handling.  

---

### 6. Inverted Pendulum  
![image](https://github.com/user-attachments/assets/1d8f40fe-c1ce-4cf3-adad-08d48b0c01fc)


#### Overview  
The inverted pendulum system aims to balance a pendulum upright on a cart.  

#### Objectives  
- **Stabilization**: Balance the pendulum.  
- **Oscillation Minimization**: Reduce instability.  

#### Methods  
1. **Modeling**: Dynamic model in MATLAB.  
2. **PID Controller Design**: Stabilization through PID.  
3. **Simulation**: System performance testing.  

#### Results  
- **Stabilization**: Achieved.  
- **Oscillations**: Reduced.  

#### Conclusions  
PID control successfully stabilized the inverted pendulum.  

---

### 7. Aircraft Pitch  
![image](https://github.com/user-attachments/assets/65712a92-8c74-4ab0-94ec-9521aee527b2)


#### Overview  
Aircraft pitch control manages the pitch angle for stable flight.  

#### Objectives  
- **Performance Metrics**: Achieve specific metrics.  
- **Stability**: Ensure pitch control stability.  

#### Methods  
1. **Modeling**: Aircraft pitch dynamics.  
2. **PID Controller Design**: Applied PID tuning.  
3. **Simulation**: Performance analysis.  

#### Results  
- **Overshoot**: 7.5%  
- **Rise Time**: 0.413 seconds  
- **Settling Time**: 9.25 seconds  
- **Steady-State Error**: 0%  

#### Conclusions  
PID control met performance metrics for aircraft pitch control.  

---

### 8. Ball & Beam  
![image](https://github.com/user-attachments/assets/c1fd25c1-efaf-4fa8-ade6-7b450ee704cb)


#### Overview  
Ball & Beam control involves positioning a ball on a beam by adjusting the beam’s angle.  

#### Objectives  
- **Position Control**: Precise ball positioning.  
- **Performance Criteria**: Meet settling time and overshoot targets.  

#### Methods  
1. **Modeling**: Ball & Beam transfer function.  
2. **PID Controller Design**: Proportional-Derivative control.  
3. **Simulation**: Performance testing.  

#### Results  
- **Settling Time**: Less than 3 seconds.  
- **Overshoot**: Less than 5%.  

#### Conclusions  
PID control achieved desired performance in ball positioning.  

---

### 9. Conclusion  
#### Summary of Key Findings  
- **Effectiveness of PID Control**: Successfully met performance criteria across systems.  
- **Versatility**: Demonstrated effectiveness in diverse applications.  

#### Implications  
Highlights PID control’s role in achieving desired system performance, offering insights for control systems engineering.  

---

### 10. Recommendations  
#### Future Work  
- **Further Optimization**: Explore advanced tuning techniques.  
- **Real-Time Implementation**: Consider practical implementations.  
- **Alternative Strategies**: Investigate other control strategies.  

---


