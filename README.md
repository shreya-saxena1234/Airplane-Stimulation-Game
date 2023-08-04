# Airplane-Stimulation-Game
An OpenGL Project implemented in c++

#### AIM:

The aim of this project is to create an interesting and creative game using OpenGL and also provides a beautiful graphical interface between the user 
and the system.



#### ABOUT:

In this basic airplane simulation game, you need to protect your aircraft from a building crash. You will need to navigate through a busy urban environment 
while avoiding tall buildings and other obstacles, the player has to control the airplane with the help of a mouse.

As you progress through the game, you may encounter more difficult scenarios like high speed and more buildings. It consists of levels in each level the 
speed of the airplane as well as obstacles is going to increase, if a collision occurs between plane and obstacles then the game will be over. 
And in the end, it will show us the distance traveled and levels successfully completed by the player.


#### CONCEPT USED:

1) Coordinate systems: Used for representing objects in a 2D space. The game uses a combination of world coordinates for the game world and screen coordinates for
rendering the game objects on the screen.

2) Geometric primitives: The game uses geometric primitives such as points, lines, andpolygons to represent various game objects, such as the buildings, clouds,trees and airplane and there are different textures and shaders applied to these primitives.

3) Transformations: Transformation such as translation is used to manipulate the position of an object in a 2D space. The game uses transformation and various physics calculations to move the plane.

4) User Interface Design: The player controls the airplane with the help of a mouse, and the user interface is designed to make this interaction as intuitive and easy to understand as possible. The game also displays information such as distance traveled and levels completed to help the player track their progress through the game.

5) Collision Detection: Collision detection is the process of detecting whether two objects in a game have collided with each other. In this game, collision detection is used to detect when the player's aircraft has collided with a building or obstacle, which causes
the game to end.

6) Background and foreground artwork : In a 2D game, the background and foreground artwork would be used to create a visually appealing game environment. In an
airplane simulation game, the background artwork would depict the city or landscape the player is flying over, while the foreground artwork would depict the obstacles the player must avoid.



#### USER DEFINED FUNCTIONS:

void keyPressed() - It works on the input via keyboard.

void mouse() - It works on the input provided by the user via mouse.

void printString() - It prints the text with font style at specific location.

void buildingBlock() - It generates the coordinates for building blocks.

void CloudBlock() - It generates the coordinates for building cloud.

void init() - It is an initialisation function.

void drawJet() - It is used to draw jet plane using shapes.

void gameEnd() - It is used for finding status of the game.

void drawBg() - It is used for setting the background of the game.

void welcome() - It is for creating the main window of the game.

void drawBuilding() - It is used for drawing towers.

void drawCloud() - It is used for drawing clouds.

bool cloudHit() - It executes when airplane hits the cloud.

bool buildingHit() - It executes whenever airplane hits the tower.

void printScore() - It is used to display score to the user .

void display() - It is a display function.

void moveJetU() - It is used to control the upward movement of airplane.

void moveJetD() - It is used to control the downward movement of airplane.


#### SCREENSHOTS:
![image](https://github.com/shreya-saxena1234/Airplane-Stimulation-Game/assets/74912353/620eaf93-39a3-44c8-968c-6aeda021ba59)

![image](https://github.com/shreya-saxena1234/Airplane-Stimulation-Game/assets/74912353/11184868-98e0-4df8-9322-7f3cb18b0f80)

![image](https://github.com/shreya-saxena1234/Airplane-Stimulation-Game/assets/74912353/696bf597-b8f7-4d70-9edc-6bda6354c28f)

![image](https://github.com/shreya-saxena1234/Airplane-Stimulation-Game/assets/74912353/9ef279e8-3719-4b80-8c1e-bd72c02c4846)

![image](https://github.com/shreya-saxena1234/Airplane-Stimulation-Game/assets/74912353/a2e5ce27-18e9-4a71-b209-676389187992)

![image](https://github.com/shreya-saxena1234/Airplane-Stimulation-Game/assets/74912353/973c3a23-ba64-4949-99a0-42038e121a16)
