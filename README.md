# JS is Easy

you can add script in html file using

##### `<script src="index.js"></script>`

##### `<script>something</script>` 
or call script file using `src="file.js"`

#### Check in browser using `Ctrl+Shift+i` or on CLI using 'node index.js'

## In index.js version 0.0.1
// Comment i.e. not executed in code

```console.log('Hello World'); //creates a console message Hello World

let name = 'Tracer007'; //creates a variable name

console.log(name); //name variable is called and shown in console


// variable name ----=
// Cannot be a reserved keyword 'name'
// Should be meaningful
// Cannot start with a number (1name)
// Cannot contain a space or hyphen (~)
// 'let firstName' is camel notation where 'firstName' is case-sensitive

let firstName;
```

## In index.js version 0.0.2(Constant)
```
let interestRate = 0.3;
interestRate = 1; // Updates interestRate value from 0.3 to 1
console.log(interestRate);
```

##### node output
`1`


#### But this will create all types of bugs in future as `var` i.e. variable can be changed so we use `const` i.e. constant where the value is not changed frequently.

```
const interestRate = 0.3;
interestRate = 1; // Will not update instead we get an error. So we can't change it.
console.log(interestRate);
```
##### node output 
```
interestRate = 1;
             ^

TypeError: Assignment to constant variable.
    at Object.<anonymous> (/home/trinity/js-basics/index.js:2:14)
    at Module._compile (internal/modules/cjs/loader.js:1137:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1157:10)
    at Module.load (internal/modules/cjs/loader.js:985:32)
    at Function.Module._load (internal/modules/cjs/loader.js:878:14)
    at Function.executeUserEntryPoint [as runMain] (internal/modules/run_main.js:71:12)
    at internal/main/run_main_module.js:17:47
```

## In index.js version 0.0.3

#### Now we will see types of variables
##### It's of two types 1. `Primitive` 2. `Reference Types`
##### In Primitive
we have

```
// primitive/Value Types
let name = 'Tracer007'; // String Literal
let age = 20; // Number Literal
let isApproved = false; // Boolean Literal
let firstName = undefined; // Undefined Or
let firstName;
let selectedColor = null; // Null
```

## In index.js version 0.0.3.1

#### Dynamic Typing
##### We have 2 types od prog. languages 1. Static 2. Dynamic
Static
```
string name = 'John'; // It means the type of variable can't be changed in progam it will always be string
```

Dynamic
```
let name = 'John'; // Variable type can be changed in run time
```

Let's check Console for an example Ctrl+Shift+I

Using typeof we can find type of variable before and after changing value
```
typeof name
"string"
name = 1;
1
typeof name
"number"
typeof age
"number"
age = 20.4
20.4
typeof age
"number"
typeof isApproved
"boolean"
typeof firstName
"undefined"
typeof selectedColor
"object"
```
Also javascript treats number and floating point number same

## In index.js version 0.0.4
#### 2. Reference Types

It contains Object 
##### Object
