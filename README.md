# go-rcv

Package **rcv** provides tools for _receiving_ input; including reading a line from the CLI.

## Documention

Online documentation, which includes examples, can be found at: http://godoc.org/github.com/rainmanh/go-rcv

[![GoDoc](https://godoc.org/github.com/rainmanh/go-rcv?status.svg)](https://godoc.org/github.com/rainmanh/go-rcv)

## Example

Here is an example usage:
```Go
var line string

rcv.Readln(&dst)

fmt.Printf("LINE: %q\n", line)
```

## Import

To import package **rcv** use `import` code like the following:
```
import "github.com/rainmanh/go-rcv"
```

## Installation

To install package **rcv** do the following:
```
GOPROXY=direct go get github.com/rainmanh/go-rcv
```

## Author

Package **rcv** was written by [Charles Iliya Krempeaux](http://rainmanh.link)
