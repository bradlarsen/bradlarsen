## Brad Larsen

[![Mastodon Profile](https://img.shields.io/mastodon/follow/109522097799876582?domain=https%3A%2F%2Finfosec.exchange)](https://infosec.exchange/@bradlarsen)
[![Personal Website](https://img.shields.io/badge/website-bradfordlarsen.com-lightgray)](https://www.bradfordlarsen.com)

I’m a computer scientist in Massachusetts with graduate education and 15 years of industry experience. I’ve worked in binary- and source-based static program analysis, symbolic execution, compilers and interpreters, high-performance computing, fuzz testing, application security, secrets detection, and production machine learning systems.

I currently work at [Truffle Security](https://trufflesecurity.com) doing research and development on secrets detection and all other things secrets-related.

You can find a PDF of my resume [here](https://bradfordlarsen.com/files/bradford-larsen-computer-scientist.pdf). I’ve also written and presented several [peer-reviewed publications](https://bradfordlarsen.com/publications/) over the years.

You can find me on the infosec.exchange Mastadon instance as <a rel="me" href="https://infosec.exchange/@bradlarsen">@bradlarsen</a>.

## Open Source

The majority of my professional work has been in closed-source proprietary codebases. But some has been open-source, including these things:

- I authored and maintained [Nosey Parker](https://github.com/praetorian-inc/noseyparker), a fast secrets detector for offensive security with high signal-to-noise, and its complementary [Nosey Parker Explorer](https://github.com/praetorian-inc/noseyparkerexplorer) TUI app for interactive triage
- I [found](https://www.mail-archive.com/sqlite-users@mailinglists.sqlite.org/msg100687.html) and [fixed](https://www.sqlite.org/src/info/4fc6580ffa7232aa) a bug in the tokenizer in [SQLite](https://sqlite.org) that caused it to not work on EBCDIC systems
- I contributed [additional fuzz targets](https://discuss.python.org/t/contributing-fuzzing-targets-to-cpython/36833) to CPython's [OSS-Fuzz](https://github.com/google/oss-fuzz) integration, which found a few bugs
- I [found](https://bugs.python.org/issue36495) and [fixed](https://github.com/python/cpython/pull/12641) memory errors in the parser in [CPython](https://github.com/python/cpython) that [also affected](https://github.com/python/typed_ast/pull/99) its related [`typed-ast`](https://github.com/python/typed_ast) library
- I [added the `sha1` function](https://github.com/duckdb/duckdb/pull/13020) to DuckDB
- I [found and fixed several bugs](https://github.com/trailofbits/manticore/pulls?q=is%3Apr+author%3Abradlarsen) in [Manticore](https://github.com/trailofbits/manticore), the low-level symbolic execution engine, enhanced its ARMv7 support, and [enhanced its Linux filesystem](https://github.com/trailofbits/manticore/pull/1673) emulation
