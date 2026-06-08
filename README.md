# tunny-dist

Public release binaries for **[Tunny](https://tunny.app)** — a self-hosted WireGuard VPN that turns any small box into a private network for your whole home.

The Tunny source lives in a separate, private repository. This repo exists only to
distribute the compiled binaries so the one-line installer works for everyone:

```sh
curl -fsSL https://tunny.app/install.sh | sh
```

## Manual download

Grab a binary for your platform from the [latest release](https://github.com/abartrim/tunny-dist/releases/latest):

- Linux — `tunny-linux-amd64`, `tunny-linux-arm64`, `tunny-linux-arm`
- macOS — `tunny-darwin-arm64`, `tunny-darwin-amd64`

```sh
chmod +x tunny-linux-arm64 && sudo mv tunny-linux-arm64 /usr/local/bin/tunny
```

Releases here are published automatically by Tunny's CI on each tagged version.
