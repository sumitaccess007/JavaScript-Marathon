**Table of Contents**
[Is JavaScript a Compiled or Interpreted Language ?]
[What you can do with JavaScript ?]
[What does Normalization mean in JavaScript ?]


## Is JavaScript a Compiled or Interpreted Language ?
- Documentation contains a good explain for this popular question.
- [Answer-1](https://softwareengineering.stackexchange.com/questions/136993/interpreted-vs-compiled-a-useful-distinction/) 
- [Answer-2](https://stackoverflow.com/questions/1326071/is-java-a-compiled-or-an-interpreted-programming-language)



## What you can do with JavaScript ?
- It is not anymore just a language with in the browser.
- We can make mobile apps with Javascript.
- We can develop a very good backend in Javascript.
- We can also build Desktop apps in Javascript.
- We can also use Javascript to build APIs.
- We can also use this language directly into the cloud itself.
- Also we can use some type safety features in TypeScript.
- We can also use Javascript in Machine Learning, Data Structures and Algorithms and Blockchain field.
- It can also be used to make libraries and frameworks as well.

## What does Normalization mean in JavaScript ?


<br>

#### Basic Declaration of Variables in Javascript
Always use **let** for declaring the variables in Javascript. **let** is simply a variable which can be changed later on.

Example -
```
let username= "Sumit Sharma"
var username = "Sumit Sharma"	// This is not a recommended way to declare variables
const username = "Sumit Sharma"	// Use this for declaring the constants
```

Example -
```
let userMobile = 9876543102
let isLoggedIn = true
```

Example -
```
let testMeLet
var testMeVar

console.log(testMeLet);
console.log(testMeVar);
```

#### Print to console in Javascript
```
console.log("Hello JavaScript");
```

#### Lexical Structure
- Elementary rule for language specification.

#### TEXT
Variables declared below are all different. Follow some specific habit of declaring the variables like CamelCase or something else.
Javascript is a case sensitive language.
```
var ONLINE
var online
var Online
var oNLINE
var 1_online	// Not allowed, as variable could not start numerical literal
var $1_online
```

#### Comments
Command - CTRLM + /

Example -
```
// Comment-1
/*
Comment-2
*/
```

#### Literals -
```
2323
23.5
"String type one"
'String type two'
"String type 'Inside' one"
'String type "Inside" one'
true
false
null
undefined	// normally it is not considered as literal
```

#### Reserved Keywords -
```
if
for
function
let
new
return
enum
implements
interface
package
private
protected
public
... and Many More ...
... Also Some Future Reserved Keywords
```

#### Special Unicode Characters -
Do not use such characters while developing the applications.
Unicode characters - try always writing them in **\u** format

Javascript always assumes that the source code we are writing has been normalized.

Example -
These both looks exactly same but their unicode is different.
```
const café = 1;
const café = 2;
console.log(café);	// No Error, Not Undefined, It prints out 1 - Copied first variable name
console.log(café);	// No Error, Not Undefined, It prints out 2 - Copied second variable name
```

Example -
```
var smiley = "\u00E9"
var smiley = "\u0301"
```

#### When to use semicolon
It does not matter if you write semicolons or not, but make a consistency in your code. So its all about what do you want to do.

Example -
```
let username= "Sumit Sharma"
let username= "Sumit Sharma";
```

Example -
```
console.log("Hey")
```

Example -
```
let gameScore = 289
console.log(gameScore);
```

Example -
```
let
gameScore
=
289
console.log(gameScore);
```

Example -
```
let y = x + f
(a+b).toString()
// It was supposed to be like this let y = x + f(a+b).toString()
```

Example -
```
return
true;
// It is assumed as return; true;
```

Example -
```
let score = 0
; [score, score+3, score+5].forEach(console.log)
```
