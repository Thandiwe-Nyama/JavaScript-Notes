# JavaScript-Notes

*JAVASCRIPT VARIABLES*
Type of values- numbers, strings of text and booleans.

Javascript defines two trivial data type: null and undefined
Javasript does not make a distinction between integer values and floating-point values.
All numbers in javascript are represented as floating-point values.
Javasript represents numbers using the 64-bit floating-point format defined by the IEEE 754 standard.

Var- declare a variable 
   -It can also declare multiple variable.

   when you store a value in a variable is called Variable Initialization.
   JavaScript is an untyped language.
   JavaScript variable caon hold a value of any data type.
   The value type of a variable can change during the excution of a program and javascrpt takes care of it automatically.
   *Comment
   *Vatiable
   *Operators
   *Assignment
   *Single-line comment are written with forward slashes(\)
   *All characters immediately following the // syntax until the end of the line will be ignored by javascript'
   *Variable can be thought of as named containers.



  STRINGS AND ARRAYS
  strings is a sequence of one or more characters that may consist of letters, numbers, or symbols.
  Strings are primitive data type and immutable, they are unchanging.

  Storing a string in avariable using the keywords var, const or let.
  string concatenation means joining two or more string together (+)
  back slash(\) is used to escape character.

  ARRAYS- Object allows you to store keyed collections of values.
  SYNTAX: let arr =new Array();
          let arr = [];

          
  METHOD POP/PUSH, SHIFT/UNSHIFT
 A queue is one of the most common uses of an array.
*Push appends an element to the end.
*Shift get an element from the beggining .
*Push adds an element to the end.
*Pop atkes element from the end.

ARRAYS AS A DEQUE
*Push- add items 
*Pop() removes the element from the end and return it.
*Shift() removes element from beggining and returnds it.
*Unshift add items to the beggining.

LOOP OVER
*For (let i=0; i<arr.length; i++i) 
*for (let items of arr)
*For (let i in arr)
We use For---of loop to compare arrays item-by-item.


FUNCTIONS
A function is a group of reusable code which can be called anywhere in your program.
Function allow a programmer to divid3e a big program into a number of small and manageable function.
E.G function functionName(Parameter-list) {
    statement 
    } Function declaration

FUNCTION EXPRESSION
const varName = function(parameter-list) {
statement
};

const myFunc = Function(x,y) {
return x+y;
};

CALLING FUNCTION

<script type = "text/javascript">
function sayHello() {
alert("Hello there!");
}
</script>

FUNCTION PARAMETERS
<script type = "text/javascript">
function sayHello(name, age) {
document.write(name +"is" + age + "years old"); }
</script>

BOOLEANS
Booleans are values that can be only one of two things true or false.
E.G Var kitchenLights = false;
kitchenLight = true
kitchenLights;
output = true

INTRODUCTION TO HTML, CSS AND JAVASCRIPT

HTML (HyperText Markup Language): HTML is the standard markup language used to create the structure and content of web pages. It utilizes tags to define different elements like headings, paragraphs, images, and links.

CSS (Cascading Style Sheets): CSS is a style sheet language used for describing the presentation of HTML documents. It allows for the customization of the appearance of HTML elements, including layout, colors, fonts, and more.

JavaScript: JavaScript is a programming language that enables interactive and dynamic behavior on web pages. It can manipulate HTML and CSS, respond to user actions, validate form inputs, create animations, and enhance the functionality of a website.

TYPE CONVERSIONS
Type conversions, also known as type casting or coercion, are processes of changing the data type of a value from one type to another. There are two main types: implicit and explicit.

Implicit Type Conversion: Automatic conversion by the programming language without explicit instruction. For example, when adding an integer and a float, the integer may be converted to a float.

Explicit Type Conversion: Manual conversion performed by the programmer using built-in functions or operators. For instance, using functions like int(), float(), str() to convert between types.

Common conversions include:

String to Number: Converting a string to an integer or float.
Number to String: Converting a number to a string.
Boolean Conversion: Converting other data types to boolean values.

NUMERIC CONVERSIONS

Numeric conversion is the process of converting between different numeric data types, such as integers, floats, and strings representing numbers. Here's a concise summary:

Integer to Float: Convert an integer to a floating-point number, often used in division operations or when dealing with non-integer values.

Float to Integer: Convert a floating-point number to an integer, truncating the decimal part.

String to Numeric: Convert a string representing a number to an actual numeric value, commonly used for extracting numerical data from user inputs or external sources.

Numeric to String: Convert a numeric value to its string representation, useful for displaying numeric values as part of strings or formatting output.

Type-specific Conversion Functions: Some languages provide specific functions for numeric conversions, such as parseInt() and parseFloat() in JavaScript.
 
