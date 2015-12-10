
# tests
    import "github.com/coralproject/shelf/pkg/tests"

Package tests provides the generic support all tests require.





## Variables
``` go
var Failed = "\u2717"
```
Failed is a unicode codepoint for a check X mark.

``` go
var Success = "\u2713"
```
Success is a unicode codepoint for a check mark.


## func DisplayLog
``` go
func DisplayLog()
```
DisplayLog writes the logdash data to standand out, if testing in verbose mode
was turned on.


## func Init
``` go
func Init()
```
Init is to be runned once. It initializes the necessary logs and mongodb
connections for testing.


## func ResetLog
``` go
func ResetLog()
```
ResetLog resets the contents of logdash.









- - -
Generated by [godoc2md](http://godoc.org/github.com/davecheney/godoc2md)