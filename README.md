# Voxiven Homebrew Tap

Homebrew tap for [Voxiven](https://voxiven.com) OSS tools.

## Install

```bash
brew tap voxiven/tap
brew install dotsync
```

## Tools

- **[dotsync](https://github.com/Voxiven/dotsync)** — multi-machine continuity for Claude Code and other AI dev tools. Peer-to-peer, real-time, no cloud.

## Updating

When a new release of dotsync (or any tool) lands:

1. The tool's release pipeline publishes a tagged tarball to GitHub
2. Update the corresponding `Formula/<name>.rb` here with the new `url` + `sha256`
3. Commit and push — `brew update` picks it up automatically on user machines
