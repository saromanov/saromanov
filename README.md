# Sergey Romanov

Go / Rust / Python engineer. I build developer tools: fast CLIs, observability
plumbing, and local-first tooling for AI agents. I like tools that finish
before the shell prompt returns.

[openfd](https://github.com/saromanov/openfd) ·
[godownload](https://github.com/saromanov/godownload) ·
[virtudoc](https://github.com/saromanov/virtudoc) ·
[rabbitmq-clue](https://github.com/saromanov/rabbitmq-clue) ·
[all repositories](https://github.com/saromanov?tab=repositories)

## Featured

### [openfd](https://github.com/saromanov/openfd) — `lsof` that answers instantly

Streams file descriptors straight from `/proc`: socket details from netlink,
deleted files, descriptor leaks, process tree, summary. Single static binary.

```console
$ cargo install openfd        # or: brew install saromanov/tap/openfd
```

![openfd scanning file descriptors and printing a summary](https://raw.githubusercontent.com/saromanov/openfd/HEAD/docs/demo.gif)

### [godownload](https://github.com/saromanov/godownload) — resumable downloads for Go

Library and CLI: multi-segment transfers, checksum verification, rate limiting,
resume, mirror manifests, progress callbacks.

```console
$ go install github.com/saromanov/godownload/cmd/godownload@latest
```

### [virtudoc](https://github.com/saromanov/virtudoc) — offline documentation server for AI agents

SQLite FTS5 index, MCP tools, incremental reindex by content hash. No network,
no API keys. `pip install virtudoc`.

![virtudoc answering a query over the local docs index](https://raw.githubusercontent.com/saromanov/virtudoc/HEAD/demo.gif)

### [rabbitmq-clue](https://github.com/saromanov/rabbitmq-clue) — RabbitMQ operations UI

Dead-letter inspection and replay with publisher confirms, queue-to-queue moves,
topology snapshot and diff, protobuf-aware publish and peek. One binary with an
embedded UI.

## More tools

[dizee](https://github.com/saromanov/dizee) — shrink JSON, logs and diffs before
they hit an agent context window ·
[otelcat](https://github.com/saromanov/otelcat) — `kcat` for OpenTelemetry ·
[logrus-loki-hook](https://github.com/saromanov/logrus-loki-hook) — reliable Loki
hook for logrus and slog ·
[goemits](https://github.com/saromanov/goemits) — Redis Streams event emitter

## Contact

[xxsmotur@gmail.com](mailto:xxsmotur@gmail.com)
