# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory: 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

### Linear Interpolation

![Kn Exp7 L1](https://user-images.githubusercontent.com/75235386/204820744-4ad32e70-1a37-4004-9927-8691b63aaee7.png)
![Kn Exp7 L2](https://user-images.githubusercontent.com/75235386/204820777-88fe449d-59bc-4812-97cc-09abacfd517f.png)

![Kn Exp7 L3](https://user-images.githubusercontent.com/75235386/204820815-fab7fdae-f55d-4b7d-98d0-e3455f4840e1.png)
![Kn Exp7 L4](https://user-images.githubusercontent.com/75235386/204820848-51d8e813-bc4e-472d-8d34-dfe94a278603.png)






### Circular Interpolation

![Kn Exp7 C1](https://user-images.githubusercontent.com/75235386/204820920-0dcf79ae-40c1-4e7a-9464-8a355a7487b8.png)


### Output:

### Linear Interpolation:
![Kn Exp7 oL1](https://user-images.githubusercontent.com/75235386/204821476-0b28fcce-eba3-4240-8de3-e4bff05e7c6d.png)

### Circular Interpolation:
![Kn Exp7 oC1](https://user-images.githubusercontent.com/75235386/204821595-bbc1b5b2-1216-4e65-94bd-09a770ad9eb4.png)




### Result: 
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.



 
