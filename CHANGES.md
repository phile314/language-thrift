0.4.0.0
=======

-   Add pretty printing module.
-   Parsers of different constructors are no longer exported by the parsing
    module; instead only the parsers for their corresponding types are
    exported.
-   Rename record for field requiredness from `fieldRequiredNess` to
    `fieldRequiredness`.

0.3.0.0
=======

-   Allow changing the underlying parser to any parser that implements the
    `TokenParsing` class from `parsers`.
-   Add `thriftIDLParser` for standard use cases.
-   Add `Language.Thrift.Parser.Trifecta` with a standard Trifecta-based
    parser.

0.2.0.0
=======

-   Track starting positions in source annotations.
-   Move docs to a separate field.

0.1.0.1
=======

-   Allow `base` 4.9.

0.1.0.0
=======

-   Initial release.