## Hi there! 👋🏻

[![Twitter Link](https://img.shields.io/twitter/follow/bradlarsen?style=social)](https://twitter.com/bradlarsen)
[![website](https://img.shields.io/badge/website-bradfordlarsen.com-lightgray)](https://www.bradfordlarsen.com)

I’m a computer scientist in Massachusetts with graduate education and 12 years industry experience. I’ve worked on static program analysis, symbolic execution, compilers and interpreters, fuzz testing, and application security.

I currently work in a team at [Praetorian](https://praetorian.com) that is combining static analysis with machine learning (specifically, large language models) to amplify and augment the capabilities of offensive security operators.

You can find my resume [here](https://bradfordlarsen.com/files/bradford-larsen-computer-scientist.pdf). I’ve also written and presented several [peer-reviewed publications](https://bradfordlarsen.com/publications/) over the years.

You can find me on the infosec.exchange Mastadon instance as <a rel="me" href="https://infosec.exchange/@bradlarsen">@bradlarsen</a>.

## Open Source

Nearly all of my professional work has been in closed-source proprietary codebases. But some has been open-source, including these things:

- I am the primary code author and project maintainer for [Nosey Parker](https://github.com/praetorian-inc/noseyparker), a fast secret scanner with high signal-to-noise
- I [found](https://www.mail-archive.com/sqlite-users@mailinglists.sqlite.org/msg100687.html) and [fixed](https://www.sqlite.org/src/info/4fc6580ffa7232aa) a bug in the tokenizer in [SQLite](https://sqlite.org) that caused it to not work on EBCDIC systems
- I contributed [additional fuzz targets](https://github.com/python/cpython/pull/111477) to CPython's [OSS-Fuzz](https://github.com/google/oss-fuzz) integration
- I [found](https://bugs.python.org/issue36495) and [fixed](https://github.com/python/cpython/pull/12641) memory errors in the parser in [CPython](https://github.com/python/cpython) that [also affected](https://github.com/python/typed_ast/pull/99) its related [`typed-ast`](https://github.com/python/typed_ast) library
- I [found and fixed several bugs](https://github.com/trailofbits/manticore/pulls?q=is%3Apr+author%3Abradlarsen) in [Manticore](https://github.com/trailofbits/manticore), the low-level symbolic execution engine, enhanced its ARMv7 support, and [enhanced its Linux filesystem](https://github.com/trailofbits/manticore/pull/1673) emulation
