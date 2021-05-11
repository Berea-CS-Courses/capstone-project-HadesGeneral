# Components Unit Testing
  
  Here I will be braking down the Robotic Skateboard down into different components. Testing each to find their individual limits, ideal usability, and any problems/bugs that arise through this.

 ----------------------------------------------------------------------------  
   
   #### Linear Acruator
   
   Purpose: To turn the device by utilizing weight to lean the skateboard one side to the other. 
   
   **Findings -**
   
   - Here I show off the actuator moving with 2.5 lbs. This is what I have been using with the system so far. This is becasue I think this is the ideal weight that isn't to heavy to break the actuator, but heavy enough to make the skateboard turn. 
   
   [![2.5 lb Linear Actuator](https://img.youtube.com/vi/gh21PnaThnI/0.jpg)](https://youtu.be/gh21PnaThnI)
   
   - Here I show off the actuator moving with 5 lbs. This is video shows that the Lineat Actuator starts to slow down with more weight. This is becasue of the NXT motor not having enough power to move such a weight fast enough.

   [![5 lb Linear Actuator](https://img.youtube.com/vi/rEQufCh28vo/0.jpg)](https://youtu.be/rEQufCh28vo)
   
   - Here I show off the actuator moving with 7.5 lbs. This is video shows that the Lineat Actuator starts to slow down and basically stops with the current weight. This is becasue of the NXT motor not having enough power to move such a weight.

   [![7.5 lb Linear Actuator](https://img.youtube.com/vi/GQlalKLsaHY/0.jpg)](https://youtu.be/GQlalKLsaHY)
   
   **Found Bugs/mechanical defects:** The worm gears that the platform is uses to move from one side to the other are not made to perfectly fit together, and so there is minor friction created from this. Making the whole system work harder to get the speed needed.
         
 ----------------------------------------------------------------------------   
   #### NXT App
   Purpose: To control the different motors and sensors of the overall system. 
   
   **Limits:** The bluetooth has a limit of ADD DISTANT HERE
   
   **Found Bugs/mechanical defects:**  When pressing a button or sending an input from the app to the NXT at the same time the Button Sensor is being activated, it will break the button sensor code. The button sesnor code will cease to work from there on, but the NXT app will work still.
   
 ----------------------------------------------------------------------------          
   #### Wheels
   Purpose: To move the system forward normally. When the button sensor is activated the wheels then transprt the Robitic Skateboard backwards to get way from what it hit infront of it.
   
   **Findings -**
   
   - Here I show off the wheel system moving with 2.5 lbs. This is the ideal amount since it moves easily with minimal problems. This is also the ideal amount that is needed to make the Skatebaord lean to the side that weight is on. 

[![2.5 lb Wheels](https://img.youtube.com/vi/koPFEo0PfT0/0.jpg)](https://youtu.be/koPFEo0PfT0)

   - Here I show off the wheel system moving with 5 lbs. In this video you can see that system works very similar to when 2.5 lbs were on it. But, it is has ever so slightly slowed down. This is because of how much power the two wheel motors can output.

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
   Purpose: To stop all motors and back the system up, moving it away from what it had bumped into. 
   
   Findings:
   
  **Found Bugs/mechanical defects:** When pressing a button or sending an input from the app to the NXT at the same time the Button Sensor is being activated, it will break the button sensor code. The button sesnor code will cease to work from there on, but the NXT app will work still.
           
 ----------------------------------------------------------------------------
  
  ## Vertical End-to-End Testing 
    
   ### Test Enviroment
   
   I will test how the Robotic Skateboard works all together. I will achieve this by seeing where the limits of turning capability of the system is and the max distance it can travel. In the image below will be the layout of the test enviorement. There will be two cones to indicate the starting place for the Skateboard. The second one will be the ending of bluetooth connection if the Skateboard went straight. The third cone will be placed where the system lands when turning at its tightest capability to the left or right and meets the end point of the bluetooth connection distance. This will be shown with the ideal 2.5 lbs and 5 lbs being used. 
   
   ### Setup
   
   - Have two cones ADD BLUETOOTH MAX DISTANCE HERE feet apart from each other. That is the the max amount of feet before the Bluetooth cuts out and doesn't work anymore.
   - Camera recording behind the test enviuroment to capture this all.
   - Tape measure to get distances.
   - Third cone to find max turning capability.

# Documentation

Here will be where changes directly done to the build of the Robitc Skateboard system I have created so far shown off in Deliverable 4.5.
