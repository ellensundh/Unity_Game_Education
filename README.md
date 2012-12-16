Unity Game Education
====================

Simple game base for moving a player in Unity. 

#Installation
* Open up the file in your Unity project. Unity will ask you to import all assets. Click on "Import" and you will get all the files you need.
* Double-click the icon named "Game_Base" in the "Project" window. This will open up the Game_Base scene in Unity.
* Click on the "Play" icon to run the game.

##Objects in project
###Cube
This object is controlled by the arrow buttons.
### Directional light
This is a light to cast light to your entire scene. With Unity Pro this light can cast shadows in your scene.

###Floor
The floor is an object made out of a cube and makes the floor of the scene. The floor has a component called Box Collider which means that if there are other object with this component they will collide. The material of this box collider is set to Bouncy so that other box colliders will bounce one they hit the floor.

###FlowerCube
A game object with the material of a flower pattern.

###Main Camera
This is the main camera of the scene. The camera can be moved around and rotated in the Unity scene. The camera has a script attahed to it called "Game". You can see it as a component if you select the Main Camera. To open the script, click on the JS icon Game right after it says Script.

![Alt text](http://ellensundh.github.com//Unity_Game_Education/inspector.png "Game script shown in Inspector")

###Point light
A source of light that is place out in the Unity scene.

###Sphere
A sphere that has the component "Box Collider" added to it together with the component RigidBody which gives the sphere gravity as it is bouncing on the floor. 

