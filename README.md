[![GoDoc](https://godoc.org/github.com/Ronmi/conenv?status.svg)](https://godoc.org/github.com/Ronmi/conenv)

Extensible (and secure if needed) way to load struct from environment variables.

It aims to be feature-rich. If you just want to load plain values from environment variables into struct, you might want to give [caarlos0/env](https://github.com/caarlos0/env) a try: lightweight tool focus on loading plain value from envvar.

# Synopsis

See [package example in godoc](https://godoc.org/github.com/Ronmi/conenv#ex-package).

# Tool

There is a command line tool: convenvtool.

To install it, simply

```bash
go get -u github.com/Ronmi/conenv/cmd/conenvtool
```

It can

* Generate RSA/DSA keys.
* Encrypt your data with 3DES/AES/RSA.
* Generate signature with DSA.
* Verify generated cipher text and signature.

# License

WTFPL

# TODO

* Test against errorneous data.
