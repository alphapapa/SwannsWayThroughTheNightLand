# Update 17 Dec 2014

I have regenerated Swann's Way Through The Night Land using comparison between sentences which uses only relatively uncommon words, under the assumption that these are more meaningful than words generally shared between the two novels in abundance.

See file output/eliminte-common-words.html

Incidentally, I switched some of the code over to the J language. 


# Swann's Way Through The Night Land

This project uses word2vec (ancillarily) and Emacs Lisp to generate a
new novel by substituting similar sentences from one novel for the
sentences of another.  The structure of the first is preserved, but
the content becomes like the second.

See the file output/swanns-way-through-the-night-land.txt for an
example.

[Word2Vec](https://code.google.com/p/word2vec/) was used to produce
word vectors based on the data set created by concatenating the words
from [Swann's Way](http://en.wikipedia.org/wiki/In_Search_of_Lost_Time) with those of [The Night Land](http://en.wikipedia.org/wiki/The_Night_Land).  

This technique is a textual transposition of my previous generative
art-work: [Meat is Mulder](http://procyonic.org/meatIsMulder/meatIsMulder.html).

# About the Author

[Procyonic](http://procyonic.org).

