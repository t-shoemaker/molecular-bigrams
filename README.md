# Molecular Bigrams
These notebooks visualize words using letter bigram data. The thickness, or weight, of the edges that connect each node represents either the frequency values for pairs of letters in a word (molecularBigrams), or the probability that one letter will follow the next in a letter pair (markovBigrams). At the moment, the frequency notebook only registers one instance of self-looping bigrams ("oo", "aa", etc.). Node layout for frequency values is handled automatically with Fruchterman-Reingold; bigram probabilities are visualized with linear plots.

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
