# Euler-equation-for-incompressible-fluids-with-constant-density
This model simulates the behaviour of an incompressible fluid with constant density.
The fluid's behaviour is characterized by the Euler equations which say the following information:
1)The speed of the fluid is the sum of gradient of the thermodynamic work and the gravity (in the z-axis).
2)The gradient of the fluid's position (in other words, the sum of the components of the fluid's speed) is equal to 0. Here's a photo of the code used for the simulation:
<img width="622" alt="image" src="https://user-images.githubusercontent.com/109503519/234561458-461feb15-436a-4c76-894c-103585a8f69c.png">
We'll use the initial condition for the fluid's position (x,y,z)=(3,2,1) (although you can set it at the value you want in the "initial condition" in the integrator block).
For the previous inicial conditions, the position of the incompressible fluid with constant density in the first 10 seconds is the one shown on the graph below:
![image](https://user-images.githubusercontent.com/109503519/234562478-08b45147-ddcd-47c5-9343-d220dd504910.png)
Moreover, all the Euler equations are satisfied, so the simulation makes sense.
