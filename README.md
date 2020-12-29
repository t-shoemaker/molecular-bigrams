# Molecular Bigrams
This notebook visualizes words using letter bigram data for the entire Google Books corpus. The thickness, or weight, of the edges that connect each node represents the frequency values for pairs of letters in a word. For now, if a word has a bigram that appears more than once, like "Mississippi," only one instance of the bigram gets counted as node. Node layout is handled automatically with Fruchterman-Reingold.

Data available for:

* Google Books (from Peter Norvig's ["English Letter Frequency Counts"](https://norvig.com/mayzner.html))
* Project Gutenberg (via Allison Parrish's [Gutenberg, dammit](https://github.com/aparrish/gutenberg-dammit); forthcoming)
* [Wordfreq](https://github.com/LuminosoInsight/wordfreq) (sampling of 25,000 words)

[![Binder](https://mybinder.org/badge_logo.svg)](https://gesis.mybinder.org/binder/v2/gh/t-shoemaker/molecular-bigrams/346812623712f78e93ebfc759ee369e43058c108)

- - -

To do:
* ~~Add bigram data for a different corpus~~
* Handle self-loops ("oo," "aa," etc.)
* ~~Do a version with Markov sequences~~
