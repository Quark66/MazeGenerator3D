# MazeGenerator3D

Long time ago when labyrinth was so popular (Greeks legends, Pyramids..)
I spend a lot of time in manual designing of labyrinths and mazes. Manually with pencil in my hand. These days
we have computers and it can help us very well.

## 2D maze 

Flat "paper" maze is very simple for going trought. My generation algorithm is based on wall construction. Generation and grouwing
individual pieces of wall in the defined space of maze. After fullfilling whole area we can say that each room in the maze 
is fullz connected to another. There is only one reqwuirement for growing and genetating walls . Every new wall panel can
be build into free space only, e.g. it can not be merged with existing wall. That's all, really!

## 3D maze

There printiplec cannot be easily applied in 3D space. On the opposite of 2D there are simpliest method - growing free space 
inside of mass of 3D blocks. There are similar principle extended into 3D. Every new room can be build (grave) only into 
free, e.g. mass space. No additional connection can be done.

## Bounds definition, input, output.

Program starts with "blank" box with dimension X,Y,Z. Each dimension represents number of caves in particulat direction. 

## Code logic

