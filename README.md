# PowerShell Script Obfuscator

A browser-based tool to obfuscate PowerShell scripts by randomizing variable names and injecting comments, reducing Shannon entropy while preserving functionality.

## Features

- **Variable Randomization**: Replaces variable names with random 20–30 character alphanumeric strings
- **Comment Injection**: Adds comments at the beginning, after lines or semicolons, and at the end
- **Flexible Script Handling**: Handles scripts with or without semicolons
- **Entropy Analysis**: Displays original and final Shannon entropy with reduction percentage
- **File Operations**: Supports file upload (`.ps1`/`.txt`) and download of obfuscated scripts
- **Client-Side Processing**: Runs entirely in the browser — no server required

## Usage

1. Open `index.html` in a modern browser
2. Paste your PowerShell script or upload a `.ps1`/`.txt` file
3. Click **"Obfuscate Script"** to generate the obfuscated version
4. Click **"Download"** to save the obfuscated script

## Getting Started

Simply clone this repository and open the `index.html` file in your web browser:

```bash
git clone https://github.com/yashrustagi2004/psObfuscator.git
cd psObfuscator
# Open index.html in your browser
```

## How It Works

The obfuscator works by:
- Parsing PowerShell variables and replacing them with randomized names
- Injecting benign comments throughout the script
- Maintaining script functionality while reducing detectability
- Calculating and displaying entropy reduction metrics

## Security Note

This tool is intended for educational purposes and legitimate security testing. Always ensure you have proper authorization before using obfuscated scripts in any environment.