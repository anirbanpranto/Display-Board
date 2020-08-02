# Display-Board
A small program to display strings into a displayboard and scrolling them to left, right, up and down.
This program was an assignment for my seniors but since it was interesting I gave it a try. It uses a bit of linear algebra knowledge about cartesian planes to draw the alphabets.

The project has been ran on Ubuntu 18.04 LTS Linux machine. To run in on Windows machines you need to edit the code a bit. Here are the instructions.
### Replace the following code
```cpp
void clrscr(){
	system ("clear"); //used for clearing the screen for each frame
}
```
### With
```cpp
void clrscr(){
	system ("CLS"); //used for clearing the screen for each frame
}
```
