# neovim config

Special thanks to https://github.com/nvim-lua/kickstart.nvim

## Path

| OS | PATH |
| :- | :--- |
| Linux | `~/.config/nvim` |
| Windows (powershell)| `$env:USERPROFILE\AppData\Local\nvim\` |

## Installation

- Linux bash
  ```sh
  bash -c 'git clone https://github.com/czM1K3/nvim-config.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim'
  ```

- on Windows (powershell)
  ```
  git clone https://github.com/czM1K3/nvim-config.git $env:USERPROFILE\AppData\Local\nvim\ 
  ```

## Post Installation

- Install packages
  ```sh
  nvim
  ```

- Headlessly install
  ```sh
  nvim --headless "+Lazy! sync" +qa
  ```

