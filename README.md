hakyll-journal
==============

Hakyll Journal is a [Hakyll](http://jaspervdj.be/hakyll/) module for adding a
journal/diary to your static website.

Development
-----------

Hakyll Journal is currently developed using
[GHC](https://www.haskell.org/ghc/) `7.8.3` and should be compatible with
[Haskell Platform](https://www.haskell.org/platform/) `2014.2.0.0`.

A development environment can be setup as follows:

1. `$ mkdir -p ~/projects`
2. `$ cd ~/projects`
3. `$ git clone https://github.com/thunderrabbit/hakyll-journal`
4. `$ cd hakyll-journal`
5. `$ git checkout -b develop`
6. `$ git branch --set-upstream develop origin/develop`
7. `$ git pull`
8. `$ cabal sandbox init`
9. `$ cabal install --only-dependencies`
10. `$ cabal build`
