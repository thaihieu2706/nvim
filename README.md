# nvim
Requirements
Neovim (version >= 0.6.0 or nightly version), run nvim -v to check neovim version.
xclip or xsel (copy/paste support)
Tree-sitter.
Ripgrep.
A terminal that supports nerdfonts.
Installation
Step 1: Run this following command:

git clone https://github.com/wbthomason/packer.nvim ~/.local/share/nvim/site/pack/packer/start/packer.nvim
Step 2: Run these following commands (back up your config if you already had one):

rm -rf ~/.config/nvim
git clone https://github.com/justanoobcoder/nvim.git ~/.config/nvim
Step 3: Run this following command:

nvim +PackerInstall
Step 4: Neovim will be opened. It may show error at first but don't worry, just press Enter. It will ask you something like OK to remove?, just press Enter. Then wait for Packer install all plugins. When the plugins are installed, you can close neovim.

Step 5: Enjoy :)

Optional
If you're a C/C++ programmer, you may want to install clang for C/C++ language support. Neovim will provide you some autocompletion, errors, warnings,... when you code C/C++ programs.
