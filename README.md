# T801 Agent downloads

Builds of [T801 Agent](https://t801.dev): the desktop app and the `t801` command-line tool. The source code is not published here.

## Install the command-line tool

macOS and Linux:

```sh
curl -fsSL https://t801.dev/install.sh | sh
```

Windows (PowerShell):

```powershell
irm https://t801.dev/install.ps1 | iex
```

Then run `t801`. Each version and its checksums (`SHA256SUMS`) are on the [Releases](https://github.com/ATK9999-STUDIOS/t801-releases/releases) page.

## Files in this repository

- `model-manifest.json`: the list of models and their settings that T801 Agent reads to stay current between releases.

## Problems and questions

Open an [issue](https://github.com/ATK9999-STUDIOS/t801-releases/issues). Privacy: [t801.dev/privacy-policy](https://t801.dev/privacy-policy).
