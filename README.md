Collection of Sublime Text 3 Plugins
===================

Sublime Text 3 can not work with some plugins, designed for Sublime Text 2. And it's very bad news. But I have solution.

On this page I describe how to install some useful Sublime Text 3 plugins.


Notes
-------

I use MacOS, but you maybe use Windows or Linux. I will describe here differences in how to do something
scepific for your OS, and you can prepare before follow instruction.


#### Go to "Packages" folder

 - MacOS: `~/Library/Application Support/Sublime Text 3/Packages/`
 - Linux: `~/.Sublime Text 3/Packages/`
 - Windows: `%APPDATA%\Sublime Text 3\Packages\`


#### Open "Command palette"

 - MacOS: `⌘` + `⇧` + `P`
 - Linux: `Ctrl` + `Shift` + `P`
 - Windows: `Ctrl` + `Shift` + `P`


#### Other questions

You can read [official Sublime Text documentation](http://docs.sublimetext.info/en/latest/)



Install Sublime Text 3 compatible plugins
--------

#### GIT support in Sublime Text 3

The best plugin is [Git](https://github.com/kemayo/sublime-text-2-git/tree/python3). We have working version in branch `python3`.

 - go to "Packages" folder
 - `git clone https://github.com/kemayo/sublime-text-2-git.git Git`
 - `cd Git`
 - `git checkout python3`
 - Open "Command palette" and type `git:` to see list of commands
