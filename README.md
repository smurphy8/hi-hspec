hi-hspec
=================

A template for [hi](https://github.com/fujimura/hi).

example:

```
$ hi -m Foo.Bar -p foo-bar  -r git@github.com:fujimura/hi-hspec.git
$ tree
.
├── ChangeLog.md
├── foo-bar.cabal
├── LICENSE
├── README.md
├── src
│   ├── Foo
│   │   ├── Bar
│   │   │   └── Internal.hs
│   │   └── Bar.hs
│   └── Main.hs
└── test
    ├── Foo
    │   └── BarSpec.hs
    └── Spec.hs

5 directories, 8 files
```

Copyright 2013-2014 Fujimura Daisuke, under the MIT license.
