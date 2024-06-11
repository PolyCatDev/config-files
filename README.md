# What is this?

PolyCat's NeoVim config files.

# Features

### Search
Using [Telescope](https://github.com/nvim-telescope/telescope.nvim) for search

### Syntax Highlighting
Using [treesitter](https://github.com/nvim-treesitter/nvim-treesitter)

### Snippets and Code Completion
lua, bash, docker, py, c,js, rust, html and css by default

### Code Formatters
Formatters thru [none-ls](https://github.com/nvimtools/none-ls.nvim) and [Mason](https://github.com/williamboman/mason.nvim)

### File Tree
[nvim-tree](https://github.com/nvim-tree/nvim-tree.lua) as file simple file tree

### Git inegration
[gitsigns](https://github.com/lewis6991/gitsigns.nvim) and [vim-fugitive](https://github.com/tpope/vim-fugitive)

### Remote connections
Thru [remote-nvim](https://github.com/amitds1997/remote-nvim.nvim)

# ATENTION
1. `ripgrep` package is required for live grep in Telescope Search to work
2. `binutils` package is required for Treesitter languages to load
3. `npm` package is required for Bash LSP and others to work

# Installation

```bash
cd ~/.config && \
git clone https://codeberg.org/PolyCat/neovim-config.git && \
mv neovim-config nvim && \
cd ~
```

# To Do

- [ ] Keyboard shortcuts list
