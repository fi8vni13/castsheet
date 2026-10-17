# CastSheet

Character reference sheets for AI production: describe a character, get a consistent
three-view sheet (front · side · back) and a 2×2 expression grid, generated free by
the [Pollinations](https://pollinations.ai) image API. Same seed = same face across boards,
so the sheets drop straight into video-model reference workflows.

[![Made with pollinations.ai](https://raw.githubusercontent.com/pollinations/pollinations/main/packages/ui/src/brand/badge-made-with.svg)](https://pollinations.ai/?ref=badge)

## Live app

https://fi8vni13.github.io/castsheet/

## Use

Open the app, describe your character, pick a style, hit **Generate boards**.
URL params prefill a fixed sheet you can share:

```
https://fi8vni13.github.io/castsheet/?desc=your+character&seed=12345
```
