# Neovim Configuration

This repository contains a custom configuration for Neovim, optimized for plugin management using `lazy.nvim`. The setup includes plugins to enhance the interface, navigation, and code editing experience for various programming languages.

## Project Structure

├── init.lua
├── lazy-lock.json
└── lua
    ├── plugins
    │   ├── catppuccin.lua
    │   ├── neo-tree.lua
    │   ├── telescope.lua
    │   └── treesitter.lua
    └── plugins.lua

## Included Plugins

This configuration includes the following plugins:

- **Catppuccin**: A visually appealing theme to enhance Neovim's appearance.
- **Neo-tree**: A powerful file explorer for easy project navigation.
- **Telescope**: A fuzzy finder to quickly locate files, symbols, and commands.
- **Treesitter**: Advanced syntax highlighting for multiple programming languages.

## Installation

1. **Clone the repository** into your Neovim configuration folder:

   ```bash
   git clone https://github.com/SosoLeJovial/nvim_config ~/.config/nvim
