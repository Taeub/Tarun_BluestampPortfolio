# 3 Joint Robotic Arm With Claw
The 3 Joint Robotic Arm is a fun device that is controlled using a controller and can move 360 degrees! The claw on the robot is even capable of carrying small objects.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Tarun S | Irvington High School | Electrical Engineering/ Mechanical Engineering | Incoming Junior

![Headstone Image]
  
# Final Milestone

# Second Milestone
My second milestone was the assembly of my controller and getting output from it. The controller itself is literally just an acrylic piece, and there are 2 joystick modules screwed into it. The joystick modules have a potentiometer and depending on the direction you move the joystick the module produces an output from 0V to 5V or anywhere in between and the arduino converts the voltage into a numerical value on the serial monitor. With this milestone I had trouble importing libraries for my code to work, and I needed a library because libraries make things easier in the sense where I don't have to recode some code that someone has already written. I realized that in every library there is a needed source folder to narrow the arduinos search for files, so i added a source folder and everything worked. Next I plan to combine my first milestone which was fully assembling the robot and ensuring that all the components work, and my second milestone which was getting output from my controller to create a fully functioning arm, and after that I plan to make some modifications to the project to make it more smooth and more efficient. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/scAhvEodq6w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
My first milestone was the assembly of my intensive project, the 3 Joint Robot Arm. I completed the assembly of the arm and for the arm I first started by building the base which holds down the battery, the arduino with its nano shield, and the motor which moves the base of the arm. There are 4 motors in total controlling the movement of the arm. The base motor controls the direction that the arm is in. 2 motors control 2 different hinges while there is another motor that controls the claw. The claw is only attached to one finger of the claw but the other is also in motion as a result of the gear that connects the two fingers. I also took time to cable manage the motor wires so that it would not hinder the movement of the robot. Finally I wrote some code to reset the robot to its original position whenever the arduino is on so when i change the direction of the motors and turn on the arduino, the arm will return to 90 degrees. I had trouble screwing down the base of the arm to the motor which hindered the motors ability to move the robot. The screw was too short, and I then found a longer screw to screw down the base to the motor. Next I plan to assemble, connect, and test the controller. I plan to write code to recieve and print the output of the joystick module. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/uOCtF2aWj2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Starter Project
My starter project is the Useless box, a prank box that provides hours of entertainment! The box itself is activated when the switch at the top is flipped, and then the acrylic arm attached the a motor is propelled up and the arm flips a hinge up and hits the switch again to turn it off. After the switch is hit by the arm, the arm retracts and hits a snap switch which stops the arm. The PCB has an LED, a snap switch, PCB terminal, and the switch at the top of the box soldered on. The build itself is powered by 3 triple-A batteries. While building the project i had an extremely hard time securing the case which I eventually solved by using a clamp to secure the corner posts so that i could put a screw through the post. This created an imprint of the screw which eventually made it easier to screw into the box. Next I plan to use my knowledge about motors to build the 3 Joint Robotic Arm.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Q8K0SotvSBg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 

# Code

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
|  |  |  |  |
|:--:|:--:|:--:|:--:|
|  |  |  |  |
|:--:|:--:|:--:|:--:|
|  |  |  |  |
|:--:|:--:|:--:|:--:|
