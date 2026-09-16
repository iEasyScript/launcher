# Project X Launcher

Builds of the Project X launcher. This repository holds no source, only
releases, so the downloads stay publicly reachable while the engine stays
private.

## Download

Always-current links, which keep working across versions:

| Platform | Link |
|---|---|
| Windows (x86-64) | [project-x-launcher-windows-x86_64.zip](https://github.com/iEasyScript/launcher/releases/latest/download/project-x-launcher-windows-x86_64.zip) |
| Linux (x86-64) | [project-x-launcher-linux-x86_64.tar.gz](https://github.com/iEasyScript/launcher/releases/latest](https://github.com/iEasyScript/launcher/releases/latest/download/project-x-launcher-linux-x86_64.tar.gz)) |

Or browse [all releases](https://github.com/iEasyScript/launcher/releases).

Every asset ships with a `.sha256` beside it. To check a download:

```bash
sha256sum -c project-x-launcher-windows-x86_64-1.0.0.zip.sha256
```

## Running it

Unzip and run the launcher. It signs you in through Jagex's own login page, so
your password goes to Jagex rather than to this program, which only receives
tokens. It then downloads the game client and can install scripts from its
Plugins tab.

Scripts come from two public repositories:
[official-scripts](https://github.com/iEasyScript/official-scripts) and
[community-scripts](https://github.com/iEasyScript/community-scripts). Writing
your own starts at [script-api](https://github.com/iEasyScript/script-api).
