# Base16 Jardo

This is my terminal colour scheme. It's a high-contrast, dark-on-light theme
and you probably won't like it, but if you work in bright cafes and other
places with lots of glare, it's much easier to read than many of the
alternatives.

## How To

Building requires
[base16-builder](https://github.com/base16-builder/base16-builder), so install
that first. If you need to generate terminal escape sequences to apply the
colours, do this:

```
base16-builder -s ./jardo.yaml -t shell -b dark > colors.zsh
```

I assume you can use this to generate themes for your personal
editor/terminal/tool of choice, but the shell is all I use.
