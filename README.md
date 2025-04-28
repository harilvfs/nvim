<p align="center"><strong>My Neovim Config (based on Kickstart)</strong></p>

<p align="center"><strong>This is basically a customized version of ChrisTitusTech's Neovim config (<a href="https://github.com/ChrisTitusTech/neovim">link</a>), tweaked for my personal workflow and preferences.</strong></p>

![NVIM](https://raw.githubusercontent.com/harilvfs/nvim/refs/heads/main/preview.webp)

## Features

- **Preconfigured plugins for a better dev experience**
- **Kickstart setup for quick and easy installation**
- **Tuned for speed and a clean look**
- **Custom keymaps to boost productivity**

## Installation

**Clone this repo into your Neovim config folder:**

```bash
git clone https://github.com/harilvfs/nvim ~/.config/nvim
```

## Usage

**1. Open Neovim**

```bash
nvim
```

**2. Install plugins with Lazy.nvim**
```bash
:Lazy sync
```

## Customization

**Feel free to tweak anything you like! Most of the settings and plugins live inside the `lua/` folder and `init.lua`.**

<p align="center"><strong>Here's a quick look at the folder structure:</strong></p>

```shell
neovim
├── doc/
│   ├── kickstart.txt
│   └── tags
├── lua/
│   ├── custom/
│   │   └── plugins/
│   │       ├── themes/
│   │       │   ├── nord.lua
│   │       │   └── onedark.lua
│   │       ├── init.lua
│   │       └── neo-tree.lua
│   ├── kickstart/
│   │   └── plugins/
│   │       ├── autoformat.lua
│   │       └── debug.lua
│   └── keymaps.lua
├── init.lua
├── lazy-lock.json
├── LICENSE
├── preview.webp
└── README.md     
```



