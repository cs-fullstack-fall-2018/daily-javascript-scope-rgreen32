# daily-javascript-scope

Write your answer AT THE BOTTOM of the page

``` javascript
function sample() {
    return fname + lname;
}
var fname = prompt("Please enter your first name:");
var lname = prompt("Please enter your last name:");
document.write(sample());
```

A: AdamWarlock

B: Nothing, blank screen

C: ReferenceError: fname not defined

D: fnamelname

WRITE ANSWER HERE



/*

	KEY: INCORRECT - No Answer Submitted :-(

	Correct answer is 'D'

	Even though the vars 'fname' and 'lname' show up in the code
	after the function 'sample()' that uses them, the variables
	get defined before the function is called.

	The function sample() would return whatever the user entered at the 
	prompts for fname + lname.

*/ 