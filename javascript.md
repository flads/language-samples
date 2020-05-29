## JavaScript

### Hello World:
```javascript
console.log('Hello, World!');
```

### Variables and constants:
```javascript
var foo = 'bar';
let foo = 'bar';
const foo = 'bar';
```

### Data types:
```javascript
const name = 'John';
const age = 30;
const rating = 7.5;
const isBlue = true;
const x = null;
const y = undefined;
const fruits = ['banana', 'apple', 'watermelon'];
```

### Control flow statements:
#### if
```javascript
if (x > 3 || x < 3) {
    ...
}
```

```javascript
if (x > 2 && x < 4) {
    ...
}
```

```javascript
if (color === 'green') {
    ...
} else if (color === 'yellow') {
    ...
} else {
    ...
}
```

#### for
```javascript
for (let i = 0; i <= 10; i++) {
    ...
}
```

```javascript
for (let todo of todos) {
    ...
}
```

#### while
```javascript
let x = 0;
while (x <= 10) {
    ...
    x++;
}
```

#### switch
```javascript
switch (x) {
    case 1:
        ...
        break;
    case 2:
        ...
        break;
    default:
        ...
        break;
}
```

### Functions
```javascript
function sum(x, y) {
    return x + y;
}
```

#### arrow function
```javascript
const sum = (x, y) => {
    return x + y;
}
```

### Classes
```javascript
class Person {
    constructor(firstName, lastName) {
        this.firstName = firstName;
        this.lastName = lastName;
    }

    getFullName() {
        return `${this.firstName} ${this.lastName}`;
    }
}

const person1 = new Person('Jhon', 'Doe');

console.log(person1.getFullName());
```

