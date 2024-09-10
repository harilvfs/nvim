<p align="center"> <strong>Neovim Configuration with Kickstart</strong>  </p> 

<p align="center"> <strong>This repository contains my personal Neovim configuration, enhanced with Kickstart for a fast and streamlined setup.
</strong>  </p>

![NVIM](https://raw.githubusercontent.com/aayushx402/neovim/main/preview.webp)

## Features

- **Preconfigured plugins for enhanced development**
- **Kickstart integration for easy setup**
- **Optimized for performance and aesthetics**
- **Custom key mappings for improved workflow**

## Installation

**Clone the repository into the config directory**

```bash
git clone https://github.com/aayushx402/nvim ~/.config/nvim
```

## Usage

**1. Launch Neovim**

```bash
nvim
```

**2. Install plugins using Lazy.nvim**
```bash
:Lazy sync
```

## Customization

**Feel free to customize the configuration by editing the files in the `lua/` and `init.lua` as per your preferences.**

<p align="center"> <strong>Quick overview of the repository structure:</strong>  </p>

```shell
neovim
├── doc/                      
│   ├── kickstart.txt         
│   ├── tags                       
├── init.lua                  
├── lua/                      
│   ├── custom
│   │   ├── plugins
│   │   │   ├── themes
│   │   │   └── nord.lua
│   │   │   └── onedark.lua
│   │   └──init.lua
│   │   └──neo-tree.lua
│   │          
│   ├── kickstart
│   │   ├── plugins
│   │   └──  autoformat.lua
│   │   └── debug.lua
│   └── keymaps.lua          
├── .stylua.toml              
└── lazy-lock.json            
```



