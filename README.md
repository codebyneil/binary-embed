# binary-embed

A long, long time ago I once needed (well, wanted) to embed multiple binary files inside of a single executable so that I could later, at run-time, write them out to disk and then use them. This is just a tiny tool that converts whatever file you point it at into a C array and dumps that code to stdout, which you can then copy-paste it into your source.
