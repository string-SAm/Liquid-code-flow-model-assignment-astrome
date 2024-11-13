# Liquid-code-flow-model-assignment-astrome
Created with CodeSandbox

Above code is written to create an interactive visual experience where users can start,stop, and reset an animation of colorful bars. Each bars's height fluctuates randomly, providing display that can be manipulated via buttons.

There're five bars and three buttons which controls the animation of button within a certain width and height, and to handle animation i uses interval timer for the animation.

Few of the JavaScript Function which uses to build this UI dynamic 

startAnimation(): This Function executed when we press on start button, it firstly cldear the existing interval to prevent multiple intervals from running simultaneously, and then setup a new interval which calls updateBars() function after every 1 second which helps to update the height of each bar randomly between 0 to 200 px, and uses some css property to smoothy transition of bars.

stopAnimation(): It clears the interval and stopped the height updation for bars.

resetAnimation(): It reset the height of bars to 200px , it firstly execute the stopAnimation() so that bars get stopped.

As all the button has there own event listener.
