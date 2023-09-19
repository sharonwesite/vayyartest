Hi Sharon,

Following our phone conversation, sending you an exercise as we discussed.
Vayyar's tracking sensor is installed on the wall in the room. 
 

The above figure is an example of arena dimensions when the sensor is installed on the wall.

X=0, Y=0, Z=0 is the point on the floor below the sensor 
Attached is the tracker_log.log file containing the tracker information of a person in a room 

t_id=0 [ID of the tracked target] 

x=+0.7 [Location on the X-axis, in units of [m]] 

y=+0.6 [Location on the Y-axis, in units of [m]] 

z=+0.8 [Location on the Z-axis, in units of [m]] 

FPS=10.14 [Frame rate – can be assumed as 10 frames/second] 

The data is provided for every frame => every 0.1 second. 

 

To do:

There is a chair located in x[-0.5, 0] y[1.8, 2.4] (0.5m width on the X-axis and 0.6m length on Y-axis) 

Please write a code that calculates the time that a person was at the chair area based on the attached log.


Thanks,
Igal

$$$$$$$$$$$$$^^^^^^^^^###########@@@@@@@@@@@@@@@@@@


I created a Flask project Download the zip file of the project and open it in IDE.
The project has an app.py file that needs to be run and then we will get the address of a local server
When we open the server in the browser, we will be ready to upload the log file and by clucking the button 
the code will run on the log file and tell us how many seconds the man was next to the chair
We will of course get the answer in the result.html file automatically.






