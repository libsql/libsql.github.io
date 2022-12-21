---
layout: default
---

![libSQL logo](/images/favicon/apple-touch-icon.png)

# What is libSQL?

libSQL is an [open source][GitHub], open contribution fork of SQLite. We aim to
evolve it to suit many more use cases than SQLite was originally designed for.

[Read more about the product vision](./about) and the motivations behind it.

libSQL is developed under the [MIT license] with a clear [code of conduct].

# Features and extensions

## Code complete

- **Nov 21, 2022**: WebAssembly user-defined functions ([PR 45], [blog][wasm-blog])
- **Nov 7, 2022**: New RANDOM ROWID keywords ([Issue 12])
- **Dec 21, 2022**: Pass down SQL string to virtual table implementation ([PR 87], thanks to [lucasvr])
- **Dec 21, 2022**: Virtual write-ahead log interface ([PR 53])

## In progress

- "Bottomless" WAL - replication to S3-compatible storage ([PR 92])

## Backlog

[Open issues on GitHub]


[GitHub]: https://github.com/libsql/libsql
[MIT license]: https://github.com/libsql/libsql/blob/main/LICENSE.md
[code of conduct]: https://github.com/libsql/libsql/blob/main/CODE_OF_CONDUCT.md
[Open issues on GitHub]: https://github.com/libsql/libsql/issues
[PR 45]: https://github.com/libsql/libsql/pull/45
[wasm-blog]: https://blog.chiselstrike.com/webassembly-functions-for-your-sqlite-compatible-database-7e1ad95a2aa7
[Issue 12]: https://github.com/libsql/libsql/issues/12
[PR 53]: https://github.com/libsql/libsql/pull/53
[PR 87]: https://github.com/libsql/libsql/pull/87
[lucasvr]: https://github.com/lucasvr
[PR 92]: https://github.com/libsql/libsql/pull/92
