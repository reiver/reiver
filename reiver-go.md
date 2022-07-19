# reiver Go

**reiver Go** is a list of amazing libraries, software, and guides created by **reiver** for the Go programming language.

## Contents

* [Binary-To-Text Encoding](#binary-to-text-encoding)
* [Byte](#byte)
* [Casting](#casting)
* [Color](#color)
* [Content Addressing](#content-addressing)
* [Counting](#counting)
* [Database](#database)
* [Error Handler](#error-handler)
* [Iterators](#iterators)
* [JSON](#json)
* [Logging](#logging)
* [Maps](#maps)
* [Money](#money)
* [Natural Language Processing](#natural-language-processing)
* [Networking](#networking)
  * [HTTP](#http)
* [Numbers](#numbers)
* [Porting](#porting)
* [Stream Processing](#stream-processing)
* [String Formatting](#string-formatting)
* [Supervision Tree](#supervision-tree)
* [Testing](#testing)
* [twtxt](#twtxt)
* [Unicode](#unicode)
* [Unique IDs](#unique-ids)
* [Video](#video)

## Binary-To-Text Encoding

* [go-bravo16](https://github.com/reiver/go-bravo16) — a more (human) safe base-16 binary-to-text encoding, and decoding; brave16 is an alternative to hexadecimal.
* [go-caret](https://github.com/reiver/go-caret) — encodes, and decodes caret text (i.e., where ASCII control codes are in caret notation) into UTF-8 text (which may also be ASCII text).

## Byte

* [go-byteliteral](https://github.com/reiver/go-byteliteral) — binary number literals for Go's byte type; including binary literals. note that Go 1.13 added binary literals, which makes this package obsolete.

## Casting

* [go-cast](https://github.com/reiver/go-cast) — tools for safely converting from one type to another, without information loss.

## Color

* [go-palette2048](https://github.com/reiver/go-palette2048) — a type that represents a color palette of 256 RGBA color with 8-bits per color channel, for a total of 2048-bits altogether, that seamlessly works with Go's built-in `"image"`, `"image/color"`, and `"image/draw"` packages.
  * [go-palette2048_gb](https://github.com/reiver/go-palette2048_gb)
  * [go-palette2048_greer](https://github.com/reiver/go-palette2048_greer)
  * [go-palette2048_gruvbox](https://github.com/reiver/go-palette2048_gruvbox)
  * [go-palette2048_html3](https://github.com/reiver/go-palette2048_html3)
  * [go-palette2048_lospec500](https://github.com/reiver/go-palette2048_lospec500)
  * [go-palette2048_nes](https://github.com/reiver/go-palette2048_nes)
  * [go-palette2048_rkbv](https://github.com/reiver/go-palette2048_rkbv)
  * [go-palette2048_solarized](https://github.com/reiver/go-palette2048_solarized)
  * [go-palette2048_tia](https://github.com/reiver/go-palette2048_tia)
* [go-rgba32](https://github.com/reiver/go-rgba32) — a type that represents an RGBA color with 8-bits per color channel (stored as a slice rather than a struct), for a total of 32-bits altogether, that seamlessly works with Go's built-in `"image"`, `"image/color"`, and `"image/draw"` packages.

## Content Addressing

* [go-hashuri](https://github.com/reiver/go-hashuri) — parses Hash URIs.

## Counting

* [go-mjrty](https://github.com/reiver/go-mjrty) — implementation of the mjrty algorithm; which igures out what is the majority of a sequence of items in a single pass, in O(n) time and O(1) space -- in linear time complexity and constant space complexity. this makes the mjrty algorithm suitable for some types of data streaming.

## Database

* [go-pqerror](https://github.com/reiver/go-pqerror) — a helper library that provides constants for the Postgres Error Codes, to be used with the Golang Postgres driver.
* [go-shunt](https://github.com/reiver/go-shunt) — enables you to create "middleware" for the the "database/sql" package.

## Error Handler

* [go-fck](https://github.com/reiver/go-fck) — tools to create and manipulate errors. one thing to notice is that `fck.Error` errors can be a Go `const`; this can be considered a replacement for `errors.New()` and `fmt.Errorf()`
* [go-errhttp](https://github.com/reiver/go-errhttp) — provides errors that make dealing with HTTP response errors easier.
* [go-manyerrors](https://github.com/reiver/go-manyerrors) — an error type that contains a list of errors.
* [go-pqerror](https://github.com/reiver/go-pqerror) — a helper library that provides constants for the Postgres Error Codes, to be used with the Golang Postgres driver.

## Iterators

* [go-iter](https://github.com/reiver/go-iter) — provides tools for creating, normalizing, and working with iterators.

## JSON

* [go-jsonio](https://github.com/reiver/go-jsonio) — tools for working with JSON I/O. this supplements Go's built-in "encoding/json" package.

## Logging

* [go-log](https://github.com/reiver/go-log) — structured and formatted logging.
* [go-loggers](https://github.com/reiver/go-loggers) — useful tools for dealing with loggers.

## Maps

* [go-mapstringinterface](https://github.com/reiver/go-mapstringinterface) — tools for working with Go's `map[string]interface{}` type.

## Money

* [go-money](https://github.com/reiver/go-money) — deals with money in a type safe way, including parsing from strings.

## Natural Language Processing

* [go-porterstemmer](https://github.com/reiver/go-porterstemmer) — a native Go clean room implementation of the Porter Stemming algorithm.

## Networking

* [go-hg](https://github.com/reiver/go-hg) — provides ☿ Mercury Protocol client and server implementations.
  * [hydrargyrum](https://github.com/reiver/hydrargyrum) — a  ☿ Mercury Protocol server that uses **go-hg**
* [go-telnet](https://github.com/reiver/go-telnet) — TELNET and TELNETS client and server implementations, in a style similar to the "net/http" library that is part of the Go standard library, including support for "middleware"; TELNETS is secure TELNET, with the TELNET protocol over a secured TLS (or SSL) connection.

### HTTP

* [go-errhttp](https://github.com/reiver/go-errhttp) — provides errors that make dealing with HTTP response errors easier.
* [go-modhandler](https://pkg.go.dev/github.com/reiver/go-modhandler) — deals with conditional GETs by sending out a "Last-Modified" HTTP response header, and properly dealing with a "If-Modified-Since" HTTP request header.

## Numbers

* [go-numeric](https://github.com/reiver/go-numeric)

## Porting

* [go-php](https://github.com/reiver/go-php) — implements functions and classes familiar to PHP developrs in Go.

## Stream Processing

* [go-mjrty](https://github.com/reiver/go-mjrty) — implementation of the mjrty algorithm; which igures out what is the majority of a sequence of items in a single pass, in O(n) time and O(1) space -- in linear time complexity and constant space complexity. this makes the mjrty algorithm suitable for some types of data streaming.

## String Formatting

* [go-stringcase](https://github.com/reiver/go-stringcase) — makes it so you can convert strings to different casing styles: lower case, UPPER CASE, Title Case, camelCase, PascalCase, snake_case, CONST_CASE, property-case, Header-Case.
* [go-tmpl](https://github.com/reiver/go-tmpl) — provides templating capabilities.

## Supervision Tree

* [go-retoil](https://github.com/reiver/go-retoil) — provides simple functionality for restarting toilers (i.e., workers).
* [go-toil](https://github.com/reiver/go-toil) — provides simple functionality for managing toilers (i.e., workers).
* [go-toilfork](https://github.com/reiver/go-toilfork) — provides simple functionality for managing a group of toilers (i.e., workers) where each toiler in the group is basically the "same" toiler.

## Testing

* [go-arbitrary](https://github.com/reiver/go-arbitrary) — provides tools for generating arbitrary data; useful for testing and placeholder data.
* [go-shunt](https://github.com/reiver/go-shunt) — enables you to create "middleware" for the the "database/sql" package.

## twtxt

* [go-twtxt](https://github.com/reiver/go-twtxt) — implements encoding and decoding of the twtxt data format; which is used for creating feeds that makes up a decentralized micro-blogging social network.

## Unicode

* [go-utf8](https://github.com/reiver/go-utf8) — implements encoding and decoding of UTF-8, for the Go programming language; this package is meant to be a replacement for Go's built-in "unicode/utf8" package.
* [go-whitespace](https://github.com/reiver/go-whitespace) — A small library for dealing with whitespace; note that this Go library accounts for all 26 UNICODE whitespace characters (and not just the standard ASCII ones), as well as accounts for all 7 UNICODE mandatory break characters.

## Unique IDs

* [go-xim](https://github.com/reiver/go-xim) — quazi‐ monotonically‐increasing unique‐identifiers, whose serialized form are safe to use as file‐names, and directory‐names, and where lexical-ordering of the xim-id (under Unicode & ASCII) is in-practice also temporal-ordering of the xim-id (almost all of the time)
  * [xim-id](https://github.com/reiver/xim-id) — a program using **go-xim**

## Video

* [go-fourcc](https://pkg.go.dev/github.com/reiver/go-fourcc) — a Go implementation of FOURCC (four character code) (4CC) identifiers for a video codecs, compression formats, colors, and pixel format used in media files.
