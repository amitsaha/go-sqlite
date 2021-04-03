# `zombiezen.com/go/sqlite`

[![Go Reference](https://pkg.go.dev/badge/zombiezen.com/go/sqlite.svg)](https://pkg.go.dev/zombiezen.com/go/sqlite)

This package provides a low-level Go interface to SQLite 3. It is a fork of
[`crawshaw.io/sqlite`][] that uses [`modernc.org/sqlite`][]. It aims to be a
mostly drop-in replacement for `crawshaw.io/sqlite`. See the [migration docs][]
for instructions on how to migrate.

[`crawshaw.io/sqlite`]: https://github.com/crawshaw.io/sqlite
[`modernc.org/sqlite`]: https://pkg.go.dev/modernc.org/sqlite
[migration docs]: cmd/zombiezen-sqlite-migrate/README.md

## Install

```shell
go get zombiezen.com/go/sqlite
```

## Getting Started

If you're creating a new application, see the [package examples][].

If you're looking to switch existing code that uses `crawshaw.io/sqlite`, take
a look at the [migration docs][].

[package examples]: https://pkg.go.dev/zombiezen.com/go/sqlite#pkg-examples

## License

Mostly ISC, with some code borrowed from `modernc.org/sqlite`, which is under a
BSD 3-Clause license. See [LICENSE](LICENSE) for details.

Source files in this repository use [SPDX-License-Identifier tags][] to indicate
the applicable license.

[SPDX-License-Identifier tags]: https://spdx.github.io/spdx-spec/appendix-V-using-SPDX-short-identifiers-in-source-files/
