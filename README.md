# Comic Mono Nerd Font 🦸

This font is a patched version of the [Comic Mono font](https://dtinth.github.io/comic-mono-font/).
It uses the Nerd Fonts [font-patcher](https://github.com/ryanoasis/nerd-fonts#font-patcher) to add a bunch of glyphs from popular icon fonts such as Font Awesome, Devicons, Octicons, and others.

## Attribution

Comic Mono is a font by [Dan T.](https://dtinth.github.io/) and is licensed under the [MIT license](https://dtinth.github.io/comic-mono-font/LICENSE).
[font-patcher](https://github.com/ryanoasis/nerd-fonts/) is a tool by [Ryan L McIntyre](https://ryanlmcintyre.com/) and is licensed under the [MIT license](https://github.com/ryanoasis/nerd-fonts/blob/master/LICENSE)

## License

This font is licensed under the [MIT license](./LICENSE).

## Patch your own font

1. Install `fontforge`
2. Download the font-patcher script from the [Nerd Fonts repo](https://github.com/ryanoasis/nerd-fonts#font-patcher) or [website](https://www.nerdfonts.com) (scroll to the bottom).
3. Unzip the download and navigate to the directory.
4. Download the font you want to patch.
5. Execute the patcher

```bash
fontforge --script ./font-patcher --complete --also-windows ./PATH_TO_FONT.ttf
```
