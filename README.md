# Hand-Interaction-Showcase
## Summarize
This project uses computer vision algorithms that detect hands to allow interaction with 3D models just by moving or closing the hands. Este proyecto se creo con el fin de usarse en ventiladores holograficos de Hologram PyP. 

## Machine learning algorithm
Dentro de los algoritmos de vision por computadora elegi [MediaPipe Hands](https://mediapipe.readthedocs.io/en/latest/solutions/hands.html). Un modelo de machine learning para el seguimiento de manos y dedos. Este me permite detectar 21 puntos clave de la mano o incluso de varias manos. 

![image](https://github.com/user-attachments/assets/7c271d8e-25d4-43c5-ae49-7051eb6f441a)

## 3D Model Representation
To represent the 3D model we used the video game engine [Panda3D](https://docs.panda3d.org/1.10/python/introduction/tutorial/index). 

![image](https://github.com/user-attachments/assets/ac274ed6-5a96-46fb-80c9-d618cdbaccd0)

Advantages:
- 100% Python programming
- High performance
- Good documentation
Disadvantages:
- Not compatible with current model formats such as fbx or animations.
- Low graphic power in illumination and textures.

## Use case
This project was proposed for use in holographic fans from [Hologram PyP](https://hologrampyp.com/), holographic fans are a display technology that gives the sensation of floating in the air thanks to the synchronization of rotating blades and rapidly changing LEDs. The use of this project in holographic fans gives a user experience not seen before.

![hand-interaction](https://github.com/user-attachments/assets/b391618c-0250-457f-a5b0-8f4bf7401f42)


# Acknowledgements
- Victor Perez, CEO of Hologram PyP for supporting this project.
