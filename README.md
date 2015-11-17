# go-sct [![GoDoc](https://godoc.org/github.com/d4l3k/go-sct?status.svg)](https://godoc.org/github.com/d4l3k/go-sct)

A color temperature setting library and CLI that operates in a similar way to f.lux and Redshift.

```sh
go install github.com/d4l3k/go-sct/sct

sct 3000 // Temperature must be 1000-10000.
```
This requires Go and the Xrandr library.

## Credit
This is a rewrite of [sct](http://www.tedunangst.com/flak/post/sct-set-color-temperature) in Go. Credit goes to him for figuring out how to do this.