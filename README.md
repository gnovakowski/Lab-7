Lab-7
=====

The robots that we utilize have a set of three infrared (IR) emitter and detector pairs on them and are used to bring in analog voltage values for the ADC. The code that I wrote in this lab is used to interpret these incoming voltages to determine whether the robot is approaching a wall in front or on one of its sides.

I wrote a total of four methods to be used with this lab functionality. 

- void initSensors()
  * This method enables the interrupt and sets the clock for the robot.

- unsigned int frontSensor()
  * This method contains the functionality required to enage the sensor at the front of the robot.

- unsigned int leftSensor()
  * This method contains the functionality required to enage the sensor on the left side of the robot.

- unsigned int rightSensor()
  * This method contains the functionality required to enage the sensor on the right side of the robot.

An example of how to properly use these methods can be seen in the file "example.c" in the Lab 7 repository.
