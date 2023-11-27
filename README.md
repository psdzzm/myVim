# SpaceVim

![Release](https://img.shields.io/badge/Release-2.2.0-8700FF.svg)
![GPLv3 License](https://img.shields.io/badge/license-GPLv3-blue.svg)

SpaceVim is a community-driven distribution of Vim and Neovim.
It's inspired by spacemacs. It manages collections of plugins in layers,
which help to collect related packages together to provide features.
This approach helps keep the configuration organized and reduces
overhead for the user by keeping them from having to think about
what packages to install.

- [Quick start guide](https://spacevim.org/quick-start-guide/): installation, configuration, and learning resources for SpaceVim
- [Documentation](https://spacevim.org/documentation/): the primary official documentation of SpaceVim
- [Available layers](https://spacevim.org/layers/): a list of available layers which can be used in SpaceVim

## Installation
```bash
sudo add-apt-repository ppa:neovim-ppa/stable -y
sudo apt install neovim
curl -sLf https://spacevim.org/install.sh | sed "s/gitlab.com\/SpaceVim\/SpaceVim.git/github.com\/psdzzm\/myVim.git --depth=1/g" | bash && ln -s "$HOME/.SpaceVim/SpaceVim.d" "$HOME/.SpaceVim.d"
```

## Community

- English: [https://spacevim.org/community/](https://spacevim.org/community/)
- Chinese: [https://spacevim.org/cn/community/](https://spacevim.org/cn/community/)


<!-- vim:set nowrap: -->
