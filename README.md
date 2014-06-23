# Gosseract-OCR [![Build Status](https://travis-ci.org/otiai10/gosseract.svg?branch=develop)](https://travis-ci.org/otiai10/gosseract)

[Tesseract-OCR](https://code.google.com/p/tesseract-ocr/) command wrapper for Golang

# example
```go
package main

import (
	"fmt"
	"github.com/otiai10/gosseract"
)

func main() {
    // This is the simlest way :)
    out := gosseract.Must("your/img/file.png")
    fmt.Println(out)
}
```

# dependencies

- [tesseract-ocr](https://code.google.com/p/tesseract-ocr/)#3.02~
- [mint](https://github.com/otiai10/mint) to simplize tests

# test
```sh
go test ./...
```

# issues
- https://github.com/otiai10/gosseract/issues?state=open
