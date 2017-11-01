






# project2

this is the README file for the project2 of Digital Control.

![image](https://user-images.githubusercontent.com/31491698/32280509-5a982138-bed9-11e7-9576-2bb00dd510f5.png)

this is the the WifiBlock and it content the tcplnit function.

the fucntion coder.extrinsic is used to get the MATLAB code.

this block is used to connect the example simulink diagram to thge roomba.

in other words it makes it possible to communicate with the roomba.

![image](https://user-images.githubusercontent.com/31491698/32281662-bd35806c-bedc-11e7-953f-fd41649671fe.png)

the above is the SensorBlock.

the SensorBlock control the six eyes.

the roomba has six eyes. 

each eye is going to read an obstacle. 

![image](https://user-images.githubusercontent.com/31491698/32282929-3618647e-bee0-11e7-9ed0-a91b653c6963.png)

the above is the WheelsBlock.

the WheelsBlock is used to control the wheels of the roomba.

this control if the roomba will turn right, left or reverse.

![image](https://user-images.githubusercontent.com/31491698/32286981-88893f24-beec-11e7-90f1-b4938db549fa.png)

this is the TemperatureBlock.

the block has code to control the temperature.

by changing the temperature putting the temperature to certain level we can get the roomba to run or stop.

![image](https://user-images.githubusercontent.com/31491698/32288072-08ebabae-bef0-11e7-9f4d-87df0bd0409a.png)

the above is the RealTime Pacer block.

this block  force the simulation to run in real (wall clock) time

***the zipped file is uploaded on the top left***

the file contains the library and the example file.


***the project explained****


the wheels block contains 2 states: the on and the off.

for the project when the temperature is less than 80 the on state the roomba keep running.

for temperature greater or equal to 80 the off state activate and the roomba stop.

when running the roomba use the sensor to avoid the obstacle.

