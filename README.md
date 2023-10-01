This is the source for my [personal website](https://lewis-weinberger.github.io/index.html),
which is hosted on [GitHub Pages](https://github.com/lewis-weinberger/lewis-weinberger.github.io).

It is generated using [Hakyll](https://jaspervdj.be/hakyll/), and thus requires
[Haskell](https://www.haskell.org/downloads/).

To generate the site contents:

```sh
git clone https://github.com/lewis-weinberger/website.git
cd website
cabal install
site build
site watch
```

A previous iteration can be found at
[lewis-weinberger/haunt-website](https://github.com/lewis-weinberger/haunt-website)
