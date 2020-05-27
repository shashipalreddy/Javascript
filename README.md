# Javascript

## Introduction

1. Javascript is 
      - lightweight
      - cross-platform
      - object-oriented programming language
2. Javascript is core technology of web development.
3. Javascript is traditionally used as a client-side.
4. Javascript has **5** datatypes:
      - Number
      - String
      - Boolean
      - Undefined
      - Null
5. Javascript has dynamic typing.
6. Dynamic typing is nothing but datatypes are automatially assigned to variables.
7. To print something to a console use  
    `console.log('Hello World!);`
8. Script file can be added in 2 ways
      - inline script: you can directly add the script in the same file
                        `<script> console.log("Hello world!"); </script>`
      - external script: we can also create the javascript file externally
                          `console.log('Hello World!);`  
                         and add them to the html file using script
                          `<script src="script.js"></script>`  
---
## Comment in Javascript
- we have 2 different kind of javascript comments  
        1. single line comment: `//Single Line Comments`  
        2. Multiline Comments: `/* multiple line comments */`
---
## Truthy and Falsy Values
- A truthy value is considered to be true when encountered in a boolean context.
- All values are truthy unless they are defined as falsy `Except: undefined, Null, 0, '', NaN`
---
## Comparison Operator
- Javascript has both strict and type-converting comparisons.  
- A strict comparison (e.g., ===) is only true if the operands are of the same type and the contents match.   
      ` E.g: console.log( 1 === 1) //Output: true;  console.log( 1 === '1') //Output: false; `  
- A type-converting comparisons (e.g., ==) will convert the operand to same type before making the comparison.  
      ` E.g: console.log( 1 == 1) //Output: true;  console.log( 1 == '1') //Output: true; `  
- type-converting comparison will do type coercion.  
- Type coercion is the process of converting value from one type to another (such as string to number, object to boolean, and so on). 
- Always use the "===" strict operator to avoid the type coercion.

---
## Functions
- function function_name(arguments)
- DRY principle Don't repeat yourself  
            `// Function Declaration: function WhatDoYouDO(job, firstName) `  
            `// Funtion Expression: var WhatDoYouDO = function(job, firstName) `

---
## Arrays
Collection of variables of different datatypes.  
> To add elements to an array
>
>>      Push: will add elements at the end of the array.  
>>      unshift: will add elements at the beginning of the array.  
> To remove elements from the array.  
>
>>      Pop: will remove the elements from the end of the array.  
>>      shift: will remove the elements from the beginning of the array.  

