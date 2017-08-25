# simplelogger
A Really simple custom message logger in Go

```
package main
import "github.com/awmpietro/simplelogger"

func main(){
  Trace.Println("I ahve something standard to say")
  Info.Println("Special information")
  Warning.Println("There is something you need to know about")
  Error.Println("Something has failed")
}
```
