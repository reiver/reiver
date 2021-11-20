# reiver Go

**reiver Go** is a list of amazing libraries, software, and guides created by **reiver** for the Go programming language.

## Contents

* [Casting](#casting)
* [Color](#color)
* [Error Handler](#error-handler)
* [JSON](#json)
* [Logging](#logging)
* [Maps](#maps)
* [Natural Language Processing](#natural-language-processing)
* [Networking](#networking)
* [Unicode](#unicode)
* [Unique IDs](#unique-ids)

## Casting

* [go-cast](https://github.com/reiver/go-cast) — tools for safely converting from one type to another, without information loss.

## Color

* [go-rgba32](https://github.com/reiver/go-rgba32) — a type that represents an RGBA color with 8-bits per color channel (stored as a slice rather than a struct), for a total of 32-bits altogether, that seamlessly works with Go's built-in `"image"`, `"image/color"`, and `"image/draw"` packages.

## Error Handler

* [go-fck](https://github.com/reiver/go-fck) — tools to create and manipulate errors. one thing to notice is that `fck.Error` errors can be a Go `const`.

## JSON

* [go-jsonio](https://github.com/reiver/go-jsonio) — tools for working with JSON I/O. this supplements Go's built-in "encoding/json" package.

## Logging

* [go-flog](https://github.com/reiver/go-flog) — structured and formatted logging.

## Maps

* [go-mapstringinterface](https://github.com/reiver/go-mapstringinterface) — tools for working with Go's `map[string]interface{}` type.

## Natural Language Processing

* [go-porterstemmer](https://github.com/reiver/go-porterstemmer) — a native Go clean room implementation of the Porter Stemming algorithm.

## Networking

* [go-hg](https://github.com/reiver/go-hg) — provides ☿ Mercury Protocol client and server implementations.
  * [hydrargyrum](https://github.com/reiver/hydrargyrum) — a  ☿ Mercury Protocol server that uses **go-hg**
* [go-telnet](https://github.com/reiver/go-telnet) — TELNET and TELNETS client and server implementations, in a style similar to the "net/http" library that is part of the Go standard library, including support for "middleware"; TELNETS is secure TELNET, with the TELNET protocol over a secured TLS (or SSL) connection.

## Unicode

* [go-utf8s](https://github.com/reiver/go-utf8s) — tools for working with Unicode encoded as UTF-8, for the Go programming language.

## Unique IDs

* [go-xim](https://github.com/reiver/go-xim) — quazi‐ monotonically‐increasing unique‐identifiers, whose serialized form are safe to use as file‐names, and directory‐names, and where lexical-ordering of the xim-id (under Unicode & ASCII) is in-practice also temporal-ordering of the xim-id (almost all of the time)
  * [xim-id](https://github.com/reiver/xim-id) — a program using **go-xim**
