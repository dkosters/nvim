# My Current nvim Installation

## Requirements + Versions

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


