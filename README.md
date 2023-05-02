Download Link: https://assignmentchef.com/product/solved-cpsc-223n-assignment-3
<br>
<strong>Traveling Ball</strong>

<strong>Introduction</strong>

This assignment is the introduction to animation using C Sharp.  Here you are going to make a simple animated object move along a specified path.

<strong>Description of user interface</strong>




<ol>

 <li>The UI must have a large physical size. Make the UI fill about 90 or 95% of your monitor.  Only leave a small area of the monitor not filled by the UI.</li>

</ol>




<ol start="2">

 <li>The graphic area covers the entire UI form. However, we section it off by colors.  Make a narrow rectangular part at the top have a light color.  In this top portion place your name.</li>

</ol>




<ol start="3">

 <li>In the middle of the graphic area use a different color to show the area for animation. This area should be very large compared to the other two areas.</li>

</ol>




<ol start="4">

 <li>At the bottom of the graphics make rectangular section have a third distinguishing color. In this third area place the control buttons and the output textboxes.</li>

</ol>




<ol start="5">

 <li>In the middle graphic area draw a fixed rectangle with a boundary that is one pixel wide. This rectangle is the path the animated ball will follow.  Make this rectangle large.  When the ball moves the center of the ball will always be directly over that path line.</li>

</ol>




<ol start="6">

 <li>The initial position of the ball is in the upper right corner of the path, the ball travels counterclockwise.</li>

</ol>




<ol start="7">

 <li>There is an area in the lower part of the UI thatl contains all the controls such as buttons and output text boxes.</li>

</ol>




<ol start="8">

 <li>The speed of the ball is fixed in the software. You as programmer pick a nice reasonable speed that is not too fast nor too slow.</li>

</ol>




<ol start="9">

 <li>The graphic area is refreshed at a fixed rate of 30 Hz. This is a fixed number and should be declared as a constant in your program.</li>

</ol>




<ol start="10">

 <li>There is a button with the initial label “Go”. When the user clicks on Go the animation starts, namely: the ball moves counter clockwise always maintaining its center directly over the path line.  When the ball is in motion the label on the “Go” button changes to “Pause”.  If the user clicks on the “Pause” button then the clock stops and the label changes to “Go”.</li>

</ol>




<ol start="11">

 <li>When the ball completes a circuit (returns to starting position) then it stops moving and changes to a gold color.</li>

</ol>




<ol start="12">

 <li>There is a reset button. If the user clicks on this button then the clock stops and the ball returns to its initial position.</li>

</ol>




<ol start="13">

 <li>There are three output fields: one for the x coordinate of the center of the ball, one for the y coordinate of the center of the ball, and one for the direction the ball is moving. There are four possible directions: left, down, right, and up.  When animation is in progress these three fields are being updated every time the graphic area refreshes.</li>

</ol>




<ol start="14">

 <li>There is an exit button. If the user clicks on the exit button then the clock stops and the form closes.</li>

</ol>

<strong>Details about functionality</strong>




You pick a nice size and color for your ball.  A ball with radius 5 or less is too small because it is too hard to see that little dot.  A radius greater than 20 too big.  You pick a nice radius somewhere in the middle.  The radius becomes a fixed constant of the program.

You pick nice contrasting colors for the ball, the background, and the painted line on the ground surface.

When the UI first opens the ball is in the upper right corner of the path.  The center of the ball is directly over the corner painted on the ground.

When the user clicks on “Go” the ball begins moving along the edges of the rectangle.  The ball continues in motion until the user clicks on “Pause” or clicks on “Exit”.  It the user clicks on “Reset” the ball simply jumps to its initial position.

This program requires three files.  The first file is a driver file, which is very similar to the driver file of the previous assignments.  The second file defines the user interface.  The user interface file will be like the second file of the previous assignment, but this one have more declarations.  This UI file will be more complex that those in the past because this one must contain a function that computes the next coordinates of the ball given its current coordinates.

























































































