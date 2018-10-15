# sublime-haskell-setup
My setup for making a working haskell development environment with sublime text 3.

Steps:
1. Install/upgrade stack:
```
curl -sSL https://get.haskellstack.org/ | sh
```
2. Install hsdev, stylish-haskell and hindent:
```
$ stack install stylish-haskell hindent
$ stack --resolver lts-9.1 --install-ghc install hsdev-0.2.5.1 
```
3. Install [Sublime Text](https://www.sublimetext.com/3)
4. Install the [Sublime Package Control package](http://wbond.net/sublime_packages/package_control/installation)
5. Use Package Control to install Sublime Haskell.
