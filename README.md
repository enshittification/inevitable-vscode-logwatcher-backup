# Log Watcher

[![CI](https://github.com/Automattic/vscode-logwatcher/actions/workflows/ci.yml/badge.svg)](https://github.com/Automattic/vscode-logwatcher/actions/workflows/ci.yml)
[![Dependency Review](https://github.com/Automattic/vscode-logwatcher/actions/workflows/dependency-review.yml/badge.svg)](https://github.com/Automattic/vscode-logwatcher/actions/workflows/dependency-review.yml)

Log Watcher is an extension for VSCode to watch logs and display them in the "Output" tab, much like what `tail -F` does.

## Features

![Log Watcher](https://github.com/Automattic/vscode-logwatcher/assets/7810770/f3849fa6-09cf-4936-9d26-12a25ca1dd18)

Avaiable commands:
  * **Log Watcher: Watch File…**: starts watching the specified file for changes. The changes will be shown in the Output tab.
  * **Log Watcher: Stop Watching File…**: stops watching the specified file.
  * **Log Watcher: Watch nginx access.log**: watch `/var/log/nginx/access.log` for changes.
  * **Log Watcher: Watch nginx error.log**: watch `/var/log/nginx/error.log` for changes.

## Requirements

This extension is tailored for development of [WordPress VIP](https://docs.wpvip.com/) with [GitHub Codespaces](https://docs.wpvip.com/technical-references/developing-with-github-codespaces/). While the "Watch File" command will work everywhere, more specialized commands like "Watch nginx access.log" expect to find the log files in the preconfigured places.

Log coloring is available when the [Log File Highlighter](https://marketplace.visualstudio.com/items?itemName=emilast.LogFileHighlighter) extension is installed.

### Installation

1. Run [`Install Extension`](https://code.visualstudio.com/docs/editor/extension-gallery#_install-an-extension) command from the [Command Palette](https://code.visualstudio.com/Docs/editor/codebasics#_command-palette).
2. Search and choose `Log Watcher`.

## Changelogs

See the [Releases section of our GitHub project](https://github.com/Automattic/vscode-logwatcher/releases) for changelogs for each release version.

## Acknowledgements

[Log icons created by Flat Icons](https://www.flaticon.com/free-icons/log)
