# Python-Space-Shooter-Game

## About The Project
The project is a throwback to the old Atari game "Space-Invaders", developed in a casual bullet-hell style. The player is expected to destroy incoming enemies while simultaneouly dodging their attacks. The controls are as follows:
- UP ARROW: Moves forward
- DOWN ARROW: Moves backwards
- LEFT ARROW: Strafe Left
- RIGHT ARROW: Strafe Right

As the player destroys all enemy spaceship in each wave, the game progressively gets harder where more enemies are contained in the following waves.

## Building/Running
The **Executable** directory contains the executable(SpaceShooter.exe) of the game built using [PyInstaller](https://pyinstaller.org/en/stable/#). To run the executable, simply double click the executable.
  
The source file of the game is contained within a single **SpaceShooter.py**. The third-party module [PyGame](https://www.pygame.org/wiki/GettingStarted) is required to run the code. PyGame can be installed via [Package Installer for Python](https://pypi.org/project/pip/) (PIP), using the command:  
_pip install pygame_
In the directory of the source file, use command:  
**For Windows**  
_python SpaceShooter.py_  
**For Linux**  
_python3 SpaceShooter.py_

## Core Features
The core features of the game are as follows:
1. Main Menu
2. PyGame Initialization
  - Window
  - Texture Loading 
3. Game Objects
  - Player Ship - Yellow
  - Enemy Ship - Red, Green, Blue
  - Lasers - Yellow, Red, Green, Blue
4. Main Game Loop
  - Input Handling
  - Player Logic
  - Enemy Logic
  - Collision Detection & Resolution
  - Lose Condition

## Credits
Tutorial: [TechWithTim](https://www.youtube.com/watch?v=Q-__8Xw9KTM&ab_channel=TechWithTim)  
Assets:
1. Background: [ansimuz](https://ansimuz.itch.io/space-background)
2. Ships: [TechWithTim](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbDJwNzhDQTFBX2ZZbmRUSGRSTXZIZGRzbENUQXxBQ3Jtc0tsaF9OcXNOY1o2ejh6QWFKUW1MQWR0bXhBMDMyazJQb0lyd3Z3eU9icEpYMEZuV1FHTl85Vk1oc09Mc0hGU3JkUDFnb1I3ZEtpWTZmTTdlZUZBNWhIR2ZKdEc1MHVZVjdPeHU5ZUxPdXBiVmUwX3NoMA&q=https%3A%2F%2Ftechwithtim.net%2Fwp-content%2Fuploads%2F2020%2F04%2Fassets.zip&v=Q-__8Xw9KTM)
