========================================================================================================================================================================================

Grupo: Equipo Galaxy.

Integrantes: Raquel Lorenzo, Auric Arango, Jorge Dixon.

Colegio: Colegio Bilingue Eben Ezer.

[![Picsart-24-08-09-06-57-58-790.png](https://i.postimg.cc/YCHpQPJg/Picsart-24-08-09-06-57-58-790.png)](https://postimg.cc/TptM6t2Y)

   Introducción

Nuestro robot (95 Octanos) se basó según las reglas de wro y según nuestros conocimientos del tema de robótica incluimos varios elementos que veremos a continuación.

   • Proceso de diseño: El proceso de diseño de "95 Octanos" fue un poco riguroso, porque tuvimos que implementar una mecánica compacta, y todas las ideas que teníamos en mente eran funcionales. En el diseño base el robot estaba muy flojo y poco resistente vibraba mucho y necesitábamos más refuerzo en las ruedas y menos de 95 octanos para corregir esto cambiamos las ruedas lisas que eran más pequeñas por más terreno y grandes junto con eso reforzando las partes laterales. girar correctamente y gracias al trabajo entre nosotros y un mar de ideas pudimos concluir con el proyecto.

   Mecánica:

   • La dirección se dirige basándose en la programación de Spike para un rendimiento optimizado, en la parte inferior tenemos.

   • Conducir: conduces a través del centro que te da las indicaciones dependiendo de la situación en la que se encuentre en el momento de conducir.

   • Diseño de Chasis: Nuestro robot tiene un chasis cuadrado que intenta simular un coche convencional.


Electrónica:

   • Sensores: El sensor de proximidad se utiliza para medir qué tan lejos está un objeto o la pared en centímetros, el sensor de colores que son dos el primero detecta el color rojo que gira a la derecha, detecta el color verde y gira a la izquierda y el sensor de orientación (hub ) que es el cerebro y conecta los cables de los motores al hub que con programación hace que el auto se mueva.

   • Control de Velocidad/Dirección: Su control de velocidad es gracias al HUB y motores de púas grandes que pueden alcanzar una velocidad de 0 RPM a 200 RPM y su dirección se maneja gracias a un mecanismo similar al control de los automóviles.

   • Diagrama de cableado:

![DIAGRAMA ELECTRICO 95 OCTANO](https://github.com/user-attachments/assets/a81490e1-d94e-469a-ab45-58298e1ba7ea)


   Programación

   • Diagrama de flujo:

![FUTUROS_ING_GC DIAGRAMA DE FLUJO](https://github.com/user-attachments/assets/283682d8-7bf6-45a3-9a61-83f451e393ae)


   Estrategias: Como estrategia principal teníamos que ver cómo se movían los sensores junto con el motor y que éste pudiera ser autónomo y específico en los colores al lado del sensor de color.

   • Discusión del código:

![image](https://github.com/user-attachments/assets/7713af4d-43a5-401a-8839-2326f6eb7def)


Esta programación la utilizamos tanto para la ronda 1 como en la ronda de obstáculos, básicamente colocamos que al iniciar el programa lo primero que realice el Hub es reiniciar el cronómetro para que comience en 0. La velocidad del motor "A" la ajustamos en 100% y la posición del motor "B" en los 0° grados. El robot realizará las siguientes acciones en un tiempo de 21.5 segundos en forma de repeticiones.

![image](https://github.com/user-attachments/assets/9bd2fdf9-d771-4cff-b9e8-e76be923354e)



Ahora, si el sensor E es menor de 80cm, entra en la siguiente condicion en donde di el sensor C está a más de 150cm y el sensor F está a menos de 90cm, lo que realizara el robot a continuación es reducir su velocidad del motor "B" a 70% y posicionar el giro del motor "B" en 300° grados con un tiempo de espera de 0,4 segundos. Al pasar la condicion volverá a ajustar su posicion incial para asi ir en linea recta.

![image](https://github.com/user-attachments/assets/7cb41402-22f9-4503-97f1-505f847b46cf)


Pero, si se reíte la condicion inicial con el sensor E y en esta ocacion el sensor F es quien detecta más de 150Cm de distancia y el sensor C detecta menos de 90cm, el robot realizará lo mismo, solo que girará al lado contrario del caso anterior, y  reducir su velocidad del motor "B" a 70% y posicionar el giro del motor "B" en 46° con un tiempo de espera de 0,4 segundos, luego volverá a reacomodarse el motor "B" en 0° grados. 

![image](https://github.com/user-attachments/assets/f64c3a58-32ef-460e-87a5-cc74ce1b4d5f)


Por último, el robot realizará estas acciones en bucle manteniendo encendido el motor "A" y acomodando el motor"B" en la posicion 0° para asi seguir en linea recta. Y al terminar el tiempo estipulado, se detendrán los motores y el Hub saldra de la programación.

![image](https://github.com/user-attachments/assets/858f51d3-777a-49b8-9a41-8442d9aeeb5c)


   Entrada de diario

   • Cronología:

Jueves 14 al 28 de marzo: En este período se realizó la creación del boceto de cómo sería el robot y la investigación sobre nuestra categoría.

Jueves y martes 2 al 25 de abril: Este mes ejecutamos la construcción del robot ensamblándolo de diferentes maneras, aplicando el sensor ultrasónico al hub, logramos que el robot girara bien.

Jueves y martes 7 al 28 de mayo: En este periodo de tiempo nos enfocamos en la estructura cambiando los neumáticos y reforzando su esqueleto para que sea fuerte contra las vibraciones y no se deshaga, creamos programas base funcionales para luego trabajarlos más profundamente.

Jueves y martes 18-27 de junio: Aquí terminamos de ensamblar el robot y nos enfocamos en programar obteniendo una programación funcional para ambas rondas, hicimos pruebas y todo funcionó como debía.

Martes y jueves 2 de julio: Terminamos de probar las programaciones y conseguimos completar la primera ronda con éxito; logramos crear una buena programación para la segunda ronda siendo funcional.

   • Reto y solución: el mayor desafío que tuvimos fue conseguir una estructura sólida para el robot, sin exceder el tamaño estipulado en la normativa. Cuando conseguimos la estructura sólida después de varias reparaciones, encontramos otro problema (estructural) que era que las ruedas delanteras, que son responsables de hacer girar el robot, tendían a caerse de la estructura la mayor parte del tiempo, provocando que el robot no girara ni caminaba correctamente, así que tuvimos que reemplazar las ruedas con púas por otras ruedas de Lego.


   Conclusión 

Información: Brain Hub, la batería se conecta.

¿Qué nos motivó a fabricar el vehículo? En los vehículos Tesla nos motiva su autonomía en pista.

   • Movilidad: Basandonos en la dimensión de la pista el robot realiza la una movilidad en linea recta combinada con giros controlados por tiempos de espera en la programacion.

   • Potencia: decidimos usar dos motores uno para la aceleración del robot a 100% y a su ves controlar el peso , y otro motor grande para los giros, para una mejor movilidad, equilibrio y velocidad de nuestro robot también barra para una mejor precisión en la movilidad de nuestro robot.

   • Sensores: utilizamos sensores de ultrasonido que envian ondas a la pared y las recibe, para evitar que las 2 laterales hagan este procedimiento siempre, tenemos una delantera que les comunica a las otras cuando empezar a medir, ejecutar las acciones , apoyándonos también en los sensores de color este tiene que tocar el bloque para que la luz reciba los reflejos de colores, por ejemplo el rojo, para que vaya a la derecha y verde izquierda.

   • Control de Velocidad de Dirección: Los motores junto con la programación fue la clave para tener una velocidad que primero acepte la programación y los motores que son dos motores que dependen si van hacia la izquierda o hacia la derecha.

   Lista de partes:

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
![image](https://github.com/auric123/95octano/assets/171710232/c0f8c2dd-5ba0-46da-8d08-85ebafc04b60)
![image](https://github.com/auric123/95octano/assets/171710232/f05a15ce-fd5a-45be-b2fb-96a15f5ae6be)
![image](https://github.com/auric123/95octano/assets/171710232/53d97875-d9c3-4948-a0a6-6e011ca0b170)
![image](https://github.com/user-attachments/assets/3ae3643d-cfdc-4e9a-bd0e-40bdce629090)
![image](https://github.com/user-attachments/assets/5ff85ad1-c3b9-4787-b2fd-36eda6186ed0)
![image](https://github.com/user-attachments/assets/7f721cb2-f245-48f4-984b-cf5e10b98710)
![image](https://github.com/user-attachments/assets/a1114258-d307-4339-ae9f-e1edd8051c9d)
![image](https://github.com/user-attachments/assets/2fb3d5bf-284c-4646-a1b8-a13be58e107c)
![image](https://github.com/user-attachments/assets/1dbd7c5a-2108-4cd1-8b78-9549cc81538f)
![image](https://github.com/user-attachments/assets/32e256c0-80a2-4515-bdf9-e68079f1f0a0)








========================================================================================================================================================================================                                                                      
proyect 95octano

Group: Galaxy Crew.

Members: Raquel Lorenzo, Auric Arango, Jorge Dixon.

School: Colegio Bilingue Eben Ezer.

[![Picsart-24-08-09-07-57-34-537.png](https://i.postimg.cc/B6TzzDSs/Picsart-24-08-09-07-57-34-537.png)](https://postimg.cc/473w7YHF)

   Introduction

Our robot was based according to the rules of wro and according to our knowledge of the subject of robotics we included several elements that we will see below. 

   • Design process: The process of designing our robot(95octane) was a bit rigorous, because we had to implementa compact mechanics, and all the ideas that we had in mind were functional. In the base design the robot was very loose and not very resistant vibrated a lot and we needed more reinforcement in the wheels and lower 95octane to correct this we changed the smooth wheels that were smaller for more ground and large together with that reinforcing the side parts to turn correctly and thanks to the work between us and a sea of ideas we were able to conclude with the project. 

   Mechanics: 

   • Steering is directed based on spike programming for optimized performance, at the bottom we have.

   • Driving: you drive through the hub which gives you the indications depending on the situation you are in at the time of your driving

   • Chassis Design: Our robot has a square chassis that tries to simulate a conventional car. 






   Electronics:

   • Sensors: Proximity sensor is used to measure how far away an object or the wall is to centimeters, sensor colors that are two the first to detect the red color that turns right, detects the green color and turns the left and Orientation sensor (hub) which is brain and connects the cables of the motors to the hub that with programming makes the car move.

   • Speed/Steering Control: Its speed control is thanks to the HUB and large spike motors that can reach a speed of 0 RPM to 200 RPM and its steering is handled thanks to a mechanism that is similar to the control of cars. 

   • Wiring Diagram:

![image](https://github.com/user-attachments/assets/fc9eb2c7-21c0-4416-8b09-048cb333bbb3)
 
   Programming
 
   •	Flowchart:

![image](https://github.com/auric123/95octano/assets/171710232/9a47f9ea-59b3-4bf8-8f43-ba88dcf4d076)


   •	Strategies: As a main strategy we had to see how the sensors moved together with the engine and that it could be autonomous and specific in the colors next to the color sensor.

   • Code discussion:

![image](https://github.com/user-attachments/assets/7a250926-4d16-4ac0-8bd6-9209aabbdc0f)

We use this programming both for round 1 and in the obstacle round, basically we place that when starting the program the first thing the Hub does is to restart the timer so that it starts at 0. The speed of the "A" engine is set to 60% and the position of the "B" engine to 0° degrees. The robot will perform the following actions in a time of 60 seconds in the form of repetitions.

![image](https://github.com/user-attachments/assets/22b5a355-0437-4ba1-b6de-1fca4c989270)

Now, if the C sensor is more than 100cm away and the F sensor is less than 75cm, what the robot will do next is to reduce its speed of the "A" motor to 40% and position the rotation of the "B" motor at 305° degrees for 0.6 seconds. As time goes by, it will adjust its speed again to 40% and the position of the "B" engine to 0° degrees.

![image](https://github.com/user-attachments/assets/3ed03b18-5244-4ea0-8bca-b4182441aab1)

But, if the F sensor is the one that detects more than 100 cm away and the C sensor detects less than 75 cm, the robot will do the same, only that it will turn to the opposite side of the previous case, positioning the "B" motor at 55° degrees and maintaining the speed of the "A" motor at 40% for 0.6 seconds, then the "B" motor will be rearranged again at 0° degrees. 

![image](https://github.com/user-attachments/assets/b95c3641-b0fa-4758-bcb5-d483953cc901)

Finally, the robot will perform these actions in a loop by keeping the "A" engine on. And at the end of the stipulated time, the engines will stop and the Hub will go out of the programming.


   Journal entry

   • Chronology: 

Thursday, March 14-28: In this period was the creation of the sketch of what the robot would be like and research on our category.

Thursday and Tuesday 2-25 April:
This month we executed the construction of the robot assembling it in different ways, applying the ultrasonic sensor to the hub, we managed to make the robot rotate well.

Thursday and Tuesday May 7-28: In this period of time we focus on the structure changing the tires and reinforcing its skeleton so that it is strong against vibrations and does not fall apart, We create functional base programs and then work them more deeply.

Thursday and Tuesday 18-27 June: Here we finished assembling the robot and focused on programming getting a functional programming for both rounds, we did tests and everything worked as it should. 

Tuesday and Thursday, July 2:

   • Challenge and solution: the biggest challenge we had was to get a solid structure for the robot, without exceeding the size stipulated in the regulations. When we got the solid structure after several repairs, we found another (structural) problem which was that the front wheels, which are responsible for spinning the robot, tended to fall off the structure most of the time, causing the robot to not steer or walk properly so we had to replace the spike wheels with other lego wheels.


   Conclusion 

Information: brain hub, battery connects 

¿What motivated us to make the vehicle?
We are motivated in Tesla vehicles by their autonomy on the track.

   • Mobility: Based on the dimension of the track, the robot performs straight-line mobility combined with turns controlled by waiting times in the programming.

   • Power: we decided to use two motors as this would make it easier to carry the weight of the robot, using two motors for better mobility, balance and speed of our robot we use a bar for better precision in the mobility of our vehicle.

   • Sensors: We use ultrasound sensors that send waves to the wall and receive them, to prevent the 2 lateral ones from always doing this procedure, we have a front one that tells the others when to start measuring, execute the actions, also relying on the color sensors This has to touch the block so that the light receives colored reflections, for example red, so that it goes to the right and green to the left.

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
![image](https://github.com/auric123/95octano/assets/171710232/c0f8c2dd-5ba0-46da-8d08-85ebafc04b60)
![image](https://github.com/auric123/95octano/assets/171710232/f05a15ce-fd5a-45be-b2fb-96a15f5ae6be)
![image](https://github.com/auric123/95octano/assets/171710232/53d97875-d9c3-4948-a0a6-6e011ca0b170)
![image](https://github.com/user-attachments/assets/a35eb5f7-ad84-4089-8751-19fc01d0fc83)
