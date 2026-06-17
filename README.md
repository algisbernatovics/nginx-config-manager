# Nginx Config Manager

A Bash menu utility for managing Nginx site configuration files from the terminal.

## Learning Goal

Practice Linux shell scripting for real server administration tasks while keeping each operation in a focused script.

## Features

- Lists available Nginx configuration files.
- Adds, edits, enables, disables, and removes site configs.
- Uses a menu loop that loads shared helpers from separate scripts.

## Requirements

- Linux environment
- Bash
- Nginx installed and configured
- Permissions to edit the target Nginx configuration directories

## Run

Review `config.sh` first, then run:

```bash
chmod +x *.sh
./main.sh
```

## Project Structure

- `main.sh` - interactive menu loop
- `config.sh` - shared paths/configuration
- `add.sh`, `edit.sh`, `enable.sh`, `disable.sh`, `remove.sh` - individual operations
- `list.sh`, `choice.sh` - menu display and selection helpers

## License

MIT License. See [LICENSE](./LICENSE).
