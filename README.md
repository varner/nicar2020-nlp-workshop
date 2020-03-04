## NICAR 2020: Finding the story: Using natural language processing (advanced)

### Description

Ever felt lost poring over a massive archive? Want to churn up interesting stories from social networks, chat archives, or forums with (relative) ease?

Why not try using a little natural language processing (NLP)!

This session will give you a taste of how to apply a blend of linguistics and AI to the text-based world of the internet. You will learn some basic NLP concepts, and how to apply them to online texts using the Python package spacy.  You'll be able to walk out of this session ready to start digging through data of your own!

To get the most out of this session, comfort in Python is ideal.

The material from this workshop is based off of curriculum from Advanced Data Journalism, co-taught by Lam Thuy Vo and Maddy Varner at the [Craig Newmark Graduate School of Journalism](https://www.journalism.cuny.edu/), Fall 2019.

- The presentation slides for this workshop can be found [here](https://docs.google.com/presentation/d/135HEZHdgMt-kAuPR1uE6r_TC1ZKSUOgEMh7monZAC-o/edit?usp=sharing)
- A mirror of this is available [here](https://github.com/varner/nicar2020-nlp-workshop)
- Want even MORE ways to investigate the social web? Check out Lam's book, [_Mining Social Media_](https://nostarch.com/miningsocialmedia)!

### Installation

This workshop uses Jupyter notebooks and python3. To install the relevant packages, run: 

`pip install -r requirements.txt`

This workshop uses `spacy`, a natural language processing package for python. We use a pre-trained English-language model. To download, run: 

`python3 -m spacy download en_core_web_sm`
