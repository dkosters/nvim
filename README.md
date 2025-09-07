# My Current nvim Installation

## Requirements + Versions
There is a bash install script ```install_nvim.sh```, you can run it with: ```sh ~/install_nvim.sh```. This, however, does not have proper version control.

- Ubuntu 
```
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 24.04.2 LTS
Release:        24.04
Codename:       noble
```

- Nvim
```
NVIM v0.11.4
Build type: Release
LuaJIT 2.1.1741730670
Run "nvim -V1 -v" for more info
```

Install:
```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux-x86_64.tar.gz
sudo rm -rf /opt/nvim
sudo tar -C /opt -xzf nvim-linux-x86_64.tar.gz
```
Add executable to path (i.e. add the following line to ```~/.bashrc```):
```
export PATH="$PATH:/opt/nvim-linux-x86_64/bin"
```
- luarocks
``` 
/usr/bin/luarocks 3.8.0
LuaRocks main command-line interface
```

Install:
```
sudo apt install luarocks
```

- npm and node 

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```
```
nvm install 16
nvm use 16
```

- tree-sitter-cli
```
npm install -g tree-sitter-cli
```

