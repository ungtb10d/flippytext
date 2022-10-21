# FlippyText [![Build Status](https://travis-ci.org/blcksec/flippytext.svg?branch=master)](https://travis-ci.org/blcksec/flippytext) [![Coverage Status](https://coveralls.io/repos/github/blcksec/flippytext/badge.svg?branch=master)](https://coveralls.io/github/blcksec/flippytext?branch=master) [![GoDoc](https://godoc.org/github.com/blcksec/flippytext?status.svg)](https://godoc.org/github.com/blcksec/flippytext)

FlippyText is a Go library for printing animated text one character at a time.

![Screencap](screencap.gif)

## Install

```
go get github.com/blcksec/flippytext
```

## Example 

```go
import "github.com/blcksec/flippytext"

func main() {
		flippytext.New().Write("hello world")
}
```
