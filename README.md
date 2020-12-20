# babel-iast
Mapping for Sanskrit romanized according to [IAST](https://en.wikipedia.org/wiki/International_Alphabet_of_Sanskrit_Transliteration) for Unicode-Devanagari

## Dependencies
babel>=3.44

## Usage
1. Include `\usepackage{babel-iast}` the preamble of your LaTeX-file after loading babel,
2. specify a font for the `iast` language, for instance `\babelfont[iast]{rm}[Renderer=Harfbuzz]{DevanagariMT}`,
3. while encoding with `iast` language support active, you can use the hyphen character (-) to separate words or morphems that should be written continuously in Devanagari. Currently babel does not support [whitespace-replacement before hyphenation](https://github.com/latex3/babel/wiki/What's-new-in-babel-3.44#preliminary-code-for-babelprehyphenation), so this is rather a workaround that should at some point be replaced with a rule mapping the proper separation of words in the romanization to the usual word separation of the Indian script.
