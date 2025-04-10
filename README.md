# DotSync

DotSync is a simple dotfiles synchronization and management system. It helps you maintain and deploy your configuration files and install your prefered programs autotmatically.

> [!NOTE]  
> This scripts are meant to be used on Arch Linux. But you can modify the commands to use other package managers for your distro.

## Features

- Automated installation of packages and configurations (dotfiles)
- Easy customization of packages.conf for your specific needs
- Easy restoration of configurations on new systems

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/li-lay/DotSync.git
   ```

2. Run the installation script:
   ```bash
   cd DotSync
   ./install.sh
   ```

> [!TIP]
> This script is easily convertable to other package managers. You can modify the install.sh script to use your distrobution package manager. And modify the packages.conf file to add or remove packages as you see fit.

## File Structure

```
DotSync/
├── dotfiles-setup.sh   # Dotfiles setup script
├── flatpaks.sh         # Flatpak package installation
├── install.sh          # Primary installation script
├── packages.conf       # List of system packages to install
├── README.md
├── tpm.sh              # Tmux plugin manager setup
└── utils.sh            # Utility functions
```
