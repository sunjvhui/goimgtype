# goimgtype


Return the type of the image

### How to install
```go
go get github.com/sunjvhui/goimgtype
```

### How to use
```go
package main

import (
	"fmt"
	"github.com/sunjvhui/goimgtype"
)

func main() {
  fmt.Println(goimgtype.Get("./test.jpg"))
}
```