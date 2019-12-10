# Ludum-Library
Ludum Library is a game library to make simple games and prototyping concepts. Ludum uses turtle for fast easy graphics. The point of Ludum is to skip the boilerplate code such as window initialization so you can focus on your game.

## How to use Ludum
Getting started with Ludum is simple. Just download the repository as a zip open the zip and put the ludumLibraryModule.py 
script in the same folder as your game script. Once you have the ludumLibraryModule.py script in the same folder as your game 
code type
```python
import ludumLibraryModule as ludum
ludum.initializer.initializeScript()
```
into the top of your script to setup your script. To see documentation type
```python
import ludumLibraryModule as ludum
ludum.documentation()
```
into your Python shell to print out the documentation for Ludum Library. For a full tutorial got to my website 
https://geeko.github.io and go to the [blog](https://geeko.github.io/blog). 

## Documentation
Ludum uses classes to handle key parts of creating a game such as initializing the basic game variables creating and managing 
sprites. Here's a list of all the Handler's and their functions. A check means that everything that is planned to be added is added otherwise it is a work in progress.
* [ ] *class* initHandler: This handler class contains functions to set up the fundetmentals of a game script.
  * [x] *function* initializeScript(): This function imports turtle to the script and creates the screen this should be called at the start of every game script.
  * [ ] *function* initWindow(*title, color, width, height, animationSpeed*): This function creates window with the imputted title, color, width, height, and animationSpeed.
