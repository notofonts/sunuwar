# Sunuwar

## Overview
This Sunuwar font was originally designed for the Unicode proposal. It has been re-engineered to meet meet Noto requirements. The SEI version of the font is located in the `sei` folder. This version can be exported directly using the `.glyphsproject` in the same directory. 

[![][Fontbakery]](https://ScriptEncodingInitiative.github.io/sunuwar/fontbakery/fontbakery-report.html)
[![][Universal]](https://ScriptEncodingInitiative.github.io/sunuwar/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://ScriptEncodingInitiative.github.io/sunuwar/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://ScriptEncodingInitiative.github.io/sunuwar/fontbakery/fontbakery-report.html)
[![][Shaping]](https://ScriptEncodingInitiative.github.io/sunuwar/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FScriptEncodingInitiative%2Fsunuwar%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FScriptEncodingInitiative%2Fsunuwar%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Noto Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FScriptEncodingInitiative%2Fsunuwar%2Fgh-pages%2Fbadges%2FNotoFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FScriptEncodingInitiative%2Fsunuwar%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FScriptEncodingInitiative%2Fsunuwar%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FScriptEncodingInitiative%2Fsunuwar%2Fgh-pages%2Fbadges%2FUniversal.json

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://ScriptEncodingInitiative.github.io/sunuwar.

For information on how to work on Noto fonts, how the build process
works and how to maintain it, see [the README file of the
notofonts.github.io
repository](https://github.com/notofonts/notofonts.github.io/blob/main/README.md)

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL
