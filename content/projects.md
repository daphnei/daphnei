Title: Projects
Date: 2010-12-03 10:20
Modified: 2010-12-05 19:30
Category: Projects
Slug: projects
Authors: Daphne Ippolito
Summary: About me

This page lists my ongoing and past research projects that I am excited by.

To see a full list of my papers, check out my [Google Scholar profile](https://scholar.google.com/citations?user=COEsqLYAAAAJ&hl=en&oi=ao).

## Language Model Memorization
[paper](https://arxiv.org/abs/2107.06499) | [code](https://github.com/google-research/deduplicate-text-datasets)  
Large language models memorize their training data.
This is bad for many reasons.
We have so far shown that deduplicating the training set can signifiantly reduce memorization caused by an example being in the dataset many times.
We are continuing to study the properties of LM memorization, including membership inference attacks, the impact of decoding staretgy and prompt choice on whether memorized content surfaces, and training strategies to control the amount of memorization. 

## Building Tools for Creative Writing
[paper on Wordcraft](https://arxiv.org/abs/2107.07430) | [paper on style transfer](https://arxiv.org/abs/2109.03910)
Can natural language generation systems be used to build tools for creative writing? Controllable rewriting, text elaboration and expansion,
and plot ideation are all tasks that NLG might be able to assist with. We are especially interested in investigating how creative writers interact
with and perceive such tools.

## The Real or Fake Text Game
[play](http://roft.io/) | [demo paper](https://arxiv.org/abs/2010.03070) | [code](https://github.com/kirubarajan/roft/)   
Are you able to detect when a passage of text transitions from being being human-written to being machine-generated? Test out your skills on RoFT, the Real or Fake Text game.
The data from our game will be used to answer questions about how factors like genre, and decoding strategy, and annotator training impact the detectability of machine-generated text.

## The Diversity-Quality Tradeoff
[paper on diverse decoding strategies](https://arxiv.org/abs/1906.06362) | [paper on detection of machine-generated text](https://arxiv.org/abs/1911.00650)  
It's possible to generate diverse text with a neural language mdodel or generate text humans perceive as high quality, but even with state-of-the-art language models, it's hard to do both.
We investigate this tradeoff and how it is impacted by choice of decoding strategy.
We also look at the detection problem: how good are humans (and trained classifiers) at detecting when text was generated with a language model?
