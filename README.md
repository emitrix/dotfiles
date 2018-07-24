## Jaime's dotfiles ##

My configuration files, based on geerlingguy dotfiles. Aslo Minimalist, I use zsh, vim and git configurations. It helps me to save a few thousand keystrokes a day. I'm using theconfig for Mac OS X, I'll try to update for use with Cygwin and Linux in the future to be be pretty flexible.


After download the files and place it on $HOME, need to run the vim vundle 
```bash
  git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
  vim +PluginInstall +qall
  #zsh plugins 
  brew install zsh-syntax-highlighting
  git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
  #zsh themes
  git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k
  git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
  git clone https://github.com/powerline/fonts.git --depth=1
```

## License

MIT / BSD
 
