This is inspired by [yoshiori](https://github.com/yoshiori/oh-my-zsh-yoshiori)
Thanks to the origin author!

## zsh my custom using oh-my-zsh

Because oh-my-zsh is very slow in Cygwin(caused by git and haven't fixed this problem),
I tried to write another config for zsh.  See [zsh-sen](https://github.com/ferminfeng/zshFermin)

### Install
----------------

1. install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

2. cd to your-dir

3. `git clone git://github.com/ferminfeng/zsh-fermin.git`

4. `cd zsh-fermin`

5. configure your favorite plugins in `plugins.conf`, for example:

**(Notice that you may need to remove `vi-mode` plugin if you don't familiar with vim)**

```
# List of plugins, if you don't need some plugins, just comment them by `#`
## Attention: zsh-syntax-highlighting must be the last plugin
git
z
#vi-mode
#docker
#vagrant
zsh-syntax-highlighting
```

6. `./install.sh`

7. `source ~/.zshrc`

### Uninstall
----------------
1. `cd zsh-fermin`

2. `./uninstall.sh`

3. delete plugins related in `~/.zshrc`


```
Warning: plugin zsh-syntax-highlighting not found #7688
https://github.com/ohmyzsh/ohmyzsh/issues/7688

git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting

```