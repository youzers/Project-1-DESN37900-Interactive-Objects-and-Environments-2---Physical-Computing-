# Project 1
*DESN 37900 Interactive Objects and Environments 2: Physical Computing*

*Modified by Jimin Chung, Adriana Rodriguez, Isabella Sulle*

The ultrasonic rangefinder takes the distance and motion tracked, and rotates the servo's based on how if it's in a specific zone. Attached to the servos are two wooden pegs in which one is attached to ribbon. The servo's are definined and measured within time and distance, in how long to unwrap the ribbon and how long to wrap it back up. 

```
//clockwise
void clockw() 
{
servo.write(0);
servo2.write(180); 
}

//counter clock-wise
void counterw() {
servo.write (180);
servo2.write (0);  
}
```
