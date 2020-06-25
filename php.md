## PHP

### Hello World:
```php
echo('Hello World');
```

### Variables and constants:
```php
$foo = "bar";
define("BAR", "foo");
```

### Data types:
```php
$name = 'John';
$age = 30;
$rating = 7.5;
$isBlue = True;
$x = NULL;
$fruits = ['banana', 'apple', 'watermelon'];
```

### Control flow statements:
#### if
```php
if ($x > 3 || $x < 3) {
    ...
}
```

```php
if ($x > 2 && $x < 4) {
    ...
}
```

```php
if ($color === 'green') {
    ...
} elseif ($color === 'yellow') {
    ...
} else {
    ...
}
```

#### for
```php
for ($i = 0; $i <= 10; $i++) {
    ...
}
```

#### foreach
```php
foreach ($todos as $todo) {
    ...
}
```

#### while
```php
$x = 0;
while ($x <= 10) {
    ...
    $x++;
}
```

#### switch
```php
switch ($x) {
    case 1:
        ...
        break;
}
```

### Functions
```php
function sum($x, $y) {
    return $x + $y;
}
```

### Classes
```php
class Person {
    function __construct(firstName, lastName) {
        $this->firstName = firstName;
        $this->lastName = lastName;
    }

    function getFullName() {
        return $this->firstName . " " . $this->lastName;
    }
}

$person1 = new Person('Jhon', 'Doe');

echo($person1->getFullName());
```

