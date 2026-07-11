# feed

Pure-Go RSS 2.0 / Atom 1.0 / JSON Feed 1.1 parser and fetcher. The package auto-detects the source format from the bytes and normalizes all three into a single `Feed` type. `Parse` handles bytes you already have; `Fetch` retrieves and parses over HTTP (a nil client uses `http.DefaultClient`). `CGO_ENABLED=0`, zero third-party dependencies — standard library only.

## Install

```bash
go get github.com/go-syndication/feed
```

Requires Go 1.26.4 or newer. `CGO_ENABLED=0`.

## Links

- Source: <https://github.com/go-syndication/feed>
- API reference: <https://pkg.go.dev/github.com/go-syndication/feed>

!!! note
    See the module's README for full, up-to-date details.
