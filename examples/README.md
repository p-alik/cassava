# Building the examples

To build these examples using the in-tree version of cassava, run:

```bash
$ cabal sandbox init
$ cabal sandbox add-source ..
$ cabal install --only-dependencies
$ cabal build
```
