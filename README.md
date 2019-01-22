# DriversVrepSimulation-2019

![image](https://user-images.githubusercontent.com/25615500/51441423-1d356e80-1cda-11e9-8bb6-7ef0bb4410cf.png)                           ![image](https://user-images.githubusercontent.com/25615500/51442072-7654d080-1ce1-11e9-9420-0460c5511492.png)

GreenBlitz Driver Simulation is a robot simulation which purpose is to train drivers, and to simulate games and strategies.

## Features

The simulation supports the entire 2019 game, with an option to drive couple of robots at the same time.
In addition, the simulation offers a scoring system, which calculate the current score of each team!

![image](https://user-images.githubusercontent.com/25615500/51440335-bbbbd280-1cce-11e9-89d0-69c829340b5b.png)
*View of the entire field*

![image](https://user-images.githubusercontent.com/25615500/51440403-59af9d00-1ccf-11e9-806f-2c77d7931b56.png)
*the View from the second driver station*

The simulation is built with the V-Rep simulator, V-Rep is a great tool to build any simulation of any kind, for more information about V-Rep see: http://www.coppeliarobotics.com/.

## Installation

In order to use GreenBlitz Driver Simulation, you need to follow these steps:

1. Download educational version of V-Rep to your computer from this site: http://www.coppeliarobotics.com/downloads.html.
![image](https://user-images.githubusercontent.com/25615500/51440432-b7dc8000-1ccf-11e9-8147-595307d1ffcd.png)
2. Open and install the V-Rep exe installation file. ![image](https://user-images.githubusercontent.com/25615500/51440450-d9d60280-1ccf-11e9-9bab-25d9a4d92beb.png)
3. Download the latest GreenBlitz Driver Simulation version from this Git repository. ![image](https://user-images.githubusercontent.com/25615500/51440456-f83bfe00-1ccf-11e9-9b41-f98d0b901120.png)

*The latest version will always have the higher number and will be if the first page, not inside the archives.*

In order to activate and use the simulation you first need to connect a joystick to your computer.
*The joystick must work with the operating system you are using.*
After you may start the simulation by opening the latest simulation file.
*if you change the connected joystick when the simulation is activated you need to reset the simulation.*

## Basic V-Rep 

V-Rep is a robot simulation, when you are using the simulation, you are using it in the creation area, which means that you can change the simulation to your liking.

### Movement

To move in the simulation, you need to press the movement button ![image](https://user-images.githubusercontent.com/25615500/51438487-9b334e80-1cb5-11e9-98db-2c0f07f43592.png) in left side of the toolbar and move by clicking on the left click and moving the mouse.
To change your perspective, press the perspective button ![image](https://user-images.githubusercontent.com/25615500/51438512-ed746f80-1cb5-11e9-8f9a-e4653c6711be.png) in left side of the toolbar, press on the left button and to move the mouse.

### Activation

To activate the simulation press on the activation button ![image](https://user-images.githubusercontent.com/25615500/51438533-201e6800-1cb6-11e9-9a4a-fedf843df463.png) in the middle of the toolbar. In addition, to close the simulation run press on the stop button ![image](https://user-images.githubusercontent.com/25615500/51438543-36c4bf00-1cb6-11e9-8db4-00aef72ec262.png) in middle of the toolbar.

### V-Rep Basic Variables

In V-Rep the user sets a lot of basic values which change the simulation behavior.
We recommend on those setting, but we advise to check on which settings the simulation work the best on your computer.

1. Tick time- each tick in the simulation is taken at least the time you set. we recommend on 25 milisec for tick, but if the simulation runs if a big delay you can set the tick time longer. ![image](https://user-images.githubusercontent.com/25615500/51438602-f7e33900-1cb6-11e9-9fbc-896133de274d.png)
2. Accuracy - we recommend the best accuracy but if the simulation run to slow if a big delay, you may change the accuracy in the following bar: ![image](https://user-images.githubusercontent.com/25615500/51438619-34af3000-1cb7-11e9-8289-f822281a2d96.png)
3. Simulation time - press on the real time button ![image](https://user-images.githubusercontent.com/25615500/51440184-050b2280-1ccd-11e9-9045-09f085cae61d.png), in order to make the simulation to run in real time.
4. Physical engine- V-Rep offers a lot of physical engines for the simulation. You can change them in this bar ![image](https://user-images.githubusercontent.com/25615500/51440203-4c91ae80-1ccd-11e9-832d-1cfb8a77e5a1.png) , we recommend to use Bullet 2.78, which comes with V-Rep.

*For more information about V-Rep see V-Rep BubbleRob tutorial : http://www.coppeliarobotics.com/helpFiles/en/bubbleRobTutorial.htm.*

## Joystick Buttons

The robots in the simulation are controlled by a joystick like an Xbox controller.
- Left axis - forward and backward -move value
- Right axis - side axis - rotate value
- Povs - up and down - control the elevator
- Y - change gear from power to speed and backward.
- A - open a window with a view from the robot driver station, and after it every press change the view to another driver station or to the robot camera.
- B - if the robot is near his team feeder, than the feeder throw one disk
- X - same as b but with balls.
- LB - pick up a ball or a disk in range of 60 cm from the elevator, works only when the elevator is in the lowest level.
- LR - throw the grabbed object, if is in a range of 60 cm from a tower or bay and have a disk then place the disk in the bay or in the tower, dependent on your elevator level.

## Scoring System

The scoring system calculate the teams scores, to activate the score system you need to press the start button in the first joystick (joystick zero).
After the start button is pressed, a window will open with the current score of the teams, each press on the button will update the score in the screen.

![image](https://user-images.githubusercontent.com/25615500/51540058-294a3900-1e5e-11e9-9bf3-aa1c5e214f04.png)


*For any support and request, you are more than welcome to contact us through any means including GitHub.*

**This simulation was created by Ofek Eshet, a member of GreenBlitz Programing Team, Commander and chief, First Lieutenate and the only active member of GreenBlitz Simulation Catagory.**

Thanks for our beloved mentor shahar for his support and knowledge in creation of the simulation.
