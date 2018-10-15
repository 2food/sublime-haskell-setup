# sublime-haskell-setup
My setup for making a working haskell development environment with sublime text 3.

Steps:
1. Install/upgrade stack:
```
curl -sSL https://get.haskellstack.org/ | sh
```
2. Install cabal:
```
$ stack install cabal-install
$ cabal update
```
2. Install stylish-haskell hindent:
```
$ stack install stylish-haskell hindent
```
3. Install [haskell-ide-engine](https://github.com/haskell/haskell-ide-engine#installation)
3. Install [Sublime Text](https://www.sublimetext.com/3)
4. Install the [Sublime Package Control package](http://wbond.net/sublime_packages/package_control/installation)
5. Use Package Control to install LSP.
6. [Configure haskell-ide-engine to work with Sublime](https://github.com/haskell/haskell-ide-engine#using-hie-with-sublime-text)
