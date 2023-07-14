201-Class 04

READ CLASS-04

Reading
Learn HTML
Creating Hyperlinks
1. To create a basic link, we wrap text or other content inside what element?

Inside the <a> element.

2. The href attribute contains what information?

The href attribute contains the URL that tells the browser where to go once the link is clicked.

3. What are some ways we can ensure links on our pages are accessible to all readers?

We can make sure that there are spaces around the link and try to make it more prominent with icons. Optional things.

CSS Layout
CSS Layout: Normal Flow CSS Layout: Positioning

1. What is meant by “normal flow”?

Normal flow is the default positioning with elements on a webpage. The arrangement is the same before we add in other code to change their positioning.

2. What are a few differences between block-level and inline elements?

Inline elements
* They can begin within a line.
* They do not start a new line.
* And the width only extends as far as it is defined by its tags. 

Block level elements are the opposite.
* They create a whole new block of code with a little space.
* They start new lines.
* 

1. _Static__ positioning is the default for every html element.

The answer is “static” positioning.

1. Name a few advantages to using absolute positioning on an element.

* Precise positioning. You have the power to put things where you want to on pages.
* Overlapping elements. You have the power to make things overlap on top of each other.
* Things can float in space on the page like a content helicopter.
* Custom layouts. 

1. What is a key difference between fixed positioning and absolute positioning?
	
	In fixed positioning, an element is stuck on one place. It does not matter where you move your browser or where you go. Up, down, left or right, the fixed positioned element will stay in place.
	In absolute positioning, you can move things wherever you’d like.
Learn JS
Functions – Reusable Blocks of Code
1. Describe the difference between a function declaration and a function invocation. 
	
	In JavaScript, a function declaration is like creating a named set of instructions that you can use later. You give it a name, write the instructions for what the function should do, and then you can use that function whenever you need it by calling its name.

	In JavaScript, when you invoke or call a function, it means you're asking the computer to execute the instructions inside that function. You use the name of the function followed by parentheses to tell the computer to perform the tasks defined in the function.

What is the difference between a parameter and an argument?

	A parameter is a value inside a function that describes what kind of information is needed, while an argument is the actual value or information you provide to the function when you use it.

Miscellaneous
6 Reasons for Pair Programming
1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.

* My partner can explain gaps in my information that will help me to bridge concepts I already know about completing the overall idea of what I am supposed to know.
* In the same way, when I explain things to my partner in the same way, it helps to solidify what I already know. 

I can complete assignments faster with that.

Things I Want To Know More About
I just want my page to look pretty like Chester’s. That requires CSS work.





PERSONAL NOTES

Code Review
Same alert prompt appears multiple times.
 
Noticing that I am getting lost in my code.
Jacob says 
*use a debugger statement.
*Draw a picture for every line of code in your loop.


CSS Positioniing
Margin is the outermost layer. It separates from sibling elements.
Border is between the margin and the padding.
Padding is the nearest to the content
Content is the content.

Every element can be positioned using “top”, “bottom”, “left”, “right.”
Static-default elements are not movable. They are stuck win their layout,
CSs position property tells the browser how to interpret these commands.

Relative-element can be moved in relation to it’s parent element or closed sibling

Absolute - Ignores sibling elements. Allows position properties to ignore the elements around them.

Fixed-Ignores the parent and sibling elements.

JS Functions
What are functions?
Allows for code to blocks to be re-used.

function logString(logNum){
    debugger;
    let batman=[];
    for(let i=0; i<logNumber;i++){
        console.log("Hey there "+batman);
        batman+="nana"
    }
}

//function invocation
logStrings();

Pair Programming(Lab Prep)

Driver-responsible for typing
Navigator-Research and informing the driver what to write.

Step 1: Driver will fork( copy from one code base into another person GitHub account) the navigators repo.

Step 2: Driver willl clone the form onto their local machine.

Step 3: Do the work like normal.

Step 4: When finished, make an add/commit/push to your for.

Step 5: Open a Pull Request from your fork to the original navigator repo.

Step 6: Navigator will accept the PR.