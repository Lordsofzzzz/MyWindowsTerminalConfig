# Windows Terminal Custom Configuration

## Overview
This repository contains a customized Windows Terminal settings file with the **Dracula** color scheme, **FiraCode Nerd Font**, and various personalization options for a modern terminal experience.

## Features
- **Dracula Theme** for a sleek and visually appealing look
- **FiraCode Nerd Font** for improved coding experience
- **Acrylic transparency** for a modern UI effect
- **Custom cursor and opacity settings** for better visibility

## Installation

1. Install **Windows Terminal** from the Microsoft Store or via `winget`:
   ```sh
   winget install --id=Microsoft.WindowsTerminal -e
   ```
2. Install **FiraCode Nerd Font**:
   - Download from [Nerd Fonts](https://www.nerdfonts.com/font-downloads)
   - Install the font on your system
3. Apply the configuration:
   - Copy `settings.json` to:
     ```
     %LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
     ```
   - Restart Windows Terminal

## Customization
To modify the configuration, edit `settings.json` and update values like color schemes, fonts, and transparency settings.

## Contributions
Feel free to fork this repository and submit pull requests with improvements or new themes!

