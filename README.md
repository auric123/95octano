                                                                        proyect 95octano
Group: Galaxy Crew.

Members: Raquel Lorenzo, Auric Arango, Jorge Dixon.

School: Colegio Bilingue Eben Ezer.


Introduction

Our robot was based according to the rules of wro and according to our knowledge of the subject of robotics we included several elements that we will see below. 

• design process: The process of designing our robot(95octane) was a bit rigorous, because we had to implementa compact mechanics, and all the ideas that we had in mind were functional. In the base design the robot was very loose and not very resistant vibrated a lot and we needed more reinforcement in the wheels and lower 95octane to correct this we changed the smooth wheels that were smaller for more ground and large together with that reinforcing the side parts to turn correctly and thanks to the work between us and a sea of ideas we were able to conclude with the project. 

Mechanics: 

• steering is directed based on spike programming for optimized performance, at the bottom we have.
 • driving: you drive through the hub which gives you the indications depending on the situation you are in at the time of your driving
• Chassis Design: Our robot has a square chassis that tries to simulate a conventional car. 






Electronics:

• Sensors: Proximity sensor is used to measure how far away an object or the wall is to centimeters, sensor colors that are two the first to detect the red color that turns right, detects the green color and turns the left and Orientation sensor (hub) which is brain and connects the cables of the motors to the hub that with programming makes the car move.
• Speed/Steering Control: Its speed control is thanks to the HUB and large spike motors that can reach a speed of 0 RPM to 200 RPM and its steering is handled thanks to a mechanism that is similar to the control of cars. 

• Wiring Diagram:

![image](https://github.com/auric123/95octano/assets/171710232/21b96cc4-9544-4d3e-ae6e-8dbff8ff26a6)
 
 Programming
 
•	Flowchart:

![image](https://github.com/auric123/95octano/assets/171710232/9a47f9ea-59b3-4bf8-8f43-ba88dcf4d076)


•	Strategies: As a main strategy we had to see how the sensors moved together with the engine and that it could be autonomous and specific in the colors next to the color sensor.

• Code discussion:

![image](https://github.com/auric123/95octano/assets/171710232/cbca41ba-e355-412e-a51f-cd11d438489c)

The first thing the code does is reset the Hub timer, then a loop is placed that will be performed until the timer reaches 33.2 seconds, the speed of motor A is set to 100% and motor B is placed in the 0° position.

![image](https://github.com/auric123/95octano/assets/171710232/bd14e2d3-ddd7-4cc2-bef6-d5a7cdc5d96b)

Then, if sensor D detects a wall less than 80cm away, it will do one of two actions; If sensor F detects a distance greater than 100cm and sensor C detects a distance less than 60cm, motor B will adjust its speed to 52% and adjust to the 60° position for 0.7 seconds, then adjust its speed again. but at 20% and it will be reset to the 0° position.

![image](https://github.com/auric123/95octano/assets/171710232/b4350931-f8c4-4669-8e4c-0b478e1297c0)

But, if sensor C detects a distance greater than 100cm and sensor F detects a distance less than 60cm, motor B will adjust its speed to 52% and adjust to the 290° position for 0.7 seconds, then adjust its speed again. speed to 20% and will reset to the 0° position.
Outside of the sensor D function, we put the function of starting engine A into the stopwatch loop.
And finally, when the time of 33.2 seconds on the stopwatch expires, we set the function to stop the motor and thus the robot would conclude with its laps.

Journal entry
•Chronology: 

Thursday, March 14-28: In this period was the creation of the sketch of what the robot would be like and research on our category.

Thursday and Tuesday 2-25 April:
This month we executed the construction of the robot assembling it in different ways, applying the ultrasonic sensor to the hub, we managed to make the robot rotate well.

Thursday and Tuesday May 7-28: In this period of time we focus on the structure changing the tires and reinforcing its skeleton so that it is strong against vibrations and does not fall apart, We create functional base programs and then work them more deeply.

Thursday and Tuesday 18-27 June: Here we finished assembling the robot and focused on programming getting a functional programming for both rounds, we did tests and everything worked as it should. 

Tuesday and Thursday, July 2:

• challenge and solution: the biggest challenge we had was to get a solid structure for the robot, without exceeding the size stipulated in the regulations. When we got the solid structure after several repairs, we found another (structural) problem which was that the front wheels, which are responsible for spinning the robot, tended to fall off the structure most of the time, causing the robot to not steer or walk properly so we had to replace the spike wheels with other lego wheels.


Conclusion 

Information: brain hub, battery connects 

¿What motivated us to make the vehicle?
We are motivated in Tesla vehicles by their autonomy on the track.

• mobility: at the beginning we were obviously inspired by the common car system, but when we saw that it consumed space, which is very important for us, we started looking for a different system. We came up with the idea of doing it with gears which convinced us because the system weighed less than the others and consumed less space.

• power: we decided to use two motors as this would make it easier to carry the weight of the robot, using two motors for better mobility, balance and speed of our robot we use a bar for better precision in the mobility of our vehicle.

 • sensors: with the help of the proximity sensor we measure the distance in which indie must rotate, also relying on the color sensors if it is red it will rotate to the right, if it is green it will rotate to the left.

• Steering Speed Control:
The motors together with the programming was the key to having a speed that will first accept the programming and the motors that are two motors that depend on whether they go to the left or to the right.


Parts List:

![image](https://github.com/auric123/95octano/assets/171710232/35c536c6-cd9e-4ae3-b061-e0b75a1359d5)
![image](https://github.com/auric123/95octano/assets/171710232/78dbfd95-8da3-4cb1-a044-5a10c20cf7fa)
![image](https://github.com/auric123/95octano/assets/171710232/a6206f33-47bc-41da-a8c5-2e10e75ad1e2)
![image](https://github.com/auric123/95octano/assets/171710232/2cef7d31-6d1d-4904-abd2-a8fa9c8be0f3)
![image](https://github.com/auric123/95octano/assets/171710232/f7a2cafd-2646-48c6-a498-effc2395be58)
![image](https://github.com/auric123/95octano/assets/171710232/62402e8b-e369-4114-850d-54f6a8b528e8)
![image](https://github.com/auric123/95octano/assets/171710232/385bbbe4-98de-4d86-8b17-b21b98dc1a8f)
![image](https://github.com/auric123/95octano/assets/171710232/c30c98e6-fbff-4ef2-8d74-ba0325fa4d45)
![image](https://github.com/auric123/95octano/assets/171710232/b05abe8c-c242-4491-b14c-73edf8e42d17)
![image](https://github.com/auric123/95octano/assets/171710232/dd39e60b-687e-4a42-8429-ed7c03311dab)
![image](https://github.com/auric123/95octano/assets/171710232/63d6cf63-f463-4550-8ed3-31e8962932f8)
![image](https://github.com/auric123/95octano/assets/171710232/992b553f-8cf2-459c-bac1-39dda907fd50)
![image](https://github.com/auric123/95octano/assets/171710232/e7ce1420-ba5c-40bf-8458-0c3b53aa7450)
![image](https://github.com/auric123/95octano/assets/171710232/a7af1c55-96d9-4f12-93aa-46e36ef7b4d9)
![image](https://github.com/auric123/95octano/assets/171710232/0f46b163-79a4-464a-bf14-0751072ea842)
![image](https://github.com/auric123/95octano/assets/171710232/1ee8636b-3545-41d9-b13a-e4f876e4bd90)
![image](https://github.com/auric123/95octano/assets/171710232/95a59277-932c-4112-a107-46fc9ceae021)
![image](https://github.com/auric123/95octano/assets/171710232/f8d254ac-4711-4224-b18c-38f582c39879)
![image](https://github.com/auric123/95octano/assets/171710232/b81bf4f5-2902-4c5d-8881-b6f4139750d2)
![image](https://github.com/auric123/95octano/assets/171710232/962ae40d-8b09-42b1-ae6d-9dde0d0b25c6)
![image](https://github.com/auric123/95octano/assets/171710232/e99c8f3f-4785-41dc-95d3-6ac1a69464ab)
![image](https://github.com/auric123/95octano/assets/171710232/7e371c02-2839-4e8f-ac34-a13e4d5d5344)
![image](https://github.com/auric123/95octano/assets/171710232/aa0fa25f-dce5-49a6-ad5e-846acad7980e)
![image](https://github.com/auric123/95octano/assets/171710232/a07ff345-2b1a-4716-8384-ef7341d1c4d5)
![image](https://github.com/auric123/95octano/assets/171710232/db95968d-4936-4dce-b951-0aba337108e8)
![image](https://github.com/auric123/95octano/assets/171710232/c0f8c2dd-5ba0-46da-8d08-85ebafc04b60)
![image](https://github.com/auric123/95octano/assets/171710232/f05a15ce-fd5a-45be-b2fb-96a15f5ae6be)
![image](https://github.com/auric123/95octano/assets/171710232/53d97875-d9c3-4948-a0a6-6e011ca0b170)








