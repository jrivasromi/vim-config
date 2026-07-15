**This repo is supposed to used as config by NvChad users, this is my particular nvim config if you find it useful**

- The main nvchad repo (NvChad/NvChad) is used as a plugin by this repo.
- So you just import its modules , like `require "nvchad.options" , require "nvchad.mappings"`
- So you can delete the .git from this repo ( when you clone it locally ) or fork it :)

Requires neovim=>0.11
usage:
```
# remove default nvim config
rm -rf .config/nvim
cd .config/nvim
git clone https://git.jrivas.net/ale/vim-config .
```
Run `:MasonInstallAll` and `:Lazy sync`
# Credits

1) Lazyvim starter https://github.com/LazyVim/starter as nvchad's starter was inspired by Lazyvim's . It made a lot of things easier!
