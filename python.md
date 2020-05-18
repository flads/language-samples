## Python

### Hello World:
```python
print("Hello, world!")
```

### Variables and constants:
```python
foo = "bar";
BAR = "foo";
```

### Data types:
```python
name = "John";
age = 30;
rating = 7.5;
isBlue = True;
x = None;
fruits = ["banana", "apple", "watermelon"];
```

### Objects:
```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
```

### Control flow statements:
#### if
```python
if (x > 3 or x < 3):
    print("The value of 'x' is not 3!")
```

```python
if (x > 2 and x < 4):
    print("The value of 'x' is 3!")
```

```python
if (color == "green"):
    print("Color is green!")
elif (color == "yellow"):
    print("Color is yellow!")
else:
    print("Color was not detected!")
```

#### for
```python
for x in range(10):
    print(x)
```

```python
for todo in todos:
    print(todo)
```

#### while
```python
x = 0
while x <= 10:
    print("The value of 'x' is %(value)5d" %{"value": x})
    x+=1
```

### Functions
```python
def sum(x, y):
    return x + y
```

### Classes
```python
class Person:
    def __init__(self, firstName, lastName):
        self.firstName = firstName;
        self.lastName = lastName;

    def getFullName(self):
        return ("%(firstName)s %(lastName)s" %{"firstName": self.firstName, "lastName": self.lastName})

person1 = Person('Jhon', 'Doe')

print(person1.getFullName())
```

