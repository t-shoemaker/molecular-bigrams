# Molecular Bigrams
These notebooks visualize words using letter bigram data. The thickness, or weight, of the edges that connect each node represents either the frequency values for pairs of letters in a word (`molecularBigrams`), or the probability that one letter will follow the next in a letter pair (`markovBigrams`). At the moment, the frequency notebook only registers one instance of self-looping bigrams ("oo", "aa", etc.). Node layout for frequency values is handled automatically with Fruchterman-Reingold; bigram probabilities are visualized with linear plots.

Data available for:

* Google Books (from Peter Norvig's ["English Letter Frequency Counts"](https://norvig.com/mayzner.html))
* English words from Allison Parrish's [Gutenberg, dammit](https://github.com/aparrish/gutenberg-dammit) (includes words that appear more than 100 times)
* [Wordfreq](https://github.com/LuminosoInsight/wordfreq) (sampling of 25,000 words)

A version of `molecularBigrams` is also available [on my website](https://tylershoemaker.info/misc/bigram_networks/).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/t-shoemaker/molecular-bigrams/62d27fe472cd9024e9698cd183c9d68b937f3ff7)

- - -

To do:
* ~~Add bigram data for a different corpus~~
* ~~Handle self-loops ("oo," "aa," etc.)~~ (all but the Python Jupyter Notebook)
* ~~Do a version with Markov sequences~~
