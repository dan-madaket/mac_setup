# mac_setup
setting up a new macbook pro for development; might as well record this for next time

Credits to all the pages I browsed when assembling this list, most notably:
* http://alexw.me/2013/10/definitive-guid-to-development-mac-setup/
* https://github.com/mathiasbynens/dotfiles
* https://mallinson.ca/osx-web-development/

#####Xcode, naturally
```bash
xcode-select --install
```

#####Install Homebrew
```bash
ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
brew doctor

which brew
sudo nano /etc/paths
```
add path to paths.  It will probably be something like: /usr/local/bin/brew

```bash
<<<<<TRY git, python, ruby>>>>>
brew install node
```


####Custom DotFiles
I forked this sweeeet [custom DotFiles configuration](https://github.com/mathiasbynens/dotfiles)

[Mine](https://github.com/dpxxdp/dotfiles)

Fork the original before using, these contain personally preferred settings.


####Apps
[Firefox]()
[iTerm 2](https://www.iterm2.com/)
[SizeUp](http://www.irradiatedsoftware.com/sizeup)
[Dash](https://kapeli.com/dash)
[Alfred](https://www.alfredapp.com/) settings in dropbox
[XtraFinder](https://www.trankynam.com/xtrafinder/) settings in dropbox
[MacDown](http://macdown.uranusjr.com/)
[PIA](https://www.privateinternetaccess.com/)
[Dropbox](https://dropbox.com)


####ITerm 2 Setup
Using Tomorrow Night Blue for theme:  https://github.com/chriskempson/tomorrow-theme
