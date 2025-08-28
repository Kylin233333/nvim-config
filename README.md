# 配置文件使用

Nvim 的配置目录在 ` ~/.config/nvim `下。在 Linux/Mac 系统上，Nvim 会默认读取` ~/.config/nvim/init.lua `文件，理论上来说可以将所有配置的东西都放在这个文件里面，但这样不是一个好的做法，因此我划分不同的文件和目录来分管不同的配置

配置 Nvim 之后，目录结构看起来会是这样⬇️

```
.
├── init.lua
└── lua
    ├── colorscheme.lua
    ├── keymaps.lua
    ├── lsp.lua
    ├── options.lua
    └── plugins.lua    
```

[参考文献:MartinLwx's blog](https://martinlwx.github.io/zh-cn/config-neovim-from-scratch/)
