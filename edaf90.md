### Types and Values
The different data types existing in JavaScript/TypeScript is the following:

**- String:**
In order to create a string value you enclose it with either ' or ". Strings are immutable, this means you can't change an initiated string value but instead you create a new string value. Note however, a String object which you create with the String() constructor, is mutable. Here is some example code:
```
let string0 = "This is a string";
let string1 = 'This is also a string';
let stringObject = new String("This is a string in a String Object");
stringObject.newString = "This is a new string property in stringObject";
stringObject.newString = "This creates a new string value in the property newString in stringObject";
```

Template literals are string literals allowing embedded expressions.
```
let string2 = 'This is a string with an ${expression} in it'
```

An empty string "" will result in a falsy value. All other strings will result in a truthy value.

**- Number:**
You can use common operators with numbers.
```
let number0 = 3;
let number1 = 5;
let number2 = number0 + number1; //number2 becomes 8
```

You can convert a string into a number.
```
let stringNumber = "3";
let justNumber = +stringNumber;
```

You can also conver a value to a boolean, if value parameter is omitted or is 0, -0, null, false, NaN or undefined will become false.
```
let number0 = 1;
!!number0; //This is now a boolean value
```

**- Boolean:**
Boolean value can be either true or false. Also, as mentioned, values can be either truthy or falsy. The values: "" (empty string), 0, -0, NaN (invalid number), null, undefined, false are interpreted as false. All other values are true.

**- Null:**


**- Undefined**


**- Object**


**- Symbol**
