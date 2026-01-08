# LM-Tools
Outils informatiques et documentations diverses

## Repository Structure

This repository is organized by target platform to improve clarity and ease of navigation.

### Linux Tools (`/linux`)

Tools and scripts designed for Linux systems:

- **`linux/scripts_shell/`** - Shell scripts (bash, sh, etc.)
- **`linux/python/`** - Python scripts and tools for Linux

### Windows Tools (`/windows`)

Tools and scripts designed for Windows systems:

- **`windows/fichiers_batch/`** - Batch files (.bat, .cmd)
- **`windows/scripts_powershell/`** - PowerShell scripts (.ps1)
- **`windows/python/`** - Python scripts and tools for Windows

## Migration Guide

### For New Contributions

When adding new tools or scripts, please place them in the appropriate directory based on:

1. **Target Platform**: Choose `/linux` or `/windows`
2. **Script Type**: Choose the appropriate subdirectory based on the scripting language/technology

### Transitioning from Previous Structure

If you're working with an older version of this repository that used a different structure, here's how the directories map:

**Old Structure → New Structure:**

- `windows/Batch/` → `windows/fichiers_batch/`
- `windows/PowerShell/` → `windows/scripts_powershell/`

**Migration Steps:**

1. Move your batch scripts from `windows/Batch/` to `windows/fichiers_batch/`
2. Move your PowerShell scripts from `windows/PowerShell/` to `windows/scripts_powershell/`
3. Place any Python scripts in the appropriate platform directory:
   - Linux Python scripts → `linux/python/`
   - Windows Python scripts → `windows/python/`
4. Update any documentation or references to the old paths

## Contributing

When contributing to this repository:

1. Place your scripts in the correct platform and technology directory
2. Include a brief description or comment explaining what your script does
3. Follow the naming conventions used in each directory
4. Update relevant README files if adding significant new functionality

## Usage

Each directory contains its own README with specific information about the tools contained within. Please refer to those READMEs for detailed usage instructions.
