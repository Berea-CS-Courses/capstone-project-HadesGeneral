# Components Unit Testing
  
  Here I will be breaking down the Robotic Skateboard down into different components. Testing each to find their individual limits, ideal usability, and any problems/bugs that arise through this.

 ----------------------------------------------------------------------------  
   
   #### Linear Actuator
   
   **Purpose:** To turn the device by utilizing weight to lean the skateboard one side to the other. 
   
   **Findings -**
   
   - Here I show off the actuator moving with 2.5 lbs. This is what I have been using with the system so far. This is because I think this is the ideal weight that isn't too heavy to break the actuator, but heavy enough to make the skateboard turn. 
   
   [![2.5 lb Linear Actuator](https://img.youtube.com/vi/gh21PnaThnI/0.jpg)](https://youtu.be/gh21PnaThnI)
   
   - Here I show off the actuator moving with 5 lbs. This is video shows that the Linear Actuator starts to slow down with more weight. This is because of the NXT motor not having enough power to move such a weight fast enough.

   [![5 lb Linear Actuator](https://img.youtube.com/vi/rEQufCh28vo/0.jpg)](https://youtu.be/rEQufCh28vo)
   
   - Here I show off the actuator moving with 7.5 lbs. This is video shows that the Linear Actuator starts to slow down and basically stops with the current weight. This is because of the NXT motor not having enough power to move such a weight.

   [![7.5 lb Linear Actuator](https://img.youtube.com/vi/GQlalKLsaHY/0.jpg)](https://youtu.be/GQlalKLsaHY)
   
   **Found Bugs/mechanical defects: ** The worm gears that the platform is uses to move from one side to the other are not made to perfectly fit together, and so there is minor friction created from this. Making the whole system work harder to get the speed needed.
         
 ----------------------------------------------------------------------------   
   #### NXT App
   
   **Purpose:** To control the different motors and sensors of the overall system. 
   
   **Findings:** The Bluetooth has a rough limit of 44.6 yards. This is because the white lines are 5 inches, the spaces between are 102 inches, and there are 15 of each. All of this added together equals out to roughly 1605 inches, or 133.75 feet which equals 44.6 yards rounded to the nearest decimal place. This makes sense since if you add in me knowing my phones Bluetooth starts to cut out at about 10 yards and the NXT mindstorm has a range of 33 yards, making 43 yards being just under where the test starts to get bad connections. The NXT [User Manual](https://www.generationrobots.com/media/Lego-Mindstorms-NXT-Education-Kit.pdf) says the range on page 42.
   
   - Below is the video of me testing to try to find the distance where the NXT app and the NXT bluetooth disconnect from each other. I did not find the exact distance, but I did find that it can reach a considerable distance before having connection issues. It seems to slow down, or not react as fast to my inputs at the longer distances.
   
   [![Distance Test](https://img.youtube.com/vi/O6z0qYRDyVc/0.jpg)](https://youtu.be/O6z0qYRDyVc)
   
   **Found Bugs/mechanical defects:**  When pressing a button or sending an input from the app to the NXT at the same time the Button Sensor is being activated, it will break the button sensor code. The button sensor code will cease to work from there on, but the NXT app will work still.
   
 ----------------------------------------------------------------------------          
   #### Wheels
   
   **Purpose:** To move the system forward normally. When the button sensor is activated, the wheels then transport the Robotic Skateboard backwards to get way from what it hit in front of it.
   
   **Findings -** Smooth concrete and asphalt seem to be the best surfaces for the wheels to get the most traction for less power. The system can handle 17.5 lbs and still move, but anything more and it will not have enough power to move. 
   
   - Here I show off the wheel system moving with 2.5 lbs. This is the ideal amount since it moves easily with minimal problems. This is also the ideal amount that is needed to make the Skateboard lean to the side that weight is on. 

[![2.5 lb Wheels](https://img.youtube.com/vi/koPFEo0PfT0/0.jpg)](https://youtu.be/koPFEo0PfT0)

   - Here I show off the wheel system moving with 5 lbs. In this video you can see that system works very similar to when 2.5 lbs were on it. But it is has ever so slightly slowed down. This is because of how much power the two-wheel motors can output.

[![5 lb Wheels](https://img.youtube.com/vi/HSez85GzGCU/0.jpg)](https://youtu.be/HSez85GzGCU)

  - Here I show off the wheel system moving with 10 lbs. In this video you can see that system starts to slow down a lot more. 

[![10 lb Wheels](https://img.youtube.com/vi/_Bh3O8xH8Ak/0.jpg)](https://youtu.be/_Bh3O8xH8Ak)

   - Here I show off the wheel system moving with 15 lbs. In this video you can see that system slows down a lot.
  
[![15 lb Wheels](https://img.youtube.com/vi/sFppsuWv2bI/0.jpg)](https://youtu.be/sFppsuWv2bI)

   - Here I show off the wheel system moving with 17.5 lbs. In this video you can see that system works very similar to when 15 lbs. It is moving very slowly, almost to a crawl. 

[![17.5 lb Wheels](https://img.youtube.com/vi/WfyRhPaAnao/0.jpg)](https://youtu.be/WfyRhPaAnao)   

   **Found Bugs/mechanical defects:** Anything over 17.5 lbs will make the wheel system not work and not move the skateboard. 
     
 ----------------------------------------------------------------------------          
   #### Button Sensor
   
   **Purpose:** To stop all motors and back the system up, moving it away from what it had bumped into. 
   
   - Here is a video showing off the button on the Robotic Skateboard. It shows off me using the NXT app to move the skateboard forward into a door. When it hits the door, it backs up. I do this a couple times to demenstrat the fucntion. The last time you see it run into the door, I actually manually back it up using the app. The stutters in the video is me inching forward to activate the program, but trying not to trigger the bug.

[![Button Sensor Test](https://img.youtube.com/vi/71WgdFV5uuM/0.jpg)](https://youtu.be/71WgdFV5uuM)

   
  **Found Bugs/mechanical defects:** When pressing a button or sending an input from the app to the NXT at the same time the Button Sensor is being activated, it will break the button sensor code. The button sensor code will cease to work from there on, but the NXT app will work still.
           
 ----------------------------------------------------------------------------
  
  ## Vertical End-to-End Testing 
  
   ### Surface Tests
   
   I will be testing the Robotic Skateboard moving over multiple surfaces.  Specifically looking at smooth concrete, asphalt, grass, and gravel.
   
   - This video has Smooth sidewalk concrete, asphalt, and grass. There does not seem to be too much noticeable difference in speed and traction when going from the concrete to asphalt. The wheels/overall system could not go over and into the grass. I believe this is because of the sharp uneven surface compared to the concrete and asphalt. They are relatively level, whereas the grass is definitely not. I also think the Lego wheels and the skateboard wheels do not have the traction to get through the grass. The motors as well might not have the power to do it to.
   
   [![Multiple Surfaces Test](https://img.youtube.com/vi/05nogra6AQk/0.jpg)](https://youtu.be/05nogra6AQk)
    
   ### Turn Test
   
   I will achieve this by seeing where the limits of turning capability of the system is and the max distance it can travel. In the image below will be the layout of the test environment. There will be two cones to indicate the starting place for the Skateboard. The second one will be the ending of bluetooth connection if the Skateboard went straight. The third cone will be placed where the system lands when turning at its tightest capability to the left or right and meets the end point of the bluetooth connection distance. This will be shown with the ideal 2.5 lbs and 5 lbs being used. 
   
   ### Setup
   
   - Have two cones ADD BLUETOOTH MAX DISTANCE HERE feet apart from each other. That is the max amount of feet before the Bluetooth cuts out and doesn't work anymore.
   - Camera recording behind the test environment to capture this all.
   - Tape measure to get distances.
   - Third cone to find max turning capability.

# Documentation

Here will be where changes directly done to the build of the Robotic Skateboard system I have created so far shown off in Deliverable 4.5.
