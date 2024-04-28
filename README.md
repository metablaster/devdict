
# About devdict

A repository hosting custom dictionaries for spell checking of source files usable with
[cSpell](https://github.com/streetsidesoftware/cspell) VScode extension

## License

[![MIT license][badge license]](/LICENSE "View license")

This project `devdict` is licensed under the `MIT` license, 3rd party dictionaries are licensed
under the license that's within their subdirectory

## How to use

Inside `.vscode` directory are `cspell.json` and `settings.json` files with sample configuration which you
can copy to your `VSCode` project and adjust according to your environment.

An important step is to remove `"/Foul/foul.dic"` line from `"ignorePaths"` in `cspell.json`,
this line there makes sense only for this repository.

## Contributing

Contributions are welcome, but only words which don't already exist in [cspell-dicts](https://github.com/streetsidesoftware/cspell-dicts)
to avoid duplication.

Note that words contained in this repository are only those which I personally add from my projects,
therefore my goal here is not a massive dictionary but to cover specific kind of words not already covered by `cSpell`

Please make sure to properly categorize and sort words into correct `*.dic` files, each `*.dic` file
contains comment at the top explaining it's scope.

Sorting of words within dictionaries is done in ascending, case insensitive alphabetical order which
can be easily done with [Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)
extension.

<!-- markdownlint-disable MD053 -->
[badge license]: https://img.shields.io/static/v1?label=License&message=MIT&color=success&style=plastic
<!-- markdownlint-enable MD053 -->
