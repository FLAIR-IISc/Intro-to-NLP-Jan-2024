# Template for Class Projects

Template and style files for the project. 

## A Few Tips about Writing

There's a lot written about writing. Some of the excellent pieces that I benefited from include:


1. [Heuristics for Scientific Writing (a Machine Learning Perspective)](https://www.approximatelycorrect.com/2018/01/29/heuristics-technical-scientific-writing-machine-learning-perspective/)
2. [Write the Paper First: Advice by Jason Eisner](https://www.cs.jhu.edu/~jason/advice/write-the-paper-first.html)
3. [The Elements of Style](https://en.wikipedia.org/wiki/The_Elements_of_Style)
4. [Bryson's Dictionary of Troublesome Words: A Writer's Guide to Getting It Right](https://www.penguinrandomhouse.com/books/20556/brysons-dictionary-of-troublesome-words-by-bill-bryson/)

I strongly recommend that people read at least the first two links above.


LaTeX typesetting advice:

1. [Usage notes](https://www.read.seas.harvard.edu/~kohler/latex.html)
2. [A Short Guide on Typesetting Math in NLP](http://demo.clab.cs.cmu.edu/cdyer/short-guide-typesetting.pdf)

I highly recommend that people read both these links.

## Tips

I'm adding some additional tips that I've found useful:

- **Use concrete and specific verbs**: This is arguably the most useful tip I have to share. When communicating, use concrete and specific verbs instead of generic counterparts. You should remind yourself of this tip, whenever you notice verbs like: "did", "have", "work", etc. Let me elaborate with a few examples:
  - "She said she will not comment on the news" --> "She _declined_ to comment on the news"
  - "He foolishly wasted the presented opportunity" -->  "He _squandered_ the presented opportunity ".
  - "I am now friends with .." --> "I _befriended_ ... "

Sometimes you can just use the verb form of the noun, e.g.,
  - "made a new connection" --> "connected with"


In scientific writing, you should familiarize with at least these verbs (and know the subtle differences among them): yield, confer, gain, degrade, proclaim, claim, pose, propose, present, suggest, recommend, speculate, hypothesize, warrant, caution, concern, assess, examine, investigate, comprehend, qualify, combat, alleviate, mitigate, exacerbate, aggravate, impact, influence, degrade, etc.

## Checklist

I've curated a **basic** checklist that you should verify before submitting:

- [ ] Do all figures have readable captions? The minimum font should be 9 pts, 10 pts is better.
- [ ] For people reading *just the caption* of your tables/figures, is there a take-home message?
- [ ] Are the numbers rounded to one significant digit? You don't have to report an accuracy of `0.23429`, just say 23.4%.
- [ ] Do you have footnotes lurking in the middle of sentences? Except for rare circumstances, footnotes come _after_ the sentence: The footnote index should appear above the period symbol.<sup>1</sup>
- [ ] Is the paper (except for the conclusion) written in present tense? ("We observe", "We report", "We find", and not "We observed/found")
- [ ] Do you all the figures have a label? (For tables use prefix "tbl:", like "tbl:summary_of_results", and similarly for figures, use "fig:", as your prefix.)
- [ ] Are are the tables and figures referenced in the text at least once?
- [ ] Are all the numbers in mathcase? For instance, say $23.4$ instead of 23.4 (Yes, it makes a difference).


### Acknowledgments

The style files are adapted from the Conference on Language Models (COLM). 
For detailed acknowledgments, please see the style file.


