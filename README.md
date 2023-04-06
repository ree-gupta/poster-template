# Poster Template

This poster template is a modified version of the [Gemini](https://github.com/anishathalye/gemini) LaTeX beamerposter theme.

## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. Modify the Makefile to specify the desired poster orientation and run `make` to build your poster

-----

If you are using the LaTeX Workshop extension for Visual Studio Code, make sure to change the TeX engine to LuaTeX by using the appropriate [recipe](https://github.com/James-Yu/LaTeX-Workshop/wiki/Compile#latex-recipes).


## License

Copyright (c) Anish Athalye. Released under the MIT License. See
[LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Auriga]: https://github.com/anishathalye/auriga
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ
