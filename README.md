[![build-status]](https://travis-ci.org/abhinav/language-thrift)

`language-thrift` provides a parser and pretty printer for the [Thrift IDL
format]. In addition to parsing the IDL, it keeps track of Javadoc-style
comments (`/** ... */`) and attaches them to the type, service, function, or
field, above which they were added. These are retained when the document is
sent through the pretty printer.

The parser uses [`parsers`] to allow plugging in the underlying parser. A
default [`trifecta`] based parser is provided.

The pretty printer supports both, [wl-pprint] and [ansi-wl-pprint].

Haddock-generated docs are available on [Hackage] and [here].

  [build-status]: https://travis-ci.org/abhinav/language-thrift.svg?branch=master
  [Thrift IDL format]: http://thrift.apache.org/docs/idl
  [`parsers`]: http://hackage.haskell.org/package/parsers
  [`trifecta`]: http://hackage.haskell.org/package/trifecta
  [wl-pprint]: http://hackage.haskell.org/package/wl-pprint
  [ansi-wl-pprint]: http://hackage.haskell.org/package/ansi-wl-pprint
  [Hackage]: http://hackage.haskell.org/package/language-thrift
  [here]: http://abhinavg.net/language-thrift/
