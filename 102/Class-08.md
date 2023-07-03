Class 8

NOTES IN-CLASS

LOOPING CODE

Looping Code- any code that runs more than once.

While loop

for (increment   break condition  updater){
	all the code to be repeated;
}

SOMETHING IDK

for (let i=0; i<10; i++){
    console.log("i is equal to:", i);
    debugger;
}

function askName(){
    let name = prompt("What is your name?");
    while(!name) {
        name=prompt("No I really want your name");
    }
}

for (let i=10; i.0; i--){
    if (i>5){
        console.log("Your i is large")
    }
}

ANSWERS

1. What is an expression in JavaScript?

	An expression is a valid unit of code that resolves to a value.
	examples: x=7 and 7+5

1. Why would we use a loop in our code?

Loops simplify code. What would normally take hundreds of lines of code can be written down to just a few.

1. When does a for loop stop executing?

The for loop ends when the end of its range is reached or we terminate it with a break statement.

1. How many times will a while loop execute?
If the condition is true and there is nothing to stop it, I believe the loop continues indefinitely.