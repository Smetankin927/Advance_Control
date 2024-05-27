# Advance_Control
Repository for final project in Advance control system course 2024

Code in this repository based on [Regelum](https://regelum.aidynamic.io/) framework

## How to use
1. Read "notes.pdf"
2. Run .ipynb file

## Project Description
Name: Double inverted pendulum stabilization around equilibrim point 
```math
 \theta_1 = \theta_2 = 0
```

<p align="center">
  <img src="https://github.com/Smetankin927/Advance_Control/blob/main/pendulum.png">
</p>

System parameters:

• $L_{1}$ , $L_{2}$ -lenghts of bottom and top pendulum $l_{i}=\frac{L_{i}}{2}$

• $m_{1}$ , $m_{2}$ – masses of the lower and upper pendulum, respectively

• $I_{i}=\frac{1}{3}mL_{i}^{2}$ – inertia moment

• $\theta_{1}$ , $\theta_{2}$ – angles of deviation from vertical of the lower and upper pendulum, respectively (state variables)

• $M$ – mass of cartpole

• $x$ – position of cartpole (state vatiable)

• $F$ – applied force (control variable)

• $g=9.81$ – gravitational constant

Define it in this block of code:

```python
M=2
m1=1
m2=1.25
L1=0.4
L2=0.6
I1=0.0014
I2=0.0375
g=9.8
```

