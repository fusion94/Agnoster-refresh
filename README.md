## Agnoster Refresh

### Overview
This is my terminal setup runing [zsh](https://github.com/robbyrussell/oh-my-zsh) with a custom [Agnoster](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/agnoster.zsh-theme) theme in [iTerm 2](http://www.iterm2.com/)

![Screeenshot](https://raw.githubusercontent.com/fusion94/Agnoster-refresh/master/Agnoster-refresh-zsh.png)

### Terminal Application Tweaks

Here are the customizations:
* Font: 11pt [Droid Sans Mono](https://github.com/fusion94/Agnoster-refresh/blob/master/fonts/DroidSansMono.ttf)
* Theme: This is the terminal theme - [Solarized Dark](https://github.com/fusion94/Agnoster-refresh/blob/master/iterm2%20theme/SolarizedDark.itermcolors)
* Cursor: #d13a82

### Shell Tweaks
This makes use of a battery capacity script from stevelosh.com’s blog: batcharge.py.

There is also an online indicator, green for active connection, and red for not.  It’s done by a cronjob touching or removing a file to indicate status every minute, and the file is checked by the prompt: online-check.sh.

### License
Licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

### Credits
This terminal was based off the work of the following [Blog Post](http://remysharp.com/2013/07/25/my-terminal-setup/) by Remy Sharp
