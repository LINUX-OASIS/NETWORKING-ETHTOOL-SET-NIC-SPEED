# NIC [ETHERNET] SPEED CONFIGURATOR

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Shell Script](https://img.shields.io/badge/shell-bash-green.svg)](https://www.gnu.org/software/bash/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![GitHub issues](https://img.shields.io/github/issues/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED.svg)](https://github.com/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED/issues)
[![GitHub forks](https://img.shields.io/github/forks/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED.svg)](https://github.com/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED/network)
[![GitHub stars](https://img.shields.io/github/stars/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED.svg)](https://github.com/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED/stargazers)

A TUI-based bash script to easily view and configure the speed and duplex settings of your Ethernet network interfaces (NICs). Built with `whiptail` for a user-friendly experience directly in your terminal.

!Demo GIF
> *(Demo GIF placeholder: Consider using a tool like `asciinema` to record a terminal session and convert it to a GIF.)*

---

## ✨ Features

-   **Interactive TUI**: A simple and intuitive `whiptail` interface for easy navigation.
-   **View NIC Capabilities**: See all supported link modes for a selected network card.
-   **Set NIC Speed**: Manually set the interface speed and duplex, disabling autonegotiation.
-   **Dependency Check**: Automatically checks for required tools and will offer to install them if missing.

## 🖥️ Compatibility

This script is designed for and tested on Debian-based Linux distributions. It should work out-of-the-box on:

-   !Debian
-   !Ubuntu
-   !Linux Mint
-   ...and other derivatives that use the `apt` package manager.

## ⚙️ Dependencies

The script relies on a few common networking and UI tools. It will attempt to automatically install any missing dependencies using `apt`.

-   `whiptail` (from the `newt` package)
-   `ethtool`
-   `iproute2` (provides the `ip` command)

## 🚀 Usage

1.  Clone the repository:
    ```bash
    git clone https://github.com/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED.git
    cd NETWORKING-ETHTOOL-SET-NIC-SPEED
    ```

2.  Make the script executable:
    ```bash
    chmod +x custom-NETWORKING-ETHTOOL-SET-NIC-SPEED.sh
    ```

3.  Run with `sudo` privileges:
    ```bash
    sudo ./custom-NETWORKING-ETHTOOL-SET-NIC-SPEED.sh
    ```
    > **Note**: The script requires `sudo` to query and modify network interface settings.

---

## 💬 Contributing

Pull requests, issues, and suggestions are warmly welcomed!

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 🌐 Links

-   [Issues](https://github.com/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED/issues)
-   [Pull Requests](https://github.com/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED/pulls)
-   [Releases](https://github.com/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED/releases)
-   [Wiki](https://github.com/LINUX-OASIS/NETWORKING-ETHTOOL-SET-NIC-SPEED/wiki)

## 🧙‍♂️ Maintainer

-   [LINUX-OASIS](https://github.com/LINUX-OASIS)

## 📜 License

This project is licensed under the **GPL-3.0 License**. See the `LICENSE` file for details.
