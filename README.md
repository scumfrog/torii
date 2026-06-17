# Torii

The secure gateway for AI tools. Sits between MCP clients (Claude Desktop, Cursor, your own apps) and the tools they call — adds policy enforcement, audit logging, threat scanning, and consent gates.

Website: **[usetorii.dev](https://usetorii.dev)** · Docs: **[usetorii.dev/docs](https://usetorii.dev/docs)**

This repo hosts the release artifacts (binaries, install script, formula refs) for the Torii gateway. The source code is developed elsewhere — visit the website to learn how the platform fits together.

## Install

```bash
# Homebrew (macOS / Linux)
brew install scumfrog/tap/torii

# curl (macOS / Linux)
curl -fsSL https://usetorii.dev/install.sh | sh

# npm
npx @torii/gateway

# Docker
docker pull ghcr.io/scumfrog/torii-gateway:latest
```

After installing, point your MCP client at the binary and set `TORII_API_KEY` (get one at [usetorii.dev/dashboard](https://usetorii.dev/dashboard)). Full setup walkthrough at [usetorii.dev/docs](https://usetorii.dev/docs).

## License

MIT. See [LICENSE](./LICENSE).
