# Programming fundation with JS

## Variables ("box" holds values)
 ```
 var x = 1; // Declare a varable, name the variable, and set the value.  
 x = z - 1; // Right side call experssions. Update value of a existing variable. No "var".  
 var fimg = new SimpleImage("xxx.png") // new create a new object. "SimpleImage" specifies the type.  
 ```
+ Variables can also hold images, strings 

## Methods
  + Perform some operation. Invoked on an object.  
  + Excution goes into the methods. Do whatever the code is there. The method retrun an answer back. Method call evaluate to that value. Excution resumes after the method call.  
  ```
  var w= fgImage.getWidth(); # object, ".", method
  ```
## Functions (not invoked on objects)
```
function squre(x) { // key word, name of the function, parameter names
var ans = x * x ;  // body of the function
return ans;  // return statement
}
var y = squre(4); // calling a function
```
Why use method and function? Good abstraction.Seperate interface from iplementation.

## Types of Data
+ Every thing is a number. Type specifies how to interpret the number and how to operate on it.
```
var n1 = 1;
var n2 = 2;
var s1= "a";
var s2= "b";
var n3 = n1 + n2;
var s3 = s1 + s2; // concatnation
```
How does JS knows the data type? 
+ Keep track of it with the value. Both the type and value are stored in the memory.
+ Called "dynamically typed" language.  

While Java:
+ "Statically type" language
+ Writes types in code.

## For Loops
```
for (var pixel of img.values()) { // variable, keyword "of", what to loop over, body of the loop;
var newG = 255 - pixel.getGreen();
pixel.setGreen(newG);
 }
```

## Conditional Execution
if () {}

## How to find bugs?
+ Observe a  Phenomenon, Ask a question, Gather Information and apply expert knownledge(on and on) 
form a hypothesis, test hypothesis, accpet hypothesis.
+ How to gather information?
Debug tools, print statement, run code by hand.
+ What is a good hypothesis?
 + Testable, prediction about behaviour
 + Actionable, can fix program if Ture.
 + Specific.
 
 
 ## Event-drive programming.
 + Create Buttons with Divs
  + Use an <input> element
  + onclick event handler
  + call javascript function.
 
 ## Changing Pages Interactively
 + to change a web page via Javascript, Must access HTML elements by code.
 + eg: document.getElementById("demo").innerHTML = txt
 
 
## Input and events
+ The HTML input tag is used to create an HTML element, like a button that gets input from the user and processes that input with JavaScript code.
+ 



