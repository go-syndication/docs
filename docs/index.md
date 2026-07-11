# go-syndication

Pure-Go RSS / Atom / JSON Feed parsing and fetching.

go-syndication provides pure-Go parsing and fetching of web syndication feeds. The format is auto-detected from the bytes and RSS 2.0, Atom 1.0 and JSON Feed 1.1 are normalized into a single Feed type, so downstream code never has to branch on the wire format. CGO_ENABLED=0, standard library only, zero third-party dependencies.

Everything is **pure Go** (`CGO_ENABLED=0`), standard-library-first, and
cross-compiles to every 64-bit Go target. Licensed BSD-3-Clause.

## Packages

<div class="pk-grid" markdown>
<a class="pk-card" href="packages/feed.md"><code>feed</code><br><small>Pure-Go RSS/Atom/JSONFeed parser and fetcher. CGO=0, zero third-party deps.</small></a>
</div>
