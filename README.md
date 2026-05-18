# homebrew-tap

Homebrew tap maintained by the [OpenLid](https://github.com/openlid)
organization. Hosts macOS casks for the project's apps.

> Note: Homebrew Casks are macOS-only by design. Linux and Windows
> distributions, when available, will be linked from each project's
> own README. This tap exists specifically for `brew install --cask`
> users on macOS.

## Usage

```bash
brew tap openlid/tap
brew install --cask openlid
```

Or in one command:

```bash
brew install --cask openlid/tap/openlid
```

## Available casks

### `openlid`

[OpenLid](https://github.com/openlid/openlid) — keep your laptop awake
even with the lid closed.

```bash
brew install --cask openlid/tap/open-lid
```

After install, launch Open-Lid; macOS will ask you to enable it in
**System Settings → General → Login Items → Allow in the Background**.
No admin password required.

## License

Apache 2.0 — see [LICENSE](LICENSE).
