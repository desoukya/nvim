## neovim setup

ZSH Setup
```
Reference:  https://www.josean.com/posts/terminal-setup
- git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
- git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
- git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
- To Configure PowerLevel10K:
```
- p10k configure
```

- Steps
```  
1. arch -arm64 brew install neovim

2. nvim —version

3. arch -arm64 brew install jesseduffield/lazygit/lazygit

4. arch -arm64 brew install tmux

5. Install coolnight iTerm theme https://github.com/desoukya/dot/blob/master/coolnight.itermcolors

6. add .vimrc https://github.com/desoukya/dot/blob/master/.vimrc

7. add .zshrc https://github.com/desoukya/dot/blob/master/.zshrc

8. cd ~/.config

9. git clone https://github.com/desoukya/nvim.git ~/.config/nvim

10. git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

11. Add tmux config: https://github.com/desoukya/dot/blob/master/.tmux.conf

12. Start tmux by running `tmux` in the terminal

13. Inside tmux, run `st` to source the config
   
14. Enter the tmux config and run <tmux_leader>+I

15. vim ~/.config/nvim/lua/desoukya/plugins-setup.lua and run <vim_leader>+s (should create /nvim/plugin/packer_compiled.lua)
     - If this doesn't work, then use `nvim plugins-setup.lua

17. For intel, edit lua/desoukya/plugins_setup.lua and remove "arch -arm64". Also, comment those packages and install. Once packages removed, uncomment those packages with arch -arm64 excluded from run command and install.

18. Enter vim and run ":Mason"
```
