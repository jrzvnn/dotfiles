# Dotfiles
dotfiles are what most Linux enthusiasts call configuration files.

![preview](./.screenshots/Screenshot%20from%202021-01-28%2021-09-34.png)

![preview](./.screenshots/2021-01-11-232800_1366x768_scrot.png)

![preview](./.screenshots/2021-01-28-210806_1366x768_scrot.png)

![preview](./.screenshots/2024-08-19_18-54.png)

This repository contains configuration files for various tools and applications that I use on my personal computer. These configuration files, also known as "dotfiles," are named with a leading . and are stored in the home directory (~/) of the user.

## Contents
* `.bashrc`: configuration file for the Bash shell, which is the default shell on most Linux systems.
* `.vimrc`: configuration file for the Vim text editor.
* `i3`: configuration files for the i3 window manager, which is a tiling window manager for Linux.
* `neofetch`: configuration file for the Neofetch system information tool.
* `rofi`: configuration file for the Rofi application launcher and window switcher.
* `alacritty`: Configuration file for the Alacritty terminal emulator.
* `lvim`: Configuration files for LunarVim, an extensible and customizable IDE layer for Neovim.
* `starship`: Configuration file for the Starship prompt, which provides a fast and customizable prompt for various shells.
* `zed`: Configuration files for the Zed editor, including keymap, settings, and themes.

## File Structure
```bash
├── .config
│   ├── alacritty
│   │   └── alacritty.toml
│   ├── i3
│   │   └── config
│   ├── lvim
│   │   ├── config.lua
│   │   └── lazy-lock.json
│   ├── neofetch
│   │   └── config.conf
│   ├── rofi
│   │   └── config
│   ├── starship
│   │   └── starship.toml
│   └── zed
│       ├── keymap.json
│       ├── settings.json
│       └── themes
├── .bashrc
├── .vimrc
└── .zshrc
```

## Usage
To use these dotfiles on your own system, simply clone this repository and move the configuration files to the appropriate locations in your home directory. For example, to use the `.bashrc` file, copy it to `~/.bashrc`.

Keep in mind that these configuration files may contain personalization and customization specific to my own setup and preferences. You may want to review and modify the files to suit your own needs before using them.

## License
This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.

## Contact
Feel free to reach out through [LinkedIn](https://www.linkedin.com/in/jrz-vnn/) if you have any questions or need further information.
