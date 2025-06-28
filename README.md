# Rua - Minimal AUR Helper

A simple yet functional AUR helper in Bash for Arch Linux.

![usage](./usage.gif)

## Description

rua is a lightweight AUR helper that automates:

- Cloning AUR packages into ~/rua/
- Building and installing with makepkg -sic

No unnecessary prompts—just fast AUR package installation.

## Requirements

- Arch Linux or Arch-based distribution
- Bash shell
- Root privileges

## Installation
```bash
git clone https://github.com/antonio-foti/rua.git
cd rua
chmod +x rua
sudo cp rua /usr/local/bin/
```

## Uninstallation
```bash
sudo rm /usr/local/bin/rua
```

## Usage
```bash
rua <aur-package-url>
```

## File Structure

All AUR packages are stored in:

```bash
~/rua/
   ├── package1/  
   ├── package2/  
   └── ...
```

## Features
- Auto-cloning into ~/rua/
- One-step install & cleanup (makepkg -sic)
- Not a full AUR manager (no updates/search)

## Contribution

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

MIT License - Free to use and modify
Created by Antonio Foti
