A fork of https://github.com/sysrpl/JsonTools applying patches not available on the Master branch with some additions of my own.

This fork is an attempt to hopefully merge the updates various developers have submitted but not had applied to create a unified version that is maintained

# JsonTools

A small pascal based json parser in one unit with no dependencies.

Please visit this [page](https://www.getlazarus.org/json/) for a complete guide on how to use this parser.

## Changelog

2020-10-05

Initial fork implementing ...

- Add [damoasda](https://github.com/damoasda) damoasda/unit-tests - source [nglthach](https://github.com/nglthach/JsonTools)
- TJsonNode.KindAsString property - returns the TJsonNodeKind enum as a string ('nkObject', 'nkArray', 'nkBool', 'nkNull', 'nkNumber', 'nkString')
- Apply [damoasda](https://github.com/damoasda) fix for #11 - Error while parsing \"\"





