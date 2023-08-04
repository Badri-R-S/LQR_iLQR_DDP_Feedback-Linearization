# Implementation of LQR, iLQR, DDP and Feedback Linearization techniques.

## Part 1: Cartpole-Balancing
A non linear cartpole balancing system was provided. The objective was to balance the cartpole at a single point. Hence, the system was linearized about that single point. This linearized system was used to solve for the infinite horizon controller using LQR.

![Alt text](3391a659-8510-443d-981a-ef321ad8c119.png)

## Part 2: Helicopter Hover
A similar non linear helicopter hovering system was provided. The objective was to stabilize the hovering system. The infinite horizon controller was determined for the linearized system.

![Alt text](2ad7c8bf-4a6b-41aa-9ab0-da8f0fe30060.png)

## Part 3: Hopper Stabilization
The objective was to stabilize and observe the hopper under different levels of perturbations for a set of points.

![Alt text](visualization_hopper.gif)   

## Part 4: Trajectory following for a helicopter flight

Given a non-linear system, the objective was to trabsform the system into a LTV setting and run LQR. A reference trajectory was provided, that is approximately feasible. 

![Alt text](6b805fb2-e49b-4b99-986c-31b32303ba5a.png)

![Alt text](e76752ec-16fd-48a6-b4b0-791f5c4c9d9e.png)

## Setup

Refer to **requirements.txt** to install all the necessary dependencies.
To set up Anaconda environment, refer https://www.anaconda.com/
For Mujoco-py installation, refer https://github.com/openai/mujoco-py
