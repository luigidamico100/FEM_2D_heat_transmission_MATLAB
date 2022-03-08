# Finite element approach (FEM) for a heat diffusion problem, simulation and control.
This project is about the implementation of the 2D FEM algorithm and its application to a the heat diffusion problem. Firstly, the steady-state case is treated, subsequently the time evolution is taken into account. A simple relay controller is finally developed a to set the desired temperature.   
The project code follow the FEM mathematical notation of the book *Fundamentals of Finite Element Analysis: Linear Finite Element Analysis (1st edition, 2018)* of Prof. Ioannis Koutromanos.  

In the file *presentation.pdf* there is a presentation about this project (*presentation.pptx* contains playable videos). Briefly, the key points are: 
- Physical model - From the physics to the mathematifcal model
- From the strong to the weak form - Mathematical derivation and equivalence
- Finite Element Method - Implementation of the 2D FEM algorithm with triangle elements
- FEM Code Verification - execution of the order-of-accuracy test through the MMS method
- Verification of unsteady case - execution of the order-of-accuracy test through the MMS method
- Control and simulations - Implementation of a Relay controller
- Conclusions - Further developments and references
