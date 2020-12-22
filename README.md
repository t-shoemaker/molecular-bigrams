# Molecular Bigrams
Experiments with letter bigram frequency.

This notebook visualizes words using letter bigram data for the entire Google Books corpus (this data is from Peter Norvig's paper, ["English Letter Frequency Counts"](https://norvig.com/mayzner.html)). The thickness, or weight, of the edges that connect each node represents the frequency values for pairs of letters in a word. For now, if a word has a bigram that appears more than once, like "Mississippi," only one instance of the bigram gets counted as node. Node layout is handled automatically with Fruchterman-Reingold.

- - -

To do:
* Add bigram data for a different corpus
* Handle self-loops ("oo," "aa," etc.)
* ~~Do a version with Markov sequences~~
