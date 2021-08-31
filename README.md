# babel-iast
mapping for Sanskrit romanized in accordance with [IAST](https://en.wikipedia.org/wiki/International_Alphabet_of_Sanskrit_Transliteration) to Unicode-Devanagari

## Dependencies
babel>=3.52

## Usage
1. Include `\usepackage{babel-iast}` in the preamble of your LaTeX-file after loading babel,
2. specify a font for the `iast` language, for instance `\babelfont[iast]{rm}[Renderer=Harfbuzz]{DevanagariMT}`,
3. switch on the `iast` language in your document with `\selectlanguage{iast}` or `\begin{otherlanguage}{iast} … \end{otherlanguage}`.