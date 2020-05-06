# Project 3 - Help MacGyver to escape!

## 1. Introduction.
This python package is a 2D game named 'Help MacGyver to escape!'. It consist of moving the hero (MacGyver) on a maze and make him escape that place. The hero will be able to leave that place if he reaches the exit. The problem, a guard is protecting the exit and he has no intention to let our hro go out so easily. Therefore, the hero will have to collect all objects dispatch here and there in the maze (a platic tube, a needle and a bottle of ether). This in order to build a syringe full of ether that will allow him to inject the guard and put him to sleep. This is how, our hero can become a free again. 

## 2. Prerequisite.
This programm requires the following components:
* python 3
* pygame==1.9.6

## 3. Installation.
### 3.1. Download.
Download this repository on your system, at the location that suit you best.

### 3.2. Python3 install.
Ensure you have **python 3** installed. If not, you can download it and install it from the [python offical website](https://www.python.org/). You'll find the necessary documentation there.

### 3.3. Create a vitrtual environment (*optionnal but recommended*).
In order to avoid python version and libraries conflicts:
* Create a virtual environment using **venv** package
>python -m venv game_repository/my_virtual_environment<
* Activate the created virtual envrionnment.
>source my/game/repository/my_virtual_environment/Scripts/activate<
'''
Documentation for this is also available on [python offical website](https://www.python.org/).

### 3.4. Pygame install.
Install **pygame** on you virtual environement. You can  install it from the [pygame website](https://www.pygame.org/news). You'll find the necessary documentation there to do so.

### 3.5. Play.
The programm is now ready to use. You can lauch xxx.py with your bash:
> python xxx.py

### 3.6. Leave the virtual environment.
Once you're done with playing, you should leave the virtual environnement. Simply type
> deactivate
>
in your bash.
> deactivate<blockquote>


### 3.7. Uninstall.
If you want to uninstall the game simply delete the complete repository.

## 4. Settings.
No settings required. Files & folders must b e used as is and shouldn't be modified.

## 5. User's Guide.

### 5.1 Goal:
The goal is to make the hero escape the maze. For that he must:
* collect all objects present on the maze.
* go to the guard, and if all objects have been collected, escape the game usccesfully. If not, then the hero will loose.

### 5.2. How to:
* Launch the game running the xxx.py file.
* On 'Menu' page, decide to play the game or not (if not is selected, then the programm will end) .
* Use keyboards arrows to move the hero in the maze.
* Objects get collected automatically when hero arrives on their positions.
* Game will end successfuly or not once the hero arrives at the guard position.
* Exit game can be done at any time by clicking on the game window right corner "x" button.