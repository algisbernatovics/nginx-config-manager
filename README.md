# Nginx Config Manager

A Bash helper for managing Nginx site configuration files from an interactive terminal menu.

## Overview

A Bash helper for managing Nginx site configuration files from an interactive terminal menu.

## Features

- Lists available Nginx configuration files.
- Provides scripts to add, edit, enable, disable, and remove configs.
- Loads shared configuration and helper scripts from a single menu loop.

## Tech Stack

- Bash
- Nginx
- Linux shell scripting

## Project Structure

- `main.sh` - interactive menu loop
- `config.sh` - paths and shared configuration
- `add.sh, edit.sh, enable.sh, disable.sh, remove.sh` - individual Nginx operations

## Getting Started

Review `config.sh` first, then start the menu:

```bash
chmod +x *.sh
./main.sh
```

Run with appropriate permissions for the target Nginx configuration directory.

## Portfolio Notes

- Demonstrates practical Linux automation for server administration.
- Breaks each action into a separate shell script for maintainability.

## Status

Portfolio-ready operations utility.
