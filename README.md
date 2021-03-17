# Gruvbox Theme for Hugo

![Hugo Gruvbox Theme screenshot](https://raw.githubusercontent.com/deadl0ckio/hugo-gruvbox-theme/main/images/screenshot.png)

## Installation

Once inside your website folder, run the following to install:

```
$ mkdir themes
$ git clone https://github.com/deadl0ckio/hugo-gruvbox-theme themes/hugo-gruvbox-theme --depth=1
```

Or by using Git submodules install via:

```
$ git submodule add https://github.com/deadl0ckio/hugo-gruvbox-theme.git themes/hugo-gruvbox-theme --depth=1
```

## Customisation

In order to edit the homepage you will first need to do the following:

```
$ mkdir -p layouts/partials
$ cp themes/hugo-gruvbox-theme/layouts/partials/hero.html layouts/partials/hero.html
```
From there you can edit as you wish.

Theme supports [Font Awesome](https://github.com/FortAwesome/Font-Awesome) fonts.

## Thanks To

Adapted from [Base16-eighties theme](https://github.com/deadl0ckio/hugo-base16-theme).
