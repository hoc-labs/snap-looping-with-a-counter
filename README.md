# Looping with a Counter

[Reference from BJC](https://bjc.edc.org/bjc-r/cur/programming/1-introduction/3-drawing/6-the-for-block.html?topic=nyc_bjc%2F1-intro-loops.topic&course=bjc4nyc.html&novideo&noassignment)

Computer scientists describe this program structure as looping, repetition, or iteration. Sequencing, selection, and iteration are building blocks of algorithms.

In the previous lab, when we were drawing shapes, we used the **repeat** block to loop a specific number of times.

In this lab, you will use **for loops** to repeat and count the repetitions so you can use that counter to draw shapes with repeated patterns.

![](https://github.com/hoc-labs/images/blob/main/spiral.png?raw=true)![](https://github.com/hoc-labs/images/blob/main/nested-squares.png?raw=true)

You can use ![](https://github.com/hoc-labs/images/blob/main/for.png?raw=true) to name a variable (here, ![](https://github.com/hoc-labs/images/blob/main/variable-i.png?raw=true)) that counts each repetition, and you can use that counter variable in the repeating script. For example, the for block lets you simplify long scripts like the one below. Each time the for block runs the script inside, it changes the value of the variable by 1, counting from the first input number to the second.

![](https://github.com/hoc-labs/images/blob/main/for-loop-equivalent.png?raw=true)  ![](https://github.com/hoc-labs/images/blob/main/for-loop-drag-i.gif?raw=true)

**Build this script that makes the sprite say the numbers 1 through 10**.
Then modify it so that the sprite says 0, 2, 4, 6, 8, ... up through 30.


**Build the following script**
![](https://github.com/hoc-labs/images/blob/main/squirral-script.png?raw=true) 

![](https://github.com/hoc-labs/images/blob/main/nested-squares.png?raw=true)

* Make sure you can explain why the square spirals outward.
* Try switching the order of the 100 and the 1 in the for block in the squiral script. What is the result?
* Try changing the turning angle in the squiral script to other numbers such as 92, 126, etc.
* Change the inputs to turn and move to get as close as you can get to a smooth spiral

![](https://github.com/hoc-labs/images/blob/main/spiral.png?raw=true) 


### Extra Challenge
Open your Pinwheel project
* Build a **nest squares** block that uses **for loop** and your **draw polygon** block to draw nested squares. Give it an input so that it will draw whatever number of squares you specify, with each square larger than the previous. 
* Build **nest polygons** that accepts the number of polygons and the number of sides for the polygons.
* Build a script that draws 12 regular polygons, each with one more side than the previous one, as shown below.

![](https://github.com/hoc-labs/images/blob/main/polygons.png?raw=true) 

**Predict what this script will do before you try it**
![](https://github.com/hoc-labs/images/blob/main/nested-fors.png?raw=true) 

Build a script that counts down by 10 from 100 to 0 (that is, 100, 90, 80, etc.).

Find a way to use **for loop** to nest squares this way. Build your block with two inputs that let you specify how many squares the design will contain and how much bigger each square will be than the previous one.

![](https://github.com/hoc-labs/images/blob/main/concentric-squares.png?raw=true) 

The following code may give you ideas about how to create animations. Make sure to remove all wait 0.5 secs blocks from your pinwheelcode so they don't slow it down. The warp block allows the drawing of the pinwheel all at once.

![](https://github.com/hoc-labs/images/blob/main/animationCode.png?raw=true) 

This block is like the squiral, but instead of changing the input to move, it changes the input to turn:

![](https://github.com/hoc-labs/images/blob/main/inspi.png?raw=true) 

* Try sketching what it will draw with an angle of 2.
* Then build it, and try each of these tests:
* You can stop each test with the **stop** button when you're sure nothing new will happen, but don't decide that too quickly!

![](https://github.com/hoc-labs/images/blob/main/inspi-tests.png?raw=true) 

What's going on? Can you work out a theory to predict anything about the shape it draws for a particular angle input?