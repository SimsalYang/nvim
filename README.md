# neoVim configs

my personal neoVim configs.

## Usage

### Windows

Clone this repository to your `LOCALAPPDATA` folder:

```
git clone https://github.com/SimsalYang/nvim "$env:LOCALAPPDATA\nvim"

```

Install `packer.nvim`:

```
git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"

```

then exec `nvim +PackerSync` to install plugins.

### Linux

Clone this repository to '~/.config/nvim' folder, then execute `nvim`, waiting
`packer.nvim` plugin install itself completed. That's ALL, have fun!

> If the `packer.nvim` auto install do not run, open nvim and execute 
`PackerSync` in commander line.
