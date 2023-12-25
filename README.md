# flatlining.github.io

- [Hugo](https://gohugo.io/)
- [Hugo Themes > Hallo](https://themes.gohugo.io/hallo-hugo/)
- [Emoji Favicons > Satellite](https://favicon.io/emoji-favicons/satellite/)
- [Clean Architecture Quotes](https://www.goodreads.com/work/quotes/25319615-clean-architecture)

## Build

```bash
# clone
git clone git@github.com:flatlining/flatlining.github.io.git
# build
hugo
```

## Server

```bash
hugo server --disableFastRender
```

## Publish

```bash
# remove old content
rm -rf docs/*
# build new content
hugo --ignoreCache -d docs
# commit new content
git add docs/*
git commit -m "publish: `date --rfc-3339=seconds`"
```
