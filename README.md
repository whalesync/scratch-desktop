# Scratch Desktop

Desktop app for [Scratch](https://www.scratch.md) — bulk edit your content with AI. Pull content from Shopify, Webflow, WordPress, Airtable, Notion, and more, edit it with any tool, and push changes back with full diff visibility and control.

## Installation

### Homebrew (macOS, Apple Silicon)

```bash
brew install --cask whalesync/scratch-desktop/scratch-desktop
```

> Apple Silicon (arm64) only. Intel Macs are not supported by the cask — use the [direct download](#direct-download) instead.

After install, launch **Scratch Desktop** from `/Applications` or Spotlight.

### Pinning a specific version

The tap also publishes versioned casks pinned to a major, minor, or patch version:

```bash
brew install --cask whalesync/scratch-desktop/scratch-desktop@1
brew install --cask whalesync/scratch-desktop/scratch-desktop@1.0
brew install --cask whalesync/scratch-desktop/scratch-desktop@1.0.7
```

### Updating

Scratch Desktop updates itself in place via the in-app auto-updater, so a manual upgrade is usually unnecessary. To force Homebrew to re-pin to the latest cask version:

```bash
brew update
brew upgrade --cask scratch-desktop
```

### Uninstalling

```bash
brew uninstall --cask scratch-desktop
```

### Direct download

Linux, Windows, and Intel macOS installers are published on the [Releases page](https://github.com/whalesync/scratch-desktop/releases).

---

## Getting Started

1. Launch **Scratch Desktop**.
2. Click **Log in with Scratch** — the app opens your browser to authenticate.
3. Create or open a workspace, connect an external service (Webflow, Airtable, Notion, …), and pull your content.
