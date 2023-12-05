#neovim setup

1. arch -arm64 brew install neovim

2. nvim —version

3. add .vimrc https://github.com/desoukya/dot/blob/master/.vimrc

4. add .zshrc https://github.com/desoukya/dot/blob/master/.zshrc

5. cd ~/.config

6. git clone https://github.com/desoukya/nvim.git

7. git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm6

8. Add tmux config: https://github.com/desoukya/dot/blob/master/.tmux.conf

9. Exit tmux config and run `st` to source the config
   
10. Enter the tmux config and run <tmux_leader>+I

11. vim ~/.config/nvim/lua/desoukya/plugins-setup.lua and run <vim_leader>+s (should create /nvim/plugin/packer_compiled.lua)

12. For intel, edit lua/desoukya/plugins_setup.lua and remove "arch -arm64". Also, comment those packages and install. Once packages removed, uncomment those packages with arch -arm64 excluded from run command and install.

13. Enter vim and run ":Mason"
