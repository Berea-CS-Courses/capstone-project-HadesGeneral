## Proof of Concept

 - The video below is showing off the robot being operated by the app with no weight. This is to show that the robot will go straight when asked. The reason it curves slightly is because the way the weights are attached to the rest of the robot is very flexible so that when it leans to one side that part won't break. because of this it also isn't rigid enough to not move in the littles ways. So, an uneven floor, which I have, and the wheels not being completely set straight can make it curve slightly. This can be fixed by making that part of the robot more rigid but allowing it to be flexible enough to not break when turning.

[![No Weight](https://img.youtube.com/vi/UOBMNFqDALw/0.jpg)](https://youtu.be/UOBMNFqDALw)

-  This video below is to demonstrate if the weight was shifted to the left side of skateboard. Thus, making the skateboard moving more to the left drastically.

[![Left Weight](https://img.youtube.com/vi/GlCJTLRf_IE/0.jpg)](https://youtu.be/GlCJTLRf_IE)

-  This video below is to demonstrate if the weight was shifted to the right side of skateboard. Thus, making the skateboard moving more to the right drastically.

[![Right Weight](https://img.youtube.com/vi/kiJmKlETUIo/0.jpg)](https://youtu.be/kiJmKlETUIo)

- This is the top of the robot.

![Top of the Robot](/Images/Top_Robot.jpg)

- This is the front of the robot.

![Front of the robot](/Images/Front_Robot.jpg)

- This is the back of the robot.

![Back of the robot](/Images/Back_Robot.jpg)

- This is the side of the robot.

![Side of the Robot](/Images/Side_Robot.jpg)

- This is the side of the motors/wheels.

![Side of Motors](/Images/Side_Motor.jpg)

- This is the top of the motors/wheels.

![Top of Motor](/Images/Top_motor.jpg)


## Concept Documentation

1. What external software or tools are needed to run your proof-of-concept? (e.g, general dependencies, build systems, or other frameworks.)

  - I am using the Lego NXT Mindstorm Brick as the brain of the entire project. It can be found [HERE](https://education.lego.com/en-us/products/lego-mindstorms-education-ev3-intelligent-brick/45500?gclid=CjwKCAjwjbCDBhAwEiwAiudBy8WWiBxQ1Vf-HBc45tcoCppfDY5ScUocorWwAFzRf5CkT-fhhYTahRoCNf4QAvD_BwE&ef_id=CjwKCAjwjbCDBhAwEiwAiudBy8WWiBxQ1Vf-HBc45tcoCppfDY5ScUocorWwAFzRf5CkT-fhhYTahRoCNf4QAvD_BwE:G:s&s_kwcid=AL!790!3!407201200497!!!g!295974719006!) on Lego's education side of their site.

  - This is the NXT Remote Control App. It can be found on the Google play store [HERE](https://play.google.com/store/apps/details?id=org.jfedor.nxtremotecontrol&hl=en_US&gl=US). The way it operates is that the three bars correspond to the three ports at the back of the NXT shown in the photo above. Touching above the middle of the bars makes the motors turn clockwise, and moving down from the middle turns them counter-clockwise. I would like the bars on the left and right side to control the respected wheel motor on the robot. The middle bar will control the weight shifting linear actuator. The entire robot will only move forward. To move forward you slide up from the middle of the bar on the left and right to make the motors move clockwise. Further from the middle of the bar determines the power output of the motors. The further away from the middle, the more power that is given. Sliding down from the middle makes the motors turn counter-clockwise. 

![App Control Scheme](/Images/Screenshot_20210318-132043.png)

  - This is the app when it asks what NXT you would like to connect to. To open the app, it asks to turn on your Bluetooth. once done it then gives this prompt. If within range of an NXT it will find it and you can tap on the one you want. NXTs can be named similar to how computers, phones, and other devices can named. Which will be used when trying to connect via Bluetooth or other connection type.

![App Bluetooth](/Images/Screenshot_20210324-195104.png)

2.What steps would need to be taken to run your proof-of-concept? (e.g, run the following command(s) or program(s): ____)

	 1. You need to download NXT Remote Control App from Google Play store.
	 2. Make sure the NXT you are using has two ports to connect two motors, but best it has three ports.
	 3. Get two NXT compatible motors, two connecting cords, and all the necessary Lego parts needed to build what I have so far.
	 4. Build robot how it is displayed. 
	 5. Connect NXT app and Robot.
	 6. Slide on the corresponding bars in the app to make move forward.

3.What is the current functionality of the proof of concept as you have submitted it? (e.g, this prototype displays a ____ that allows a user to ____)

 - I currently can be controlled through the NXT app via Bluetooth. It can move forward and move to the right and left when the weight is on the respected side of the platform above the robot. It can only turn via this method. 

4.Are there any components of the code or systems you have submitted that you did not create? If so, document them here alongside their source or reference. (e.g, code blocks you might have found on StackOverflow. Code dependencies do not need to be listed here, such as Qt3.)

 - The NXT Remote Control App. It can be found on the Google play store [HERE](https://play.google.com/store/apps/details?id=org.jfedor.nxtremotecontrol&hl=en_US&gl=US). The author is Jacek Fedorynski.

## Updates

- D1 - Updated Concept, Requirements, Software, and overall cleaned up the document
- D2 - Updated Small Components, Prioritization, and overall cleaned up the document
- D3 - Added an Entity Relationship Diagram, updated Reflection, and overall cleaned up the document
- Photos - Added photos of the Robot to the photos folder

## Reflection

- How confident do you feel about your project now that you have created a working proof-of-concept?

	- I feel pretty confident in making it more sturdy and making the turning being controlled by the app instead of by manually setting the weight on it.

- Have you faced any significant challenges in the creation of your project so far? If so, what are they?

	- The main challenge was acquiring the parts needed to build the robot. This was due to my project being more physical and the parts either needed to be ordered or supplied by the Computer Science department. 
	- The other challenge I had was building the robot overall. The Legos I am using are Lego technic, which are a type of Lego that are not the same as regular building Legos. So, familiarizing with how they work together was needed to make all this work.

- What do you need from instructors and teaching assistants to better help you implement, understand, or otherwise think about your project?
	- At this time, I am not sure of anything specific I need help with.


# Testing

## Longbaord Test

  - In this video I am showing off that the system I have currently created has the power to move a board that is heavier than the prehvious one. This baord weights roughly 8.8 lb. This is a little over two and half times the weight of the 3.5 lb baord. This is promising and lets me know the system and move with more weight with minor difficulty.

[![Longboard Test](https://img.youtube.com/vi/PxLmkoWhS8k/0.jpg)](https://youtu.be/PxLmkoWhS8k)

## Gear System

  - Here I am showing off  the gear setup that could help move the weight faster. The wheel is on the middle axle because this allows o nthe lthe first two gears (large gear on the left, and small gear right in front of it) to manipulate it. The other two (the right larger gear and small one in front of it) don't do anything currently. The piece of tape is there to show the speed of the wheel while turning it.

[![Gear System - Two Gear](https://img.youtube.com/vi/gz6hHgDXq0U/0.jpg)](https://youtu.be/gz6hHgDXq0U)

  - Here is the sname gear system but the wheel is on the back axle so that all the gears are manipulating it. This is to show that becaus of this gear system, with less roation of the initial axle, the wheel turns faster than in the prehvious video above. This will allow me to see if a two or a four gear system is needed to move the weight to the speed I need. 

[![Gear System - Four Gear](https://img.youtube.com/vi/2eLd3TePotY/0.jpg)](https://youtu.be/2eLd3TePotY)


## Updated Wheel/Axel Support

  - Here I am showing off the new support for the wheels and axles. This fixes the issue of the wheels being too flexable and interfering with how straight it can go. This also makes the connection to the rest of the stystem stronger, allowing the wheels have less of a problem pulling everything.

![Wheel Support Front](/Images/wheel_support_front.jpg)

![Wheel Support Front](/Images/wheel_support_side.jpg)


## Prototype Linear Actuator

  - Here I am showing off the prototype linear actor with side walls. The walls are there to help support the weight needed for the system. This is needed since  the length of the axle makes it more easier to bend than the shorter ones. Below is pictures of the setup.

![Top of Linear Actuator](/Images/top_lear_actuator.jpg)

![Side_Linear_Actuator](/Images/side_linear_actuator.jpg)


  - This video shows off the system working without the weight

[![Prototype Linear Actuator - No Weight](https://img.youtube.com/vi/0X-RVBH9JJw/0.jpg)](https://youtu.be/0X-RVBH9JJw)

  - This video shows of the system with the weight

[![Prototype Linear Actuator - No Weight](https://img.youtube.com/vi/yudEdZfCi_M/0.jpg)](https://youtu.be/yudEdZfCi_M)
