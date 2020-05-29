## Go

### Hello World:
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

### Variables and constants:
```go
var foo = "bar";
var foo, bar = "bar", "foo"
var foo bool = true
var foo bool
const Foo = "bar"

func main() {
    foo := "bar"
}
```

### Data types:
```go

var {
    name string = 'John'
    age int = 30
    rating1 float64 = 7.5
    isBlue bool = true
}
```
There are other types, see: https://go-tour-br.appspot.com/basics/11

### Control flow statements:
#### if
```go
if x > 3 || x < 3 {
    ...
}
```

```go
if x > 2 && x < 4 {
    ...
}
```

```go
if z := 2; x > z && x < z+2 {
    ...
}
```

```go
if color === 'green' {
    ...
} else color === 'yellow' {
    ...
} else {
    ...
}
```

#### for
```go
for i := 0; i <= 10; i++ {

}
```

#### while
```go
for i <= 10 {

}
```
Yes, this is not a mistake. The while in Go is just that.

#### switch
```go
switch x {
    case 1:
        ...
    case 2:
        ...
    default:
        ...
}
```
