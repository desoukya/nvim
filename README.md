#neovim setup

1. arch -arm64 brew install neovim

2. arch -arm64 brew install jesseduffield/lazygit/lazygit

3. nvim —version

4. add .vimrc https://github.com/desoukya/dot/blob/master/.vimrc

5. add .zshrc https://github.com/desoukya/dot/blob/master/.zshrc

6. cd ~/.config

7. git clone https://github.com/desoukya/nvim.git

8. git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm6

9. Add tmux config: https://github.com/desoukya/dot/blob/master/.tmux.conf

10. Exit tmux config and run `st` to source the config
   
11. Enter the tmux config and run <tmux_leader>+I

12. vim ~/.config/nvim/lua/desoukya/plugins-setup.lua and run <vim_leader>+s (should create /nvim/plugin/packer_compiled.lua)

13. For intel, edit lua/desoukya/plugins_setup.lua and remove "arch -arm64". Also, comment those packages and install. Once packages removed, uncomment those packages with arch -arm64 excluded from run command and install.

14. Enter vim and run ":Mason"
