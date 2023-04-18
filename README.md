# flatlining.github.io

- [Hugo](https://gohugo.io/)
- [Hugo Themes > Hallo](https://themes.gohugo.io/hallo-hugo/)
- [Emoji Favicons > Satellite](https://favicon.io/emoji-favicons/satellite/)
- [Clean Architecture Quotes](https://www.goodreads.com/work/quotes/25319615-clean-architecture)

## Build

```bash
$ git clone git@github.com:flatlining/flatlining.github.io.git
# download theme
$ git submodule init
$ git submodule update
# update theme
$ git submodule update --remote --rebase
# build
$ hugo
```

## Serve

```bash
hugo server --disableFastRender
```

## Publish

```bash
$ hugo --ignoreCache
$ git checkout --orphan gh-pages
$ git push --force --set-upstream origin gh-pages
```
