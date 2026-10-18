# Escribir-releases

Downloads for the [Escribir](https://escribir.app/) Mac app: a text editor for
Markdown, Fountain, and plain text.

This repo holds **only GitHub releases**. Each release is named `v<version>` and
carries one asset, `Escribir.dmg`: the Developer ID-signed, notarized build that
the Homebrew cask installs. There is no source here; Escribir's source repo is
private, and its release workflow publishes the DMG to this public repo so that
Homebrew can download it.

## Install

```bash
brew install --cask intrusive-memory/tap/escribir
```

Or open the latest `Escribir.dmg` from
[Releases](https://github.com/intrusive-memory/Escribir-releases/releases/latest)
and drag Escribir to Applications. Requires macOS 26.4 or later on Apple silicon.

Escribir is also on the Mac App Store. The two share one bundle id, so remove an
App Store copy from `/Applications` before installing the cask.
