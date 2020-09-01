# JS is Easy

you can add script in html file using

##### `<script src="index.js"></script>`

##### `<script>something</script>` 
or call script file using `src="file.js"`

### Check in browser using `Ctrl+Shift+i` or on CLI using 'npm index.js'

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
#npm output `1`