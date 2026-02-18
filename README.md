<div align="center">

# 🍨 Pastel Sorbet

**The Fastfetch Edition**

![Version](https://img.shields.io/badge/version-1.0.0-ff8596?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-6ef298?style=flat-square)
![Flavor](https://img.shields.io/badge/flavor-sweet-ffd85c?style=flat-square)

<p align="center">
  <img src="assets/pastel-sorbet.png" alt="Pastel Sorbet Fastfetch Preview" width="800">
</p>

_A soft, pastel system fetch with rich purples and vibrant accents._

Part of the Pastel Sorbet family: [Neovim](https://github.com/Memnoc/pastel_sorbet.nvim) | [Kitty](https://github.com/Memnoc/pastel-sorbet-kitty) | [Ghostty](https://github.com/Memnoc/pastel-sorbet-ghostty) | [Alacritty](https://github.com/Memnoc/pastel-sorbet-alacritty)

</div>

---

<p align="center">
  <a href="#installation">Installation</a> •
  <a href="#features">Features</a> •
  <a href="#palette">Palette</a> •
  <a href="#variants">Variants</a>
</p>

---

## Installation

```bash
mkdir -p ~/.config/fastfetch
cp config-pastel-sorbet.jsonc ~/.config/fastfetch/config.jsonc
```

### Requirements

- [fastfetch](https://github.com/fastfetch-cli/fastfetch)
- A [Nerd Font](https://www.nerdfonts.com/) as your terminal font
- Truecolor terminal support (`echo $COLORTERM` should return `truecolor` or `24bit`)

## Features

- Tree-style grouped modules with box-drawing characters
- Nerd Font icons for every module
- Color-coded sections mapped to the Pastel Sorbet palette
- 24-bit truecolor throughout — no 256-color approximation
- Branded `🍨 Pastel Sorbet` label in output

## Palette

| Section  | Color  | Hex       |
| -------- | ------ | --------- |
| Identity | pink   | `#ff8ed0` |
| System   | blue   | `#7db8ff` |
| Desktop  | cyan   | `#4cf0d8` |
| Hardware | yellow | `#ffd85c` |
| Network  | green  | `#6ef298` |
| Logo     | purple | `#c88df7` |
| Output   | fg_dim | `#cdc8da` |

Full palette reference available in the [Neovim edition](https://github.com/Memnoc/pastel_sorbet.nvim).

## Variants

A default variant without the Pastel Sorbet palette is also included as `config.jsonc`, using standard ANSI colors.

## License

MIT
