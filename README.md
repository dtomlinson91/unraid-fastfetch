# unraid-fastfetch

An Unraid plugin that installs fastfetch ([upstream](https://github.com/fastfetch-cli/fastfetch)).

## Install

In the Unraid web UI, go to **Plugins > Install Plugin** and paste this URL:

```
https://github.com/dtomlinson91/unraid-fastfetch/raw/main/unraid-fastfetch.plg
```

## Release

The `release` workflow uses the shared workflow in [unraid-plugin-template](https://github.com/dtomlinson91/unraid-plugin-template).
It runs every Monday, and it releases a new plugin version when upstream has a new release.
To release by hand, run the workflow from the **Actions** tab.

The plugin settings are in `plugin.conf`. The text for the Unraid Plugins page is in `description.md`.
