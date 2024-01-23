#neovim setup

1. arch -arm64 brew install neovim

2. arch -arm64 brew install jesseduffield/lazygit/lazygit

3. arch -arm64 brew install tmux

4. nvim —version

5. add .vimrc https://github.com/desoukya/dot/blob/master/.vimrc

6. add .zshrc https://github.com/desoukya/dot/blob/master/.zshrc

7. cd ~/.config

8. git clone https://github.com/desoukya/nvim.git

9. git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

10. Add tmux config: https://github.com/desoukya/dot/blob/master/.tmux.conf

11. Start tmux by running `tmux` in the terminal

12. Inside tmux, run `st` to source the config
   
13. Enter the tmux config and run <tmux_leader>+I

14. vim ~/.config/nvim/lua/desoukya/plugins-setup.lua and run <vim_leader>+s (should create /nvim/plugin/packer_compiled.lua)

15. For intel, edit lua/desoukya/plugins_setup.lua and remove "arch -arm64". Also, comment those packages and install. Once packages removed, uncomment those packages with arch -arm64 excluded from run command and install.

16. Enter vim and run ":Mason"
