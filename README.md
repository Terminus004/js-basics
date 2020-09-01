# JS is Easy

you can add script in html file using

##### `<script src="index.js"></script>`

##### `<script>something</script>` 
or call script file using `src="file.js"`

### Check in browser using `Ctrl+Shift+i` or on CLI using 'node index.js'

### In index.js version 0.0.1
// Comment

```console.log('Hello World'); //creates a console message Hello World

let name = 'Tracer007'; //creates a variable name`

console.log(name); //name variable is called and shown in console


// variable name ----=
// Cannot be a reserved keyword 'name'
// Should be meaningful
// Cannot start with a number (1name)
// Cannot contain a space or hyphen (~)
// 'let firstName' is camel notation where 'firstName' is case-sensitive

let firstName;
```

### In index.js version 0.0.2(Constant)
```
let interestRate = 0.3;
interestRate = 1; // Updates interestRate value from 0.3 to 1
console.log(interestRate);
```
# node output `1`

But this will create all types of bugs in future as `var` i.e. variable can be changed so we use `const` i.e. constant.

```
const interestRate = 0.3;
interestRate = 1; // Will not update instead we get an error. So we can't change it.
console.log(interestRate);
```
# node output 
* ```
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