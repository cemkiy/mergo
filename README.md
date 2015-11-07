# Mergo

A helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.

mergo: Thanks to [imdario/mergo](https://github.com/imdario/mergo/)

And tihs version allows for empty values. Example: false, 0 or []

Your struct variables must be pointers. Because golang allows nil variables with pointer.

## Installation

    go get github.com/cemkiy/mergo

    // use in your .go code
    import (
        "github.com/cemkiy/mergo"
    )

## License

[BSD 3-Clause](http://opensource.org/licenses/BSD-3-Clause) license, as [Go language](http://golang.org/LICENSE).
