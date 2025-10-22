<<<<<<< HEAD
# Black Hat Go: Go Programming for Hackers and Pentesters
Code Snippets from the Book "Black Hat Go"
=======
**Cross-compiling**

*Constraints*

```
$ GOOS="linux" GOARCH="amd64" go build <file>.go 
```

Produces a ELF 64-Bit binary for Linux

*go doc command*

```
$ go doc <function/library>
```

Prints more information about a function/library

*go get*

```
$ go get <package_name>
```

```go
package main

import (
    "fmt"
    "net/http"
    "github.com/stacktitan/ldapauth" (1)
)
```
(1): Needs to be downloaded via ```$ go get github.com/stacktitan/ldapauth```
>>>>>>> bdd2761 (added README)
