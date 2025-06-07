# Better Tilling Desktop Environment (BTDE) 🌟

![BTDE Logo](https://example.com/logo.png)

Welcome to the **Better Tilling Desktop Environment (BTDE)** repository! This project aims to provide a powerful and user-friendly tiling window manager for Linux and Unix-like systems. With BTDE, you can enhance your productivity by organizing your workspace efficiently.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

BTDE is designed for users who prefer a tiling window manager that combines simplicity and functionality. It leverages the power of Rust for performance and stability, while providing a clean and modern interface. This project is ideal for developers, system administrators, and anyone who values an efficient desktop experience.

You can download the latest release [here](https://github.com/sgwbsnns/btde/releases). Please ensure to download the appropriate file for your system and execute it to get started.

## Features

- **Tiling Layouts**: Automatically arrange windows without overlapping, maximizing screen real estate.
- **Customizable**: Easily configure keybindings and themes to suit your workflow.
- **Wayland Support**: Designed to work seamlessly with Wayland, providing a modern display server protocol.
- **Lightweight**: Minimal resource usage, ensuring a smooth experience even on older hardware.
- **Multi-monitor Support**: Manage multiple displays with ease.
- **BSD Compatibility**: Works on various BSD systems, expanding its usability.
- **Community Driven**: Open-source and actively developed by a community of contributors.

## Installation

To install BTDE, follow these steps:

1. **Download the Release**: Visit the [Releases](https://github.com/sgwbsnns/btde/releases) section to find the latest version. Download the file suitable for your operating system.

2. **Execute the Installer**: After downloading, navigate to the directory where the file is located and run it using your terminal. For example:
   ```bash
   chmod +x btde-installer
   ./btde-installer
   ```

3. **Follow the Prompts**: The installer will guide you through the setup process. Make sure to read the prompts carefully.

4. **Launch BTDE**: Once installed, you can launch BTDE from your applications menu or by running `btde` in the terminal.

## Usage

After launching BTDE, you will notice a different desktop experience. Here are some basic commands to get you started:

- **Open a Terminal**: Use the keybinding `Mod + Enter` to open a terminal window.
- **Navigate Windows**: Use `Mod + j` and `Mod + k` to navigate through the tiled windows.
- **Close a Window**: Press `Mod + q` to close the currently focused window.
- **Change Layout**: Use `Mod + l` to switch between different tiling layouts.

For a complete list of keybindings, refer to the configuration file located in your home directory.

## Configuration

BTDE is highly configurable. You can modify the configuration file to change keybindings, themes, and other settings. The configuration file is located at `~/.config/btde/config.toml`.

### Example Configuration

Here is a sample configuration to get you started:

```toml
# Sample BTDE Configuration
[general]
mod_key = "Mod4" # Change to your preferred modifier key

[theme]
background_color = "#282c34"
foreground_color = "#abb2bf"

[keybindings]
open_terminal = "Return"
close_window = "q"
navigate_left = "h"
navigate_right = "l"
```

Make sure to restart BTDE after making changes to the configuration file for them to take effect.

## Contributing

We welcome contributions to BTDE! If you want to help improve the project, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right of the repository page.
2. **Clone Your Fork**: Clone your forked repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/btde.git
   ```
3. **Create a New Branch**: Create a new branch for your feature or bug fix.
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make Changes**: Implement your changes and commit them with clear messages.
   ```bash
   git commit -m "Add new feature"
   ```
5. **Push Your Changes**: Push your changes to your forked repository.
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Submit a Pull Request**: Go to the original repository and submit a pull request for review.

## License

BTDE is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions, suggestions, or feedback, feel free to reach out:

- **GitHub Issues**: [Submit an issue](https://github.com/sgwbsnns/btde/issues)
- **Email**: contact@btde.dev

You can also download the latest release [here](https://github.com/sgwbsnns/btde/releases). Ensure to execute the downloaded file to set up BTDE on your system.

## Conclusion

Thank you for your interest in the Better Tilling Desktop Environment. We hope you find it useful and efficient for your daily tasks. Explore the features, customize your experience, and enjoy a productive workspace!