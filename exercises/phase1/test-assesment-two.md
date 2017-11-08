1. Which HTML 5 tag would you use for semantically correctly wrap your page footer?<footer>
2. What is the difference between a class and an id in HTML and what is it used for?id is an unique element, while class is for more than one element
3. What is wrong in the following HTML?ID needs to go first before class
  ```
  <div class="some-class">
  <div class="some-class" id="someID"></div>
  ```
4. How would you create a new file named `testFile` with the command line?mkdir testFile
5. How would you remove this file with the command line?mv
6. Given you are in a folder that has git and a remote branch on github. How would you get the most current version on your machine?git status
7. Which industry vertical are you interested in and why?health care industry because it is a broad industry and i feel it is more opportunity
8. Using Javascript, please write a function testFunc, that takes two arguments, an array and a number, and returns a new array where each element has been multiplied with the second number? E.g. `testFunc([1, 2, 3], 2)` would return `[2, 4, 6]`.
var a = testFunc([1,2,3], 2);
function testFunc(arr,number) {

for(var i = 0; i < arr.length; i++) {
 arr[i] = arr[i]* number;
console.log(arr);
  
}
}

9. Print all numbers from -10 up until 10 to the command line using a for loop in JS.
var startNumber = -10;
var endNumber = 10;

for(startNumber = -10; startNumber <= endNumber; startNumber ++) {
if (startNumber < 10) ;
console.log(startNumber);
}
10. What would the console print in following example 5
```
function outer() {
  var x = 5;
  
  function inner(multiplier) {
    console.log(multiplier - x);
  }
  
  return inner;
}

var firstResult = outer();
firstResult(10);
```
11. What will be output to the terminal?36
```
var someObject = {b : "some test", a : "this is A", c : function(input){ return input * 6;}}
console.log(someObject.c(6));
```
