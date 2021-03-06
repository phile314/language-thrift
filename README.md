[![build-status]](https://travis-ci.org/abhinav/language-thrift)

`language-thrift` provides a parser and pretty printer for the [Thrift IDL
format]. In addition to parsing the IDL, it keeps track of Javadoc-style
comments (`/** ... */`) and attaches them to the type, service, function, or
field, above which they were added. These are retained when the document is
sent through the pretty printer.

The parser uses [`megaparsec`] and the pretty printer [`ansi-wl-pprint`]. The
pretty printer can produce syntax highlighted output.

Haddock-generated docs are available on [Hackage] and [here].

  [build-status]: https://travis-ci.org/abhinav/language-thrift.svg?branch=master
  [Thrift IDL format]: http://thrift.apache.org/docs/idl
  [`megaparsec`]: http://hackage.haskell.org/package/megaparsec
  [`ansi-wl-pprint`]: http://hackage.haskell.org/package/ansi-wl-pprint
  [Hackage]: http://hackage.haskell.org/package/language-thrift
  [here]: http://abhinavg.net/language-thrift/
