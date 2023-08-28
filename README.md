# Random-Color-Controller-using-JS
It is a basic JavaScript Program which controls background color of a window using setInterval and clearInterval methods.


Walkthrough
1. Create a basic window with h1 header and two buttons namely start and stop using CSS
2. Create a randomColor named function which contains a string named hex which contains all the possible hexcode color characters and a for loop  which runs for 6 times(as hexcode is of 6 characters) and the value of 'color' is updated using Math.random and Math.floor on hex.
3. addEventListner on both start and stop buttons
4. Create a function named changeBgColor which will change the background color of the window then bind this into a function called startChangingColor and then use setInterval(changeBgColor,500)
5. Similarly do for the Stop button
6. And then use the clearInterval method.
 
