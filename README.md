# My EndeavourOS Configurations

![License](https://img.shields.io/github/license/brunoalvesufu/my-endeavour-config)
![GitHub last commit](https://img.shields.io/github/last-commit/brunoalvesufu/my-endeavour-config)
![GitHub repo size](https://img.shields.io/github/repo-size/brunoalvesufu/my-endeavour-config)

This repository contains my custom configurations for different tools and terminals used in my EndeavourOS setup. Feel free to explore and use these configurations in your own environment.

## Table of Contents

- Tools
- Installation
- Included Configurations
- Technologies
- Contributing
- License

## Tools

- [Oh My Zsh](https://ohmyz.sh/)
- [Kitty Terminal](https://sw.kovidgoyal.net/kitty/)

## Installation

### Cloning the Repository

To clone this repository directly to your home directory, use the following commands:

```bash
cd ~
git clone https://github.com/brunoalvesufu/my-endeavour-config.git
```

### Applying the Configurations

To set up the configurations, you can use the following commands to create symbolic links. This way, your configurations will stay in sync with the repository:

```bash
# Create symbolic links
ln -s ~/my-endeavour-config/.p10k.zsh ~/.p10k.zsh
ln -s ~/my-endeavour-config/.zshrc ~/.zshrc
ln -s ~/my-endeavour-config/.config/kitty ~/.config/kitty
```

## Included Configurations

### Zsh and Oh My Zsh

- **.p10k.zsh**: Powerlevel10k theme configuration for Zsh.
- **.zshrc**: Custom Zsh configurations, including plugins and aliases.

### Kitty Terminal

Configurations for the Kitty terminal emulator, focused on performance and aesthetics.

## Technologies

### EndeavourOS
[EndeavourOS](https://endeavouros.com/) is a rolling-release Linux distribution based on Arch Linux. It aims to be a beginner-friendly Arch-based system without sacrificing any of the features that make Arch great.

### Oh My Zsh
[Oh My Zsh](https://ohmyz.sh/) is a delightful, open source, community-driven framework for managing your Zsh configuration. It comes bundled with thousands of helpful functions, helpers, plugins, and themes.

### Kitty Terminal
[Kitty](https://sw.kovidgoyal.net/kitty/) is a fast, feature-rich, GPU-based terminal emulator. It offers features like tabs, layouts, and the ability to view images directly in the terminal.

### Powerlevel10k
[Powerlevel10k](https://github.com/romkatv/powerlevel10k) is a theme for Zsh that emphasizes speed, flexibility, and out-of-the-box experience. It's highly customizable and provides instant prompt feedback.

## Contributing

Contributions are welcome! Feel free to open issues and pull requests for improvements or fixes.

1. Fork the project
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

**Made by [Bruno Alves](https://github.com/brunoalvesufu)**
