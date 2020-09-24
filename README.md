# go-rapi

Rithmic version: 0.39.0.0

This library contains Rithmic APIs in Go.

Files are compiled using Rithmic's official protobuf files.

## Quick Start
#### Create `hello` directory, cd `hello` directory
```bash
mkdir hello
cd hello
```

#### Init module
```bash
go mod init
```

#### Download and install
```bash
go get github.com/vacwm/go-rapi
```

#### Import and run
```go
package main

import "github.com/vacwm/go-rapi"

func main() {
	var templateID *int32
	*templateID = 10
	var requestLogin := rti.RequestLogin{TemplateId: templateID}
  ...
}
```
