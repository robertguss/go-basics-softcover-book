# Variables

```go
package main

import (
  "fmt"
)

func main() {
  age := 47
  fmt.Printf("%v, %T\n", age, age)

  var ageString string = string(age)
  fmt.Printf("%v, %T", ageString, ageString)
}


/*
  The result of the code above is:
  14, int
*/
```
