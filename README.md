# file-integrity-checker
"A Python tool to monitor changes in files by calculating and comparing hash values"


# File Integrity Checker

## Overview
The **File Integrity Checker** is a Python tool that monitors changes in files by calculating and comparing their hash values (SHA-256). It helps ensure that important files remain unaltered, providing security and file integrity monitoring.

## Features
- **Monitors file changes** by comparing hash values.
- **Detects unauthorized file modifications** (e.g., malware infections, file corruption).
- **Stores initial hash values** in a `file_hashes.json` file.
- **Alerts the user** when a file has been modified or added.

## Requirements
- Python 3.x
- `hashlib` (built-in Python library, no installation required)

## Setup and Usage

### Step 1: Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/yourusername/file-integrity-checker.git
cd file-integrity-checker
