
# Whiteplain Dark

This is patch [Hugo](https://gohugo.io/) theme.
This is a patch to change [Hugo](https://gohugo.io/) theme [Whiteplain](https://github.com/taikii/whiteplain) to dark mode.

## Installation

```
$ git clone https://github.com/taikii/whiteplain-dark.git themes/whiteplain-dark
```
Or
```
$ git submodule add https://github.com/taikii/whiteplain-dark.git themes/whiteplain-dark
```

## Usage

### Configration

This theme should be used with Whiteplain. You need to write `config.toml` as follows.

```toml
theme = ["whiteplain-dark", "whiteplain"]
```

If you are using `custom.css`, add the following line in the 1st line.

```css
@import url(./whiteplain-dark.css);
```

Other settings depend on [Whiteplain](https://github.com/taikii/whiteplain).

## License
[MIT](LICENSE)
