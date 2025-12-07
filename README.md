# Papaya
More details on how to contribute and about the config schema are following :)

## Translations
How to add translations for another Locale:
1. Copy the translations file of any other existing Locale (`default.xml` = `en`)
2. Name the file according to your Locale's country code ([See here](https://saimana.com/list-of-country-locale-code/), but with a `-` instead of `_`). E.g. `pt` = Portugese (any country), `pt-BR` = Brazilian Portugese.
3. Translate the texts:
	- Translate only `<string "...">[this part]</string>` and do not modify the `name` etc
	- Translations marked with `translatable="false"` do not need to be translated. You can remove the whole line then.
	- `%1$s`, `%d` etc are placeholders for texts which are filled at runtime (`%1$s games` -> `PSP games`). Please keep them and place them where it makes sense in your language.

If you don't know how to use Git, you can also download a translation file, translate it and send it to me somewhere else. Also, don't hesistate to reach out to me if you need more information to contribute with translations. Thank you for contributing! :)
- [mail@sebschaef.com](mailto:mail@sebschaef.com)
- [Discord](https://discord.gg/bv9HTAepTP)
- [Reddit](https://www.reddit.com/user/IllegalArgException/)

## Icons
TBD

## Config - Presets
TBD
