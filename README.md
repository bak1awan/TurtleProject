# Turtles Project
## Description
### Project structure
When you will run this project in Unreal Editor, you will see a single `TurtlesContent` folder. It has the following structure:
1. `Blueprints` folder - this folder includes all the blueprint classes created by me. In the `Character` folder you can find an `AICharacter` and a `PlayerCharacter`. In `Environment` folder there are Blueprints for `Finish`, `Nest Of Turtles` and `Buttons`.
2. `External Content` - all used external assets are here - animations, meshes, sounds, VFX and etc.
3. `Images` - pictures used for some widgets.
4. `Level` - level itself.
### Key points to be noted
1. The project implements two types of buttons - one is pressed *by standing* on it, the other - *by interacting* with the keyboard.
2. Buttons, turtle nests, and finish locations are linked using *tags*.
