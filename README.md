<img width="1920" height="738" alt="Przechwytywanie" src="https://github.com/user-attachments/assets/c0b3dbbf-d7ef-4e55-ba20-32bb73355b7f" />
# JSON Beautifier

Single-file web app for formatting and prettifying JSON data with support for nested JSON strings.

## Purpose

Transforms minified or poorly formatted JSON into human-readable output with proper indentation and line breaks. Handles edge cases like JSON-encoded strings within JSON objects—common in API responses where nested data gets serialized.

## Features

- **Recursive formatting**: Detects and formats JSON strings embedded within JSON objects
- **Configurable indentation**: 2 spaces, 4 spaces, or tabs
- **Minify option**: Compress formatted JSON back to compact form
- **Dual-panel interface**: Input left, output right for side-by-side comparison
- **Copy to clipboard**: One-click output copying
- **Keyboard shortcut**: Ctrl/Cmd+Enter for quick formatting
- **Error handling**: Clear validation messages for malformed JSON
- **Dark theme**: VSCode-style interface for extended use

## Use Cases

- API response analysis
- Configuration file cleanup
- Data migration and ETL workflows
- Debugging serialized JSON payloads
- Log file parsing
- Integration testing

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- Client-side processing (no data leaves your browser)
- Recursive parser handles arbitrary nesting depth
- Responsive layout (stacks vertically on mobile)

## Installation

Download `json-beautifier.html` and open in any modern browser. No build process or server required.

## Usage

1. Paste JSON into left panel
2. Click "Format JSON" or press Ctrl/Cmd+Enter
3. Formatted output appears in right panel
4. Use "Minify" to compress, "Copy Output" to grab results

## Keywords

JSON formatter, JSON beautifier, JSON prettifier, JSON validator, JSON parser, nested JSON, API response formatter, developer tools, web-based JSON tool, JSON viewer

## License

MIT
