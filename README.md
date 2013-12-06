Lab-7
=====

The robots that we utilize have a set of three infrared (IR) emitter and detector pairs on them and are used to bring in analog voltage values for the ADC. The code that I wrote in this lab is used to interpret these incoming voltages to determine whether the robot is approaching a wall in front or on one of its sides.

I wrote a total of four methods to be used with this lab functionality. An example of how to properly use these methods can be seen in the file "example.c" in the Lab 7 repository.

- void initSensors()
  This method enables the interrupt and sets the clock for the robot

- unsigned int frontSensor()

- unsigned int leftSensor()

- unsigned int rightSensor()
