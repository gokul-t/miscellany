# miscellany

## Linux

- Vim
```sh
ln -s ./linux/.vimrc ~/.vimrc;
```

- Code
```sh
cp ./linux/code/settings.json ~/.config/Code/User/settings.json;
cp ~/.config/Code/User/settings.json ./linux/code/settings.json;
```

## Mac

- IdeaVim
```sh
ln -s ./mac/.ideavimrc ~/.ideavimrc
```

## Windows

- PowerToys KeyRemaps
```sh
mklink $env:LOCALAPPDATA\Microsoft\PowerToys\Keyboard Manager\default.json .\windows\power_toys\default.json
```


