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
