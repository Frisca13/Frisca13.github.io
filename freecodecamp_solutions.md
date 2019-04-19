Exercise 1 JS

## How to write comments
```js
//abcde//
/*abcde*/
```
I know how to write comments

## Declare JavaScript Variables
```js
// Example
var ourName;

// Declare myName below this line
var myName;
```

## Storing Values with the Assignment Operator
```js
// Setup
var a;
var b = 2;

// Only change code below this line
var a = 7;
var b = 7;
b = a;
```

## Initializing Variables with the Assignment Operator
```js
// Example
var ourVar = 19;

// Only change code below this line
var a = 9;
```

## Understanding Uninitialized Variables
```js
// Initialize these three variables
var a = 5;
var b = 10;
var c = 'I am a';

// Do not change code below this line

a = a + 1;
b = b + 5;
c = c + " String!";
```

## Understanding Case Sensitivity in Variables
```js
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
var studlyCapVar = 10;
var properCamelCase = "A String";
var titleCaseOver = 9000;
```

## Add Two Numbers with JavaScript
```js
var sum = 10 + 10;
```

## Subtract One Number from Another with JavaScript
```js
var difference = 45 - 33;
```

## Multiply Two Numbers with JavaScript
```js
var product = 8 * 10;
```

## Divide One Number by Another with JavaScript
```js
var quotient = 66 / 33;
```

## Increment a Number with JavaScript
```js
var myVar = 87;

// Only change code below this line
var myVar = 87;myVar++;
```

## Decrement a Number with JavaScript
```js
var myVar = 11;

// Only change code below this line
var myVar = 1
```

## Create Decimal Numbers with JavaScript
```js
var ourDecimal = 5.7;

// Only change code below this line
var myDecimal = 5.7;
```

## Multiply Two Decimals with JavaScript
```js
var product = 2.0 * 0.0;
//my fix//
var product = 1.0 * 5.0;
```

## Divide One Decimal by Another with JavaScript
```js
var quotient = 4.4 / 2.0
```

## Finding a Remainder in JavaScript
```js
// Only change code below this line

var remainder = 11 % 3;
```

## Compound Assignment With Augmented Addition
```js
var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line

a += 12;
b += 9;
c += 7;
```

## nted Subtraction
```js
var a = 11;
var b = 9;
var c = 3;

// Only modify code below this line

a -= 6;
b -= 15;
c -= 1;
```

## Compound Assignment With Augmented Multiplication
```js
var a = 5;
var b = 12;
var c = 4.6;

// Only modify code below this line

a *= 5;
b *= 3;
c *= 10;
```

## Compound Assignment With Augmented Division
```js
var a = 48;
var b = 108;
var c = 33;

// Only modify code below this line

a /= 12;
b /= 4;
c /= 11;
```

## Declare String Variables
```js
// Example
var firstName = "Alan";
var lastName = "Turing";

// Only change code below this line
var myFirstName = "Frisca"
var myLastName = "Julia"
```

## Escaping Literal Quotes in Strings
```js
var myStr = "I am a \"double quoted\" string inside \"double quotes\".";
```

## Quoting Strings with Single Quote
```js
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```

## Escape Sequences in Strings
```js
var myStr = "FirstLine\n\t\\"+"SecondLine\n"+"ThirdLine";
```

## Concatenating Strings with Plus Operator
```js
// Example
var ourStr = "I come first. ";
ourStr += "I come second.";

// Only change code below this line

var myStr = "This is the first sentence. " ;
myStr += "This is the second sentence.";
````

## Constructing Strings with Variables
```js
// Example
var ourName = "freeCodeCamp";
var ourStr = "Hello, our name is " + ourName + ", how are you?";

// Only change code below this line
var myName = "Frisca ";
var myStr = "My name is " + myName + " and I am well!";
```

## Appending Variables to Strings
```js
// Example
var anAdjective = "awesome!";
var ourStr = "freeCodeCamp is ";
ourStr += anAdjective;

// Only change code below this line

var someAdjective = "interesting" ;
var myStr = "Learning to code is";
myStr += someAdjective;
```

## Find the Length of a String
```js
// Example
var firstNameLength = 0;
var firstName = "Ada";

firstNameLength = firstName.length;

// Setup
var lastNameLength = 0;
var lastName = "Lovelace";

// Only change code below this line.

lastNameLength = 8;
lastName = "Cordelia";

lastNameLength = lastName.length;
```

## Use Bracket Notation to Find the First Character in a String
```js
// Example
var firstLetterOfFirstName = "";
var firstName = "Ada";

firstLetterOfFirstName = firstName[0];

// Setup
var firstLetterOfLastName = "";
var lastName = "Lovelace";

// Only change code below this line
var firstLetterOfLastName = "";
var lastName = "L";

firstLetterOfLastName = lastName[0];
```

## Understand String Immutability
```js
// Setup
var myStr = "Jello World";

// Only change code below this line

var myStr = "Jello World"
myStr= "H";
myStr = "Hello World";
```

## Use Bracket Notation to Find the Nth Character in a String
```js
// Example
var firstName = "Ada";
var secondLetterOfFirstName = firstName[1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var thirdLetterOfLastName = "V";
var thirdLetterOfLastName = lastName[2];
var lastName = "Lovelace";
```

## Use Bracket Notation to Find the Last Character in a String
```js
// Example
var firstName = "Ada";
var lastLetterOfFirstName = firstName[firstName.length - 1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var lastLetterOfLastName = "e";
var lastLetterOfLastName = lastName[lastName.length -1];
var lastName = "Lovelace"
```

## Use Bracket Notation to Find the Nth-to-Last Character in a String
```js
// Example
var firstName = "Ada";
var thirdToLastLetterOfFirstName = firstName[firstName.length - 3];

// Setup
var lastName = "Lovelace";

// Only change code below this line
var secondToLastLetterOfLastName = "c";
var thirdToLastLetterOfFirstName = firstName[firstName.length - 3];

var lastName = "Lovelace";
```

## Word Blanks
```js
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
  // Your code below this line
  var result = "";
result+= "My "+myAdjective+" "+myNoun+" "+myVerb+" very "+myAdverb+".";
  // Your code above this line
  return result;
}

// Change the words here to test your function
wordBlanks("dog", "big", "ran", "quickly");
```

## Store Multiple Values in one Variable using JavaScript Arrays
```js
// Example
var ourArray = ["John", 23];

// Only change code below this line.
var myArray = ["array", 13];
```

## Nest one Array within Another Array
```js
// Example
var ourArray = [["the universe", 42], ["everything", 101010]];

// Only change code below this line.
var myArray = [["Bulls",23], ["White Sox", 45]];
```

## Access Array Data with Indexes
```js
var ourArray = [50,60,70];
var ourData = ourArray[0]; // equals 50

// Setup
var myArray = [50,60,70];

// Only change code below this line.
var myArray = [50,60,70];
var myData = myArray[0];

var myArray = [50,60,70];
```

## Modify Array Data With Indexes
```js
// Example
var ourArray = [18,64,99];
ourArray[1] = 45; // ourArray now equals [18,45,99].

// Setup
var myArray = [18,64,99];

// Only change code below this line.
var myArray = [18,64,99];
myArray[0] = 45;
var myArray = [45,64,99];
```

## Access Multi-Dimensional Arrays With Indexes
```js
// Setup
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];

// Only change code below this line.
var myData = myArray[2][1];
```

## Manipulate Arrays With push()
```js
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.push(["happy", "joy"]);
// ourArray now equals ["Stimpson", "J", "cat", ["happy", "joy"]]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
myArray.push(["dog", 3]);
```

## Manipulate Arrays With pop()
```js
// Example
var ourArray = [1,2,3];
var removedFromOurArray = ourArray.pop(); 
// removedFromOurArray now equals 3, and ourArray now equals [1,2]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
var removedFromMyArray = myArray.pop();
```

## Manipulate Arrays With shift()
```js
// Example
var ourArray = ["Stimpson", "J", ["cat"]];
var removedFromOurArray = ourArray.shift();
// removedFromOurArray now equals "Stimpson" and ourArray now equals ["J", ["cat"]].

// Setup
var myArray = [["John", 23], ["dog", 3]];

// Only change code below this line.
var removedFromMyArray = myArray.shift();
```

## Manipulate Arrays With unshift()
```js
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();

myArray.unshift(["Paul",35])
```

## Shopping List
```js
var myList = [["rice", 5] , ["bread", 6] , ["cake", 7], [ "quinoa", 9], ["potato", 20]];
```

## Write Reusable JavaScript with Functions
```js
function reusableFunction() {
  console.log("Hi World");
}

reusableFunction();
```

## 47.Passing Values to Functions with Arguments
```js
// Example
function ourFunctionWithArgs(a, b) {
  console.log(a - b);
}
ourFunctionWithArgs(10, 5); // Outputs 5

// Only change code below this line.
function functionWithArgs (a , b) {
console.log(a + b);
}
functionWithArgs (1 , 2);
functionWithArgs (7 , 9);
```
## 48. Global Scope and Functions
```js
// Declare your variable here


function fun1() {
  // Assign 5 to oopsGlobal Here
  
}

// Only change code above this line
function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
var myGlobal = 10;
function fun1() {
  oopsGlobal = 5;
}
```

## 49. Local Scope and Functions
```js
function myLocalScope() {
var myVar = 'use strict';
}
myLocalScope();
```

## 50. Global vs. Local Scope in Functions
```js
// Setup
var outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
  
  
  
  // Only change code above this line
  return outerWear;
}

myOutfit();
var outerWear = "T-Shirt";
function myOutfit() {
  var outerWear = "sweater";
  return outerWear;
}
myOutfit();
```

## 51. Return a Value from a Function with Return
```js
// Example
function minusSeven(num) {
  return num - 7;
}

// Only change code below this line
function timesFive (num) {
  return num * 5;
}
timesFive(5);
timesFive(2);
timesFive(0);


console.log(minusSeven(10));
```

## 52. Understanding Undefined Value returned from a Function
```js
// Example
var sum = 0;
function addThree() {
  sum = sum + 3;
}

// Only change code below this line



// Only change code above this line
var returnedValue = addFive();
function addFive() {
  sum = sum + 5;
}
```

## 53. Assignment with a Returned Value
```js
// Example
var changed = 0;

function change(num) {
  return (num + 5) / 3;
}

changed = change(10);

// Setup
var processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line
var processed = 0;
function processArg(num) {
  return (num + 3) / 5;
}
processed = processArg(7);
```

## 54. Stand in Line
```js
function nextInLine(arr, item) {
  // Your code here
    arr.push(item);
    return  arr.shift();   // Change this line
}

// Test Setup
var testArr = [1,2,3,4,5];

// Display Code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 10) ,testArr[4]); // Modify this line to test
console.log("After: " + JSON.stringify(testArr));
```

## 55. Understanding Boolean Values
```js
function welcomeToBooleans() {
return true;
}
```

## 56. Use Conditional Logic with If Statements
```js
// Example
function ourTrueOrFalse(isItTrue) {
  if (isItTrue) { 
    return "Yes, it's true";
  }
  return "No, it's false";
}

// Setup
function trueOrFalse(wasThatTrue) {

  // Only change code below this line.

    if (wasThatTrue) {
    return "Yes, that was true";
  }
  return "No, that was false";
}

  // Only change code above this line.
// Change this value to test
trueOrFalse(true);
```

## 57. Comparison with the Equality Operator
```js
// Setup
function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testEqual(12);
```

## 58. Comparison with the Strict Equality Operator
```js
// Setup
function testStrict(val) {
  if (val === 7) {// Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testStrict(10);
```

## 59. Practice comparing different values
```js
// Setup
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
compareEquality(10, "10")
```

## 60. Comparison with the Inequality Operator
```js
// Setup
function testNotEqual(val) {
  if (val != 99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testNotEqual(10);
```

## 61. Comparison with the Strict Inequality Operator
```js
// Setup
function testStrictNotEqual(val) {
  // Only Change Code Below this Line
  
  if (val !== 17) {

  // Only Change Code Above this Line

    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testStrictNotEqual(10);
```

## 62. Comparison with the Greater Than Operator
```js
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }
  
  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

// Change this value to test
testGreaterThan(10);
```

## 63. Comparison with the Greater Than Or Equal To Operator
```js
function testGreaterOrEqual(val) {
  if (val >= 20) {  // Change this line
    return "20 or Over";
  }
  
  if (val >= 10) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

// Change this value to test
testGreaterOrEqual(10);
```

## 64. Comparison with the Less Than Operator
```js
function testLessThan(val) {
  if (val < 25) {  // Change this line
    return "Under 25";
  }
  
  if (val < 55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

// Change this value to test
testLessThan(10);
```

## 65. Comparison with the Less Than Or Equal To Operator
```js
function testLessOrEqual(val) {
  if (val <= 12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }
  
  if (val <= 24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

// Change this value to test
testLessOrEqual(10);
```

## 66. Comparisons with the Logical And Operator
```js
function testLogicalAnd(val) {
  // Only change code below this line
  if (val >= 25 && val <= 50) {
      return "Yes";
  }

  // Only change code above this line
  return "No";
}

// Change this value to test
testLogicalAnd(10);
```

## 67. Comparisons with the Logical Or Operator
```js
function testLogicalOr(val) {
  // Only change code below this line

  if (val < 10 || val > 20 ) {

    return "Outside";
;
}

  // Only change code above this line
  return "Inside";
}

// Change this value to test
testLogicalOr(15);
```

## 68. Introducing Else Statements
```js
function testElse(val) {
  var result = "";
  // Only change code below this line

  if (val > 5) {
    result = "Bigger than 5";
  }

  else {
    result = "5 or Smaller";
  }
  
  // Only change code above this line
  return result;
}

// Change this value to test
testElse(4);
```

## 69. Introducing Else If Statements
```js
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }

  else if (val < 5) {
    return "Smaller than 5";
  }
  else {
      return "Between 5 and 10";
  }

}

testElseIf(7);
```

## 70. Logical Order in If Else Statements
```js
function orderMyLogic(val) {
  if (val < 5) {
    return "Less than 5";
  } else if (val < 10) {
    return "Less than 10";
  } else {
    return "Greater than or equal to 10";
  }
}

orderMyLogic(7);
```

## 71. Chaining If Else Statements
```js
function testSize(num) {
  // Only change code below this line
  if(num < 5) {
    return "Tiny";
  } else if (num < 10) {
 return "Small";
  } else if (num < 15) {
return "Medium";
  } else if (num < 20) {
return "Large";
  } else if ( num >= 20 ) {
    return "Huge";
    } else {
    return "Change Me"; }

}
  // Only change code above this line
// Change this value to test
testSize(7);
```

## 72. Golf Code
```js
var names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  if (strokes == 1) {
return "Hole-in-one!";
  } else if (strokes <= par - 2) {
     return "Eagle" ;
  } else if (strokes == par - 1) {
     return "Birdie" ;
  } else if (strokes == par) {
     return "Par" ;
  } else if (strokes == par + 1) {
     return "Bogey" ;
  } else if (strokes == par + 2) {
     return "Double Bogey" ;
  } else if (strokes >= par + 3) {
     return "Go Home!" ;
  } else {
     return "Change Me";
  }
}

golfScore(5, 4);
```
