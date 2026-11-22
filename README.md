# Python WSL Hello

A minimal Python project for practicing Ubuntu on WSL, VS Code, Git, and GitHub.

## Run

```bash
python3 app/main.py
```

Expected output:

```text
Hello, world!
```

## Structure

- `app/main.py`: application entry point.
- `examples/`: reserved for a real VS Code screenshot with WSL terminal output.
- `requirements.txt`: no third-party dependencies required.

## Setup Status

The application has been tested with Python 3.12 on Windows.
Ubuntu on WSL is not installed yet: Windows component store corruption
blocks installation (`0x80073712`), and DISM repair could not locate repair
content (`0x800f0915`). WSL execution and its screenshot are still pending.
