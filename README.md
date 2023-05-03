Download Link: https://assignmentchef.com/product/solved-cs2261-homework-02-simple-mode-3-game
<br>
In this homework, you will be making a simple game in Mode 3. Some suggested games along the complexity level we expect are:

<ul>

 <li>Pong</li>

 <li>Breakout</li>

 <li>Catch the Falling Rectangles</li>

 <li>Dodge the Falling Rectangles</li>

</ul>

<strong>YOU ARE NOT ALLOWED TO COPY LAB CODE EXCEPT FOR YOUR MYLIB.C AND MYLIB.H FILES.  </strong>

You are free to choose one of these, but encouraged to create your own original game (if you choose this option, please speak with a TA first so that we can ensure it is on the expected difficulty level). Your game must have the following:

<ul>

 <li>An end (win/lose) state

  <ul>

   <li>You do not have to have anything happen once you reach this state, as long as it can be understood that you have reached an end to the game.</li>

  </ul></li>

 <li>At least two moving objects</li>

 <li>At least two buttons used for input</li>

 <li>Collision that matters

  <ul>

   <li>Something must happen whenever two different objects hit each other</li>

  </ul></li>

 <li>A readme.txt file

  <ul>

   <li>An instruction manual (of sorts) that tells a player how to play your game ● Only a ​<em>minimal </em>​amount of flicker.</li>

  </ul></li>

</ul>

Your code must have the following:

<ul>

 <li>Multiple .c files</li>

 <li>At least one .h file</li>

 <li>Good organization (see tips below)</li>

 <li>Meaningful comments</li>

</ul>

<h1>Tips</h1>

<ul>

 <li>Start early. Never underestimate how long it takes to make a game.</li>

 <li>For collision code, draw pictures. Graph paper is your friend.</li>

 <li>When splitting code between multiple files, put code that will be useful in multiple games in myLib.c, and code specific to this game in main.c or other files. Those other files should be specific to a concept (collision, etc.).</li>

 <li>Organize your code into functions specific to what that code does. Your main method should not be very long.</li>

 <li>Having ​update() and ​​draw() functions that you call in ​ main() ​ is helpful.​</li>

 <li>Make sure the order takes into account waiting for vblank at the correct times to minimize flicker.</li>

 <li>Build upon the myLib.c and myLib.h files from previous assignments.</li>

</ul>